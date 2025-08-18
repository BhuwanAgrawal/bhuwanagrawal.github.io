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
<p style="text-align: left;"><a href="Resume_Bhuwan_Agrawal.pdf" download style="color: inherit; text-decoration: none;"><i class='fas fa-file-download'></i> Download Resume (PDF)</a></p>
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
  <div style="margin-top: 5px; font-size: 14px; display: flex; align-items: center; gap: 5px; justify-content: center;">
    <i class="fas fa-certificate"></i>
    ISTQB Certified
  </div>
</a>
</div>
    </div>
  </div>
</div>
<div class="navbar">
  <a href="#career-objective" onclick="openTab('career-objective'); window.location.hash='career-objective'">Career Objective</a>
  <a href="#profile-summary" onclick="openTab('profile-summary'); window.location.hash='profile-summary'">Profile Summary</a>
  <a href="#work-experience" onclick="openTab('work-experience'); window.location.hash='work-experience'">Work Experience</a>
  <a href="#key-projects" onclick="openTab('key-projects'); window.location.hash='key-projects'">Key Projects</a>
  <a href="#technical-skills" onclick="openTab('technical-skills'); window.location.hash='technical-skills'">Technical Skills</a>
  <a href="#certifications" onclick="openTab('certifications'); window.location.hash='certifications'">Certifications</a>
  <a href="#academic-background" onclick="openTab('academic-background'); window.location.hash='academic-background'">Academic Background</a>
</div>

<div id="career-objective" class="containerTab">
  <h2>Career Objective</h2>
  <p>To leverage over 13+ years of experience in software quality assurance and test automation to lead high-performing QA teams, drive continuous improvement, and deliver high-quality digital solutions in a fast-paced environment.</p>
</div>

<div id="profile-summary" class="containerTab activeTab">
  <h2>Profile Summary</h2>
  <p>Quality Assurance Professional with over 13+ years of experience in software testing, automation, and quality management. Proficient in manual and automated testing using tools such as Selenium, Cypress, Ranorex, and TestComplete. Skilled in test case design, defect tracking, team management, and client communication. Proven ability to lead QA teams, deliver high-quality products, and ensure testing best practices.</p>
</div>

<div id="work-experience" class="containerTab">
  <h2>Work Experience</h2>
  <ul>
    <li><i class="fas fa-briefcase"></i> <strong>QA Manager – Bitxia Tech Pvt. Ltd.</strong>, Gurugram (Sep 2022 – July 2025)</li>
    <li><i class="fas fa-briefcase"></i> <strong>Sr. Test Engineer – DLT LABS</strong>, Noida (Jun 2021 – Sep 2022)</li>
    <li><i class="fas fa-briefcase"></i> <strong>Associate Team Lead – Xorlabs.com</strong>, Greater Noida (Mar 2014 – Jun 2021)</li>
    <li><i class="fas fa-briefcase"></i> <strong>Software Test Engineer – Safenet Infotech Pvt. Ltd.</strong> via Magna InfoTech, Noida (Mar 2012 – Mar 2014)</li>
  </ul>
</div>

<div id="certifications" class="containerTab">
  <h2><i class="fas fa-award"></i> Certifications</h2>
  <ul>
    <li><i class="fas fa-certificate"></i> ISTQB Certified Tester – Foundation Level</li>
  </ul>
</div>

<div id="technical-skills" class="containerTab">
  <h2>Technical Skills</h2>
  <ul>
    <li><i class="fas fa-tools"></i> Testing Tools: Selenium, Cypress, Ranorex, TestComplete, QTP</li>
    <li><i class="fas fa-code"></i> Languages: Java, VBScript</li>
    <li><i class="fas fa-project-diagram"></i> Test Management Tools: TestRail, TestLink</li>
    <li><i class="fas fa-bug"></i> Bug Tracking: JIRA, QC, MKS</li>
    <li><i class="fas fa-code-branch"></i> Version Control: SVN, GitHub</li>
    <li><i class="fas fa-database"></i> Database: SQL Server</li>
    <li><i class="fas fa-desktop"></i> Operating Systems: Windows XP/7/10, Windows Server 2008</li>
    <li><i class="fas fa-tasks"></i> Other: Agile Methodologies, Project Planning, Team Leadership, SDLC/STLC, Regression & Functional Testing</li>
  </ul>
</div>

<div id="key-projects" class="containerTab">
  <h2><i class="fas fa-project-diagram"></i> Project Experience</h2>
  <p><strong><i class="fas fa-building"></i> Bitxia Tech Pvt. Ltd.</strong></p>
  <ul>
    <li>eNAM 2.0 (Dec 2024 – July 2025)</li>
    <li>APL Logistics (Apr 2023 – Dec 2024)</li>
    <li>Investor Portal (Sep 2022 – Apr 2023)</li>
    <li>Jarvis Retail Lending (Sep 2022 – Apr 2023)</li>
    <li><strong>Responsibilities:</strong> Team leadership (5–6 QA members), client communication, project estimation, manual testing (functional, regression, GUI), Jira, TestRail</li>
  </ul>
  <p><strong><i class="fas fa-building"></i> DLT LABS</strong></p>
  <ul>
    <li>PPD (DL Asset Track) (Mar 2022 – Sep 2022)</li>
    <li>THOR (DL Asset Track) (Jun 2021 – Feb 2022)</li>
    <li><strong>Responsibilities:</strong> Manual testing of blockchain apps, TestLink, Jira</li>
  </ul>
  <p><strong><i class="fas fa-building"></i> Xorlabs.com</strong></p>
  <ul>
    <li>SQLCM, XMF Automation, CML Configurator, SQL Secure, Uptime, ASD, One Source Configurator, MSQT</li>
    <li><strong>Responsibilities:</strong> Manual & automation testing (Ranorex, Selenium, TestComplete), Jira</li>
  </ul>
  <p><strong><i class="fas fa-building"></i> Safenet Infotech Pvt. Ltd.</strong></p>
  <ul>
    <li>Usage Reporting System, WPS Online, WPS Client</li>
    <li><strong>Responsibilities:</strong> Manual & QTP automation (VBScript), functional, GUI, DB testing, MKS</li>
  </ul>
</div>

<div id="academic-background" class="containerTab" style="margin-bottom: 40px;">
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

    // Update document title
    const titleMap = {
      "career-objective": "Career Objective",
      "profile-summary": "Profile Summary",
      "key-projects": "Key Projects",
      "work-experience": "Work Experience",
      "technical-skills": "Technical Skills",
      "certifications": "Certifications",
      "academic-background": "Academic Background"
    };
    document.title = titleMap[tabName] ? `Bhuwan Agrawal – ${titleMap[tabName]}` : "Bhuwan Agrawal – Resume";
  }
}

// Load default tab from URL or fallback
window.onload = function () {
  const hash = window.location.hash.substring(1);
  const defaultTab = document.getElementById(hash) ? hash : "profile-summary";
  openTab(defaultTab);
}
</script>



</body>
</html>
