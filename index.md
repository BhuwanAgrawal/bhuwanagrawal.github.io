from pathlib import Path

# Full HTML resume with all sections included (completed version)
html_content = r"""
<html>
<head>
<link rel="icon" type="image/png" href="profile.jpg">
<meta name="viewport" content="width=device-width, initial-scale=1">
<script src='https://kit.fontawesome.com/1053334a8a.js' crossorigin='anonymous'></script>
<style>
.navbar {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 8px;
  padding: 10px;
  background-color: #1a5276;
  border-top: 2px solid #f1c40f;
  border-bottom: 2px solid #f1c40f;
  position: sticky;
  top: 0;
  z-index: 1000;
}
.navbar a {
  font-size: 13px;
  padding: 8px 16px;
  color: white;
  background-color: #1a5276;
  text-decoration: none;
  transition: background-color 0.3s, box-shadow 0.3s;
  border: 2px solid transparent;
  border-radius: 20px;
  box-shadow: 0 2px 4px rgba(0,0,0,0.2);
  display: inline-block;
}
.navbar a:hover {
  background-color: #154360;
  border-color: #f1c40f;
}
.navbar a.activeLink {
  background-color: #154360;
  border-color: #f1c40f;
}
.containerTab {
  display: none;
  padding: 20px;
  background: LightSteelBlue;
  color: black;
  opacity: 0;
  transition: opacity 0.5s ease-in-out;
}
.containerTab.activeTab {
  display: block !important;
  opacity: 1;
}
@media screen and (max-width: 768px) {
  .header {
    flex-direction: column;
    align-items: flex-start;
    text-align: left;
  }
  .header > div {
    width: 100%;
  }
  .navbar {
    flex-direction: column;
    align-items: stretch;
  }
  .navbar a {
    text-align: center;
    width: 100%;
  }
}
</style>
</head>
<body>

<!-- Header Section -->
<div style="background-color: LightCyan; padding: 20px;">
  <div style="display: flex; justify-content: space-between; align-items: center; position: relative;">
    <h1 style="margin: 0 auto; font-size: 32px; color: #1a5276; font-family: 'Georgia', serif; text-align: center; flex: 1;">Curriculum Vitae</h1>
  </div>
  <div class="header" style="display: flex; justify-content: space-between; align-items: flex-start; flex-wrap: wrap;">
    <div style="flex: 1 1 60%; min-width: 300px; background-color: #f5f9fc; padding: 15px; border-radius: 10px; border: 1px solid #cfdce6;">
      <h2 style="margin-top: 0; font-size: 28px; font-family: 'Georgia', serif; color: #1a5276; text-align: left;">Bhuwan Agrawal</h2>
      <h4 style="margin-top: -10px; font-family: 'Georgia', serif; color: #1a5276; text-align: left;">QA Manager</h4>
      <p style="text-align: left;"><i class='fas fa-map-marker-alt'></i> B-105 Stellar Mi Citihomes,<br>Omicron 3, Greater Noida, 201310</p>
      <p style="text-align: left;"><i class='fas fa-mobile-alt'></i> 8800149988 | <i class='fa fa-envelope'></i> <a href="mailto:bhuwan83@gmail.com">bhuwan83@gmail.com</a></p>
      <p style="text-align: left;"><i class='fab fa-linkedin'></i> <a href="https://www.linkedin.com/in/bhuwanagrawal" target="_blank" rel="noopener noreferrer">linkedin.com/in/bhuwanagrawal</a></p>
      <p style="text-align: left;"><i class='fab fa-github'></i> <a href="https://github.com/BhuwanAgrawal" target="_blank" rel="noopener noreferrer">github.com/BhuwanAgrawal</a></p>
      <p style="text-align: left;"><a href="Resume_QA_Bhuwan_Agrawal.pdf" download style="color: inherit; text-decoration: none;"><i class='fas fa-file-download'></i> Download Resume (PDF)</a></p>
    </div>
    <div style="flex: 0 1 35%; min-width: 180px; display: flex; flex-direction: column; align-items: center;">
      <div style="margin-bottom: 15px;">
        <img src="profile.jpg" alt="Profile Photo" style="width: 110px; height: 110px; border-radius: 8px; object-fit: cover; object-position: top center; box-shadow: 0 0 8px rgba(0,0,0,0.2); border: 2px solid #1a5276;">
      </div>
      <div style="text-align: center;">
        <a href="https://www.istqb.in/about-us/certified-tester/foundation-level/36257-bhuwan-agrawal" target="_blank" rel="noopener noreferrer">
          <img src="CTFL.png" alt="Certification" style="width: 140px; height: auto; border: 2px solid #1a5276; border-radius: 8px;">
        </a>
        <a href="https://www.istqb.in/about-us/certified-tester/foundation-level/36257-bhuwan-agrawal" target="_blank" rel="noopener noreferrer" style="text-decoration: none; color: #1a5276;" title="View Certification">
          <div style="margin-top: 5px; font-size: 14px; display: flex; align-items: center; gap: 5px; justify-content: center;"><i class="fas fa-certificate"></i> ISTQB Certified</div>
        </a>
      </div>
    </div>
  </div>
</div>

<!-- Navigation -->
<div class="navbar">
  <a href="#career-objective" onclick="openTab('career-objective'); return false;">Career Objective</a>
  <a href="#profile-summary" onclick="openTab('profile-summary'); return false;">Profile Summary</a>
  <a href="#technical-skills" onclick="openTab('technical-skills'); return false;">Technical Skills</a>
  <a href="#work-experience" onclick="openTab('work-experience'); return false;">Work Experience</a>
  <a href="#key-projects" onclick="openTab('key-projects'); return false;">Project Experience</a>
  <a href="#github-portfolio" onclick="openTab('github-portfolio'); return false;">GitHub Portfolio</a>
  <a href="#certifications" onclick="openTab('certifications'); return false;">Certifications</a>
  <a href="#academic-background" onclick="openTab('academic-background'); return false;">Academic Background</a>
</div>

<!-- Sections -->
<div id="career-objective" class="containerTab">
  <h2>Career Objective</h2>
  <p>To leverage over 13+ years of experience in software quality assurance, test automation, and AI-driven testing to architect scalable QA frameworks, mentor engineering teams, and deliver high-quality products through innovative, automation-first, and AI-powered testing strategies across UI, API, database, performance, and non-functional domains.</p>
</div>

<div id="profile-summary" class="containerTab">
  <h2>Profile Summary</h2>
  <p>QA Leader with 13+ years’ experience in automation and quality engineering. Skilled in building scalable QA frameworks across UI, API, DB, and performance testing. Hands-on with Cypress, Playwright, Jenkins and GitHub Actions. Proficient in AI-assisted testing using VS Code with GitHub Copilot and Cursor, driving faster script creation, improved test coverage, and higher efficiency. Strong track record in mentoring teams, defining QA strategy, and ensuring quality-first agile delivery.</p>
</div>

<div id="technical-skills" class="containerTab">
  <h2>Technical Skills</h2>
  <ul>
    <li>Testing Tools: Selenium, Cypress, Playwright</li>
    <li>Languages: Java, Python, JavaScript, TypeScript</li>
    <li>Test Management Tools: TestRail, TestLink</li>
    <li>API Testing: Postman, Playwright</li>
    <li>CI/CD Tools: Jenkins, GitHub Actions</li>
    <li>Cloud Testing Platforms: Browserstack</li>
    <li>AI Tools: Cursor AI, GitHub Copilot</li>
    <li>Bug Tracking: JIRA</li>
    <li>Version Control: SVN, GitHub</li>
    <li>Database: MS SQL Server, Postgres</li>
    <li>Operating Systems: Windows 10/11</li>
    <li>Other: Agile Methodologies, Project Planning, Team Leadership, SDLC/STLC, Regression & Functional Testing</li>
  </ul>
</div>

<div id="work-experience" class="containerTab">
  <h2>Work Experience</h2>
  <ul>
    <li>QA Manager – Bitxia Tech Pvt. Ltd., Gurugram (Sep 2022 – July 2025)</li>
    <li>Sr. Test Engineer – DLT LABS, Noida (Jun 2021 – Sep 2022)</li>
    <li>Associate Team Lead – Xorlabs.com, Greater Noida (Mar 2014 – Jun 2021)</li>
    <li>Software Test Engineer – Safenet Infotech Pvt. Ltd. via Magna InfoTech, Noida (Mar 2012 – Mar 2014)</li>
  </ul>
</div>

<div id="key-projects" class="containerTab">
  <h2>Project Experience</h2>
  <h3>Bitxia Tech Pvt. Ltd.</h3>
  <ul>
    <li><strong>eNAM 2.0 (Dec 2024 – July 2025):</strong> Digital agri-trading platform enabling farmers, traders, and FPOs to buy/sell produce online.<br><em>Contribution:</em> Designed and executed automation framework using Playwright for UI and API automation, ensuring faster regression cycles and improved test coverage.</li>
    <li><strong>APL Logistics COMS Application (Apr 2023 – Dec 2024):</strong> Comprehensive logistics and supply chain management solution.<br><em>Contribution:</em> Implemented Playwright-based automation integrated into CI/CD pipelines, enhancing reliability and reducing manual testing effort.</li>
    <li><strong>Investor Portal (Sep 2022 – Apr 2023):</strong> Web platform for investors.<br><em>Contribution:</em> Developed Cypress automation scripts, reducing manual execution time and ensuring stability across releases.</li>
    <li><strong>Jarvis Retail Lending (Sep 2022 – Apr 2023):</strong> Loan origination and management system.<br><em>Contribution:</em> Built automation suite with Cypress, integrated it into CI/CD pipelines, and introduced AI-assisted testing practices.</li>
  </ul>
  <h3>Responsibilities at Bitxia</h3>
  <ul>
    <li>Led QA team of 5–6 members, managed client communication, estimations, and test delivery.</li>
    <li>Hands-on with Cypress and Playwright for UI/API automation, reducing regression cycle time.</li>
    <li>Owned QA automation architecture across UI, API, DB, performance, and non-functional testing.</li>
    <li>Mentored engineers on automation best practices, frameworks, scripting, and AI-assisted testing.</li>
    <li>Integrated automation frameworks into CI/CD pipelines (Jenkins, GitHub Actions).</li>
    <li>Defined QA governance models, test strategy, and quality standards.</li>
    <li>Collaborated with developers, product managers, and DevOps for agile delivery.</li>
  </ul>
</div>

<div id="github-portfolio" class="containerTab">
  <h2>GitHub Portfolio – Test Automation Projects</h2>
  <ul>
    <li><a href="https://github.com/BhuwanAgrawal/Playwright-Project" target="_blank">Playwright Project</a> – End-to-end automation framework demonstrating UI testing using Playwright.</li>
    <li><a href="https://github.com/BhuwanAgrawal/Cypress-Project" target="_blank">Cypress Project</a> – Test automation suite for functional and regression testing of web applications.</li>
    <li><a href="https://github.com/BhuwanAgrawal/Selenium-KD-Project" target="_blank">Selenium Keyword Driven Project</a> – Keyword-driven automation framework for regression and functional testing.</li>
  </ul>
</div>

<div id="certifications" class="containerTab">
  <h2>Certifications</h2>
  <ul>
    <li>ISTQB Certified Tester – Foundation Level</li>
  </ul>
</div>

<div id="academic-background" class="containerTab">
  <h2>Academic Background</h2>
  <ul>
    <li>MCA – UP Technical University – 64.28%</li>
    <li>BCA – Allahabad Agriculture Institute – 7.96 CGPA</li>
  </ul>
</div>

<script>
function openTab(tabName) {
  const tabs = document.getElementsByClassName("containerTab");
  const links = document.querySelectorAll(".navbar a");
  for (let i = 0; i < tabs.length; i++) {
    tabs[i].classList.remove("activeTab");
  }
  links.forEach(link => link.classList.remove("activeLink"));
  const activeTab = document.getElementById(tabName);
  const activeLink = document.querySelector(`.navbar a[href="#${tabName}"]`);
  if (activeTab) {
    activeTab.classList.add("activeTab");
    if (activeLink) activeLink.classList.add("activeLink");
    window.scrollTo({ top: 0, behavior: 'smooth' });
    const titleMap = {
      "career-objective": "Career Objective",
      "profile-summary": "Profile Summary",
      "technical-skills": "Technical Skills",
      "work-experience": "Work Experience",
      "key-projects": "Project Experience",
      "github-portfolio": "GitHub Portfolio",
      "certifications": "Certifications",
      "academic-background": "Academic Background"
    };
    document.title = titleMap[tabName] ? `Bhuwan Agrawal – ${titleMap[tabName]}` : "Bhuwan Agrawal – Resume";
  }
}
window.onload = function () {
  const hash = window.location.hash.substring(1);
  const defaultTab = document.getElementById(hash) ? hash : "profile-summary";
  openTab(defaultTab);
}
</script>

</body>
</html>
"""

# Save expanded HTML file
output_file = Path("/mnt/data/index_full_expanded.html")
output_file.write_text(html_content, encoding="utf-8")

output_file
