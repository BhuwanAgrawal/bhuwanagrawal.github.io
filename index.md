<html>
<head>
<link rel="icon" type="image/png" href="profile.jpg">
<meta name="viewport" content="width=device-width, initial-scale=1">
<script src='https://kit.fontawesome.com/1053334a8a.js' crossorigin='anonymous'></script>
<style>
/* Navbar Styling */
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

/* Tab container styling */
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

/* Header and Responsive */
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

/* Technical Skills Styling */
#technical-skills ul {
  list-style-type: none;
  padding-left: 0;
  margin: 0;
}

#technical-skills li {
  display: flex;
  padding: 4px 0; /* spacing between items */
  flex-wrap: wrap; /* allow wrapping on small screens */
}

#technical-skills li strong {
  flex: 0 0 220px; /* increased width for headings */
  text-align: right;
  margin-right: 15px;
  font-weight: bold;
  color: #2c3e50; /* subtle dark color for headings */
}

#technical-skills li span {
  flex: 1; /* remaining space for values */
  color: #34495e; /* slightly lighter color for values */
}

/* Responsive adjustments for mobile */
@media (max-width: 600px) {
  #technical-skills li {
    flex-direction: column;
    align-items: flex-start;
  }

  #technical-skills li strong {
    text-align: left;
    margin-right: 0;
    margin-bottom: 2px;
    flex: none; /* remove fixed width */
  }

  #technical-skills li span {
    flex: none;
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

<!-- Updated Technical Skills Section -->
<div id="technical-skills" class="containerTab">
  <h2>Technical Skills</h2>
  <ul>
    <li><strong>Testing Tools:</strong> <span>Selenium, Cypress, Playwright</span></li>
    <li><strong>Languages:</strong> <span>Java, Python, JavaScript, TypeScript</span></li>
    <li><strong>Test Management Tools:</strong> <span>TestRail, TestLink</span></li>
    <li><strong>API Testing:</strong> <span>Postman, Playwright</span></li>
    <li><strong>CI/CD Tools:</strong> <span>Jenkins, GitHub Actions</span></li>
    <li><strong>Cloud Testing Platforms:</strong> <span>Browserstack</span></li>
    <li><strong>AI Tools:</strong> <span>Cursor AI, GitHub Copilot</span></li>
    <li><strong>Bug Tracking:</strong> <span>JIRA</span></li>
    <li><strong>Version Control:</strong> <span>SVN, GitHub</span></li>
    <li><strong>Database:</strong> <span>MS SQL Server, Postgres</span></li>
    <li><strong>Operating Systems:</strong> <span>Windows 10/11</span></li>
    <li><strong>Other:</strong> <span>Agile Methodologies, Project Planning, Team Leadership, SDLC/STLC, Regression & Functional Testing</span></li>
  </ul>
</div>

<div id="work-experience" class="containerTab">
  <h2>Work Experience</h2>
  <ul>
    <li><strong>QA Manager</strong> – Bitxia Tech Pvt. Ltd., Gurugram (Sep 2022 – July 2025)</li>
    <li><strong>Sr. Test Engineer</strong> – DLT LABS, Noida (Jun 2021 – Sep 2022)</li>
    <li><strong>Associate Team Lead</strong> – Xorlabs.com, Greater Noida (Mar 2014 – Jun 2021)</li>
    <li><strong>Software Test Engineer</strong> – Safenet Infotech Pvt. Ltd. via Magna InfoTech, Noida (Mar 2012 – Mar 2014)</li>
  </ul>
</div>

<!-- Other sections remain unchanged (key-projects, github-portfolio, certifications, academic-background) -->

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
