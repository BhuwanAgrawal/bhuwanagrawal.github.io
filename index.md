<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<script src='https://kit.fontawesome.com/1053334a8a.js' crossorigin='anonymous'></script>
<style>
  body { font-family: Arial, sans-serif; margin: 0; }
  .header, .footer { background-color: LightCyan; padding: 10px; text-align: center; position: relative; }
  .header img { position: absolute; top: 10px; right: 20px; width: 160px; height: auto; }
  .navbar { overflow: hidden; background-color: #333; display: flex; flex-wrap: wrap; justify-content: center; }
  .navbar a { color: white; padding: 14px 20px; text-decoration: none; display: block; text-align: center; }
  .navbar a:hover { background-color: #ddd; color: black; }
  .containerTab { display: none; padding: 20px; background: LightSteelBlue; color: black; }
  ul { padding-left: 20px; }
  h2 { color: darkblue; }
  .activeTab { display: block !important; }
  .header h1 { font-size: 32px; margin-bottom: 5px; }
</style>
</head>
<body>

<div class="header" style="display: flex; flex-wrap: wrap; align-items: center; justify-content: center; gap: 20px; position: relative;">
  <img src="CTFL.png" alt="Certification" style="position: absolute; top: 10px; right: 20px; width: 160px; height: auto;">
  <div style="flex: 1 1 300px; text-align: center;">
    <h1 style="font-size: 32px; margin-bottom: 5px;"><u>CURRICULUM VITAE</u></h1>
    <h2 style="margin-top: 0; font-size: 28px; font-family: 'Georgia', serif; color: #1a5276;">Bhuwan Agrawal</h2>
    <h4 style="margin-top: -10px; font-family: 'Georgia', serif; color: #1a5276;">QA Manager</h4>
    <hr style="width: 60%; margin: 10px auto; border: 1px solid #1a5276;">
  </div>
  <div style="flex: 0 0 auto;">
  <img src="Bhuwan.jpg" alt="Profile Photo" style="width: 140px; height: 140px; border-radius: 8px; object-fit: cover; box-shadow: 0 0 8px rgba(0,0,0,0.2);">
</div>
  <hr style="width: 60%; margin: 10px auto; border: 1px solid #1a5276;">
  <p><i class='fas fa-map-marker-alt'></i> B-105 Stellar Mi Citihomes,<br>Omicron 3, Greater Noida, 201310</p>
  <p><i class='fas fa-mobile-alt'></i> 8800149988 | <i class='fa fa-envelope'></i> <a href="mailto:bhuwan83@gmail.com">bhuwan83@gmail.com</a></p>
  <p><i class='fab fa-linkedin'></i> <a href="https://www.linkedin.com/in/bhuwanagrawal">linkedin.com/in/bhuwanagrawal</a></p>
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

<div id="objective" class="containerTab activeTab">
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
  var x = document.getElementsByClassName("containerTab");
  for (var i = 0; i < x.length; i++) {
    x[i].classList.remove("activeTab");
  }
  document.getElementById(tabName).classList.add("activeTab");
}
</script>

<div class="footer">
  <p><i class='fa fa-download'></i> <a href="Resume_Bhuwan_Agrawal.pdf" download>Download Resume (PDF)</a></p>
</div>

</body>
</html>
