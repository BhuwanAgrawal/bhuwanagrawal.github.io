<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<link rel="icon" type="image/png" href="profile.jpg">
<meta name="viewport" content="width=device-width, initial-scale=1">
<script src='https://kit.fontawesome.com/1053334a8a.js' crossorigin='anonymous'></script>
<title>Bhuwan Agrawal – Resume</title>
<style>
/* Navbar styling */
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
.navbar a:hover, .navbar a.activeLink {
  background-color: #154360;
  border-color: #f1c40f;
}

/* Container tabs */
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

/* Technical skills list */
#technical-skills ul {
  list-style: none;
  padding-left: 0;
}
#technical-skills li {
  display: flex;
  flex-wrap: wrap;
  margin-bottom: 6px;
}
#technical-skills li strong {
  width: 180px; /* Adjust width for alignment */
  text-align: left;
}

/* Header */
.header {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  flex-wrap: wrap;
}

/* Responsive */
@media screen and (max-width: 768px) {
  .header { flex-direction: column; align-items: flex-start; text-align: left; }
  .header > div { width: 100%; }
  .navbar { flex-direction: column; align-items: stretch; }
  .navbar a { text-align: center; width: 100%; }
}

/* Project experience styling */
.company-block, .portfolio-block, .cert-block, .academic-block {
  margin-bottom: 20px;
  padding: 10px 15px;
  background-color: #e8f0f8;
  border-left: 4px solid #1a5276;
  border-radius: 6px;
}
.company-name { color: #1a5276; }
.project-name { color: #154360; font-weight: bold; }
.contribution-list li { list-style-type: disc; margin-left: 20px; color: #34495e; }
.responsibilities-title { margin-top: 10px; font-weight: bold; color: #1a5276; }
.responsibilities-list li { list-style-type: square; margin-left: 20px; color: #2c3e50; margin-bottom: 4px; }

a { color: #154360; text-decoration: none; }
a:hover { text-decoration: underline; }
</style>
</head>
<body>

<!-- Header Section -->
<div style="background-color: LightCyan; padding: 20px;">
  <div style="display: flex; justify-content: space-between; align-items: center; position: relative;">
    <h1 style="margin: 0 auto; font-size: 32px; color: #1a5276; font-family: 'Georgia', serif; text-align: center; flex: 1;">Curriculum Vitae</h1>
  </div>
  <div class="header">
    <div style="flex: 1 1 60%; min-width: 300px; background-color: #f5f9fc; padding: 15px; border-radius: 10px; border: 1px solid #cfdce6;">
      <h2 style="margin-top: 0; font-size: 28px; font-family: 'Georgia', serif; color: #1a5276; text-align: left;">Bhuwan Agrawal</h2>
      <h4 style="margin-top: -10px; font-family: 'Georgia', serif; color: #1a5276; text-align: left;">QA Manager</h4>
      <p style="text-align: left;"><i class='fas fa-map-marker-alt'></i> B-105 Stellar Mi Citihomes,<br>Omicron 3, Greater Noida, 201310</p>
      <p style="text-align: left;"><i class='fas fa-mobile-alt'></i> 8800149988 | <i class='fa fa-envelope'></i> <a href="mailto:bhuwan83@gmail.com">bhuwan83@gmail.com</a></p>
      <p style="text-align: left;"><i class='fab fa-linkedin'></i> <a href="https://www.linkedin.com/in/bhuwanagrawal" target="_blank">linkedin.com/in/bhuwanagrawal</a></p>
      <p style="text-align: left;"><i class='fab fa-github'></i> <a href="https://github.com/BhuwanAgrawal" target="_blank">github.com/BhuwanAgrawal</a></p>
      <p style="text-align: left;"><a href="Resume_QA_Bhuwan_Agrawal.pdf" download style="color: inherit;"><i class='fas fa-file-download'></i> Download Resume (PDF)</a></p>
    </div>
    <div style="flex: 0 1 35%; min-width: 180px; display: flex; flex-direction: column; align-items: center;">
      <div style="margin-bottom: 15px;">
        <img src="profile.jpg" alt="Profile Photo" style="width: 110px; height: 110px; border-radius: 8px; object-fit: cover; object-position: top center; box-shadow: 0 0 8px rgba(0,0,0,0.2); border: 2px solid #1a5276;">
      </div>
      <div style="text-align: center;">
        <a href="https://www.istqb.in/about-us/certified-tester/foundation-level/36257-bhuwan-agrawal" target="_blank">
          <img src="CTFL.png" alt="Certification" style="width: 140px; height: auto; border: 2px solid #1a5276; border-radius: 8px;">
        </a>
        <a href="https://www.istqb.in/about-us/certified-tester/foundation-level/36257-bhuwan-agrawal" target="_blank" style="text-decoration: none; color: #1a5276;" title="View Certification">
          <div style="margin-top: 5px; font-size: 14px; display: flex; align-items: center; gap: 5px; justify-content: center;"><i class="fas fa-certificate"></i> ISTQB Certified</div>
        </a>
      </div>
    </div>
  </div>
</div>

<!-- Navbar -->
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

<!-- Career Objective -->
<div id="career-objective" class="containerTab">
  <h2>Career Objective</h2>
  <p>To leverage over 13+ years of experience in software quality assurance, test automation, and AI-driven testing to architect scalable QA frameworks, mentor engineering teams, and deliver high-quality products through innovative, automation-first, and AI-powered testing strategies across UI, API, database, performance, and non-functional domains.</p>
</div>

<!-- Profile Summary -->
<div id="profile-summary" class="containerTab">
  <h2>Profile Summary</h2>
  <p>QA Leader with 13+ years’ experience in automation and quality engineering. Skilled in building scalable QA frameworks across UI, API, DB, and performance testing. Hands-on with Cypress, Playwright, Jenkins, and GitHub Actions. Proficient in AI-assisted testing using VS Code with GitHub Copilot and Cursor, driving faster script creation, improved test coverage, and higher efficiency. Strong track record in mentoring teams, defining QA strategy, and ensuring quality-first agile delivery.</p>
</div>

<!-- Technical Skills -->
<div id="technical-skills" class="containerTab">
  <h2 style="text-align: left;">Technical Skills</h2>
  <ul>
    <li><strong>Testing Tools:</strong> Selenium, Cypress, Playwright</li>
    <li><strong>Languages:</strong> Java, Python, JavaScript, TypeScript</li>
    <li><strong>Test Management Tools:</strong> TestRail, TestLink</li>
    <li><strong>API Testing:</strong> Postman, Playwright</li>
    <li><strong>CI/CD Tools:</strong> Jenkins, GitHub Actions</li>
    <li><strong>Cloud Testing Platforms:</strong> Browserstack</li>
    <li><strong>AI Tools:</strong> Cursor AI, GitHub Copilot</li>
    <li><strong>Bug Tracking:</strong> JIRA</li>
    <li><strong>Version Control:</strong> SVN, GitHub</li>
    <li><strong>Database:</strong> MS SQL Server, Postgres</li>
    <li><strong>Operating Systems:</strong> Windows 10/11</li>
    <li><strong>Other:</strong> Agile Methodologies, Project Planning, Team Leadership, SDLC/STLC, Regression & Functional Testing</li>
  </ul>
</div>

<!-- Work Experience -->
<div id="work-experience" class="containerTab">
  <h2>Work Experience</h2>
  <ul>
    <li><strong>QA Manager</strong> – Bitxia Tech Pvt. Ltd., Gurugram (Sep 2022 – July 2025)</li>
    <li><strong>Sr. Test Engineer</strong> – DLT LABS, Noida (Jun 2021 – Sep 2022)</li>
    <li><strong>Associate Team Lead</strong> – Xorlabs.com, Greater Noida (Mar 2014 – Jun 2021)</li>
    <li><strong>Software Test Engineer</strong> – Safenet Infotech Pvt. Ltd. via Magna InfoTech, Noida (Mar 2012 – Mar 2014)</li>
  </ul>
</div>

<!-- Project Experience -->
<div id="key-projects" class="containerTab">
  <h2><i class="fas fa-project-diagram"></i> Project Experience</h2>

  <div class="company-block">
    <h3><i class="fas fa-building"></i> <span class="company-name">Bitxia Tech Pvt. Ltd.</span></h3>
    <ul>
      <li><strong class="project-name">eNAM 2.0 (Dec 2024 – July 2025):</strong>
        <ul class="contribution-list">
          <li>Designed and executed automation framework using Playwright for UI and API automation.</li>
        </ul>
      </li>
      <li><strong class="project-name">APL Logistics COMS Application (Apr 2023 – Dec 2024):</strong>
        <ul class="contribution-list">
          <li>Implemented Playwright automation integrated with CI/CD pipelines.</li>
        </ul>
      </li>
      <li><strong class="project-name">Investor Portal (Sep 2022 – Apr 2023):</strong>
        <ul class="contribution-list">
          <li>Developed Cypress automation scripts for functional and regression testing.</li>
        </ul>
      </li>
      <li><strong class="project-name">Jarvis Retail Lending (Sep 2022 – Apr 2023):</strong>
        <ul class="contribution-list">
          <li>Built automation suite using Cypress with AI-assisted testing practices.</li>
        </ul>
      </li>
    </ul>
    <h4 class="responsibilities-title">Responsibilities:</h4>
    <ul class="responsibilities-list">
      <li>Led QA team of 5–6 members; handled client communication, project estimation, and delivery.</li>
      <li>Hands-on automation using Cypress & Playwright for UI and API testing.</li>
      <li>Owned QA automation architecture for UI, API, DB, performance, and non-functional testing.</li>
      <li>Mentored QA engineers on framework design, scripting, and AI-assisted testing.</li>
      <li>Integrated automation frameworks into CI/CD pipelines (Jenkins, GitHub Actions).</li>
      <li>Defined QA governance, test strategy, and quality standards.</li>
      <li>Collaborated with developers, product managers, and DevOps to ensure quality-first agile delivery.</li>
    </ul>
  </div>

  <div class="company-block">
    <h3><i class="fas fa-building"></i> <span class="company-name">DLT LABS</span></h3>
    <ul>
      <li><strong class="project-name">PPD (DL Asset Track) (Mar 2022 – Sep 2022)</strong></li>
      <li><strong class="project-name">THOR (DL Asset Track) (Jun 2021 – Feb 2022)</strong></li>
      <li class="responsibilities-list"><em>Responsibilities:</em> Manual testing of blockchain apps using TestLink and Jira.</li>
    </ul>
  </div>

  <div class="company-block">
    <h3><i class="fas fa-building"></i> <span class="company-name">Xorlabs.com</span></h3>
    <ul>
      <li><strong class="project-name">Projects:</strong> SQLCM, XMF Automation, CML Configurator, SQL Secure, Uptime, ASD, One Source Configurator, MSQT</li>
      <li class="responsibilities-list"><em>Responsibilities:</em> Manual & automation testing (Ranorex, Selenium, TestComplete), Jira.</li>
    </ul>
  </div>

  <div class="company-block">
    <h3><i class="fas fa-building"></i> <span class="company-name">Safenet Infotech Pvt. Ltd.</span></h3>
    <ul>
      <li><strong class="project-name">Projects:</strong> Usage Reporting System, WPS Online, WPS Client</li>
      <li class="responsibilities-list"><em>Responsibilities:</em> Manual & QTP automation (VBScript), functional, GUI, DB testing, MKS.</li>
    </ul>
  </div>
</div>

<!-- GitHub Portfolio -->
<div id="github-portfolio" class="containerTab">
  <h2><i class="fab fa-github"></i> GitHub Portfolio – Test Automation Projects</h2>
  <div class="portfolio-block">
    <ul>
      <li><a href="https://github.com/BhuwanAgrawal/Playwright-Project" target="_blank">Playwright Project</a>
        <ul class="contribution-list"><li>End-to-end UI automation using Playwright.</li></ul>
      </li>
      <li><a href="https://github.com/BhuwanAgrawal/Cypress-Project" target="_blank">Cypress Project</a>
        <ul class="contribution-list"><li>Functional & regression testing suite.</li></ul>
      </li>
      <li><a href="https://github.com/BhuwanAgrawal/Selenium-KD-Project" target="_blank">Selenium Keyword Driven Project</a>
        <ul class="contribution-list"><li>Keyword-driven automation framework.</li></ul>
      </li>
    </ul>
  </div>
</div>

<!-- Certifications -->
<div id="certifications" class="containerTab">
  <h2><i class="fas fa-certificate"></i> Certifications</h2>
  <div class="cert-block">
    <ul>
      <li>ISTQB Certified Tester – Foundation Level</li>
    </ul>
  </div>
</div>

<!-- Academic Background -->
<div id="academic-background" class="containerTab">
  <h2><i class="fas fa-graduation-cap"></i> Academic Background</h2>
  <div class="academic-block">
    <ul>
      <li>MCA – UP Technical University – 64.28%</li>
      <li>BCA – Allahabad Agriculture Institute – 7.96 CGPA</li>
    </ul>
  </div>
</div>

<script>
function openTab(tabName) {
  const tabs = document.getElementsByClassName("containerTab");
  const links = document.querySelectorAll(".navbar a");
  for (let i = 0; i < tabs.length; i++) tabs[i].classList.remove("activeTab");
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
