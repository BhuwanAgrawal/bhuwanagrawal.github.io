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

<div class="header">
  <img src="CTFL.png" alt="Certification">
  <h1><u>CURRICULUM VITAE</u></h1>
  <h2 style="margin-top: 0; font-size: 26px;">Bhuwan Agrawal</h2>
  <p><i class='fas fa-map-marker-alt'></i> B-105 Stellar Mi Citihomes,<br>Omicron 3, Greater Noida, 201310</p>
  <p><i class='fas fa-mobile-alt'></i> 8800149988 | <i class='fa fa-envelope'></i> <a href="mailto:bhuwan83@gmail.com">bhuwan83@gmail.com</a></p>
  <p><i class='fab fa-linkedin'></i> <a href="https://www.linkedin.com/in/bhuwanagrawal">linkedin.com/in/bhuwanagrawal</a></p>
</div>

<div class="navbar">
  <a href="#b1" onclick="openTab('b1'); window.location.hash='b1'">Objective</a>
  <a href="#b2" onclick="openTab('b2'); window.location.hash='b2'">Summary</a>
  <a href="#b3" onclick="openTab('b3'); window.location.hash='b3'">Experience</a>
  <a href="#b6" onclick="openTab('b6'); window.location.hash='b6'">Projects</a>
  <a href="#b5" onclick="openTab('b5'); window.location.hash='b5'">Skills</a>
  <a href="#b4" onclick="openTab('b4'); window.location.hash='b4'">Certifications</a>
  <a href="#b7" onclick="openTab('b7'); window.location.hash='b7'">Education</a>
</div>

<div id="b1" class="containerTab activeTab">
  <h2>Objective</h2>
  <p>To achieve a challenging position in Software Testing and Quality Assurance, leveraging my skills to contribute to the organization's success and personal growth.</p>
</div>

<div id="b2" class="containerTab">
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

<div id="b3" class="containerTab">
  <h2>Experience</h2>
  <ul>
    <li><b>QA Manager – Bitxia Tech Pvt. Ltd.</b>, Gurugram (Sep 2022 – Present)</li>
    <li><b>Sr. Test Engineer – DLT LABS</b>, Noida (Jun 2021 – Sep 2022)</li>
    <li><b>Associate Team Lead – Xorlabs.com</b>, Greater Noida (Mar 2014 – Jun 2021)</li>
    <li><b>Software Test Engineer – Safenet Infotech Pvt. Ltd.</b> via Magna InfoTech, Noida (Mar 2012 – Mar 2014)</li>
  </ul>
</div>

<div id="b4" class="containerTab">
  <h2>Certifications</h2>
  <ul>
    <li>ISTQB Certified Tester – Foundation Level</li>
  </ul>
</div>

<div id="b5" class="containerTab">
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

<div id="b6" class="containerTab">
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

<div id="b7" class="containerTab">
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
