<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<script src='https://kit.fontawesome.com/1053334a8a.js' crossorigin='anonymous'></script>
<style>
.containerTab { display: none; padding: 20px; background: LightSteelBlue; color: black; }
.activeTab { display: block !important; }
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
  }
  .navbar a {
    text-align: left;
    padding-left: 20px;
  }
}
.navbar a {
  padding: 12px 20px;
  color: white;
  background-color: #1a5276;
  text-decoration: none;
  transition: background-color 0.3s, border-bottom 0.3s;
  border-bottom: 3px solid transparent;
}
.navbar a:hover {
  background-color: #154360;
  border-bottom: 3px solid #f1c40f;
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
</style>
</head>
<body>

<div style="background-color: LightCyan; padding: 20px;">
  <h1 style="font-size: 36px; color: #1a5276; letter-spacing: 2px; text-transform: uppercase; text-align: center; margin-bottom: 20px;"><u>Curriculum Vitae</u></h1>
  <div class="header" style="display: flex; justify-content: space-between; align-items: flex-start; flex-wrap: wrap;">
    <div style="flex: 1 1 60%; min-width: 300px; background-color: #f5f9fc; padding: 15px; border-radius: 10px; border: 1px solid #cfdce6;">
      <h2 style="margin-top: 0; font-size: 28px; font-family: 'Georgia', serif; color: #1a5276; text-align: left;">Bhuwan Agrawal</h2>
      <h4 style="margin-top: -10px; font-family: 'Georgia', serif; color: #1a5276; text-align: left;">QA Manager</h4>
      <p style="text-align: left;"><i class='fas fa-map-marker-alt'></i> B-105 Stellar Mi Citihomes,<br>Omicron 3, Greater Noida, 201310</p>
      <p style="text-align: left;"><i class='fas fa-mobile-alt'></i> 8800149988 | <i class='fa fa-envelope'></i> <a href="mailto:bhuwan83@gmail.com">bhuwan83@gmail.com</a></p>
      <p style="text-align: left;"><i class='fab fa-linkedin'></i> <a href="https://www.linkedin.com/in/bhuwanagrawal">linkedin.com/in/bhuwanagrawal</a></p>
    </div>
    <div style="flex: 0 1 35%; min-width: 180px; display: flex; flex-direction: column; align-items: center;">
      <div style="margin-bottom: 15px;">
        <img src="profile.jpg" alt="Profile Photo" style="width: 140px; height: 140px; border-radius: 8px; object-fit: contain; box-shadow: 0 0 8px rgba(0,0,0,0.2);">
      </div>
      <div>
        <img src="CTFL.png" alt="Certification" style="width: 140px; height: auto;">
      </div>
    </div>
  </div>
</div>
<div class="navbar">
  <a href="#objective" onclick="openTab('objective'); window.location.hash='objective'">Objective</a>
  <a href="#summary" onclick="openTab('summary'); window.location.hash='summary'">Summary</a>
  <a href="#experience" onclick="openTab('experience'); window.location.hash='experience'">Experience</a>
  <a href="#projects" onclick="openTab('projects'); window.location.hash='projects'">Projects</a>
  <a href="#skills" onclick="openTab('skills'); window.location.hash='skills'">Skills</a>
  <a href="#certifications" onclick="openTab('certifications'); window.location.hash='certifications'">Certifications</a>
  <a href="#education" onclick="openTab('education'); window.location.hash='education'">Education</a>
</div>

<div id="objective" class="containerTab">
  <h2>Objective</h2>
  <p>To achieve a challenging position in Software Testing and Quality Assurance, leveraging my skills to contribute to the organization's success and personal growth.</p>
</div>

<div id="summary" class="containerTab">
  <h2>Professional Summary</h2>
  <ul>
    <li>13+ years of experience in Software Testing and QA</li>
    <li>Expert in automation tools: Selenium, Cypress, Ranorex, TestComplete</li>
    <li>Strong in manual testing: functional, regression, GUI, database</li>
    <li>Experienced with SDLC/STLC, Agile, test planning, and team leadership</li>
    <li>Tools: Jira, TestRail, TestLink, GitHub, SVN, SQL Server</li>
    <li>Team management, client interaction, project estimation and delivery</li>
  </ul>
</div>

<div id="experience" class="containerTab">
  <h2>Experience</h2>
  <ul>
    <li><b>QA Manager – Bitxia Tech Pvt. Ltd.</b>, Gurugram (Sep 2022 – Present)</li>
    <li><b>Sr. Test Engineer – DLT LABS</b>, Noida (Jun 2021 – Sep 2022)</li>
    <li><b>Associate Team Lead – Xorlabs.com</b>, Greater Noida (Mar 2014 – Jun 2021)</li>
    <li><b>Software Test Engineer – Safenet Infotech Pvt. Ltd.</b> via Magna InfoTech, Noida (Mar 2012 – Mar 2014)</li>
  </ul>
</div>

<div id="certifications" class="containerTab">
  <h2>Certifications</h2>
  <ul>
    <li>ISTQB Certified Tester – Foundation Level</li>
  </ul>
</div>

<div id="skills" class="containerTab">
  <h2>Software Skills</h2>
  <ul>
    <li>Languages: Java, VBScript</li>
    <li>Automation Tools: Selenium, Cypress, Ranorex, TestComplete</li>
    <li>Bug Tracking: Jira, QC, MKS</li>
    <li>Test Management: TestRail, TestLink</li>
    <li>Version Control: SVN, GitHub</li>
    <li>Databases: SQL Server</li>
    <li>OS: Windows XP/7/10, Server 2008</li>
    <li>Office Tools: MS Excel, Word, PowerPoint</li>
  </ul>
</div>

<div id="projects" class="containerTab">
  <h2>Project Experience</h2>
  <p><b>Bitxia Tech Pvt. Ltd.</b> (Sep 2022 – Present)</p>
  <ul>
    <li>eNAM 2.0, APL Logistics, Investor Portal, Jarvis Retail Lending – QA Manager</li>
    <li>Responsibilities: Team leadership, test planning, client interaction, Jira/TestRail usage</li>
  </ul>
  <p><b>DLT LABS</b> (Jun 2021 – Sep 2022)</p>
  <ul>
    <li>PPD & THOR (DL Asset Track) – Manual Testing</li>
    <li>Tools: Jira, TestLink</li>
  </ul>
  <p><b>Xorlabs.com</b> (Mar 2014 – Jun 2021)</p>
  <ul>
    <li>Key Projects: SQLCM, XMF Automation, CML Configurator, SQL Secure, OSC, ASD, MSQT</li>
    <li>Automation: Selenium, Ranorex, TestComplete</li>
  </ul>
  <p><b>Safenet Infotech Pvt. Ltd.</b> (Mar 2012 – Mar 2014)</p>
  <ul>
    <li>Projects: Usage Reporting System, WPS Online, WPS Client</li>
    <li>Manual + QTP (VBScript) Automation, MKS for defect tracking</li>
  </ul>
</div>

<div id="education" class="containerTab">
  <h2>Education</h2>
  <ul>
    <li>MCA – UP Technical University – 64.28%</li>
    <li>BCA – Allahabad Agriculture Institute – 7.96 CGPA</li>
  </ul>
</div>

<script>
function openTab(tabName) {
  const tabs = document.getElementsByClassName("containerTab");
  for (let i = 0; i < tabs.length; i++) {
    tabs[i].classList.remove("activeTab");
  }
  const activeTab = document.getElementById(tabName);
  if (activeTab) {
    activeTab.classList.add("activeTab");
  }
}

// Load default tab from URL or fallback
window.onload = function () {
  const hash = window.location.hash.substring(1);
  const defaultTab = document.getElementById(hash) ? hash : "summary";
  openTab(defaultTab);
}
</script>

<div class="footer">
  <p><i class='fa fa-download'></i> <a href="Resume_Bhuwan_Agrawal.pdf" download>Download Resume (PDF)</a></p>
</div>

</body>
</html>
