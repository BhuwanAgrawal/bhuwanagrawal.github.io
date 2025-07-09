<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<script src='https://kit.fontawesome.com/1053334a8a.js' crossorigin='anonymous'></script>
<link rel="stylesheet" href="style.css">
</head>
<body>

<div class="header">
  <h2><u>CURRICULUM VITAE</u></h2>
  <img src="CTFL.png" alt="Certification" width="200" height="150" align="right">
  <h6><b>Name:</b> Bhuwan Agrawal</h6>
  <h6><i class='fa fa-home'></i> B-105 Stellar Mi Citihomes, Omicron 3, Greater Noida, 201310</h6>
  <h6><i class='fas fa-mobile-alt'></i> 8800149988</h6>
  <h6><i class='fa fa-envelope'></i> <a href="mailto:bhuwan83@gmail.com">bhuwan83@gmail.com</a></h6>
  <h6><i class='fab fa-linkedin'></i> <a href="https://www.linkedin.com/in/bhuwanagrawal">linkedin.com/in/bhuwanagrawal</a></h6>
</div>

<div class="navbar">
  <a onclick="openTab('b1')">Objective</a>
  <a onclick="openTab('b2')">Summary</a>
  <a onclick="openTab('b3')">Experience</a>
  <a onclick="openTab('b6')">Projects</a>
  <a onclick="openTab('b5')">Skills</a>
  <a onclick="openTab('b4')">Certifications</a>
  <a onclick="openTab('b7')">Education</a>
</div>

<div id="b1" class="containerTab">
  <h2>Objective</h2>
  <p>To achieve a challenging position in Software Testing and Quality Assurance, leveraging my skills to contribute to the organization's success and personal growth.</p>
</div>

<div id="b2" class="containerTab" style="display:none;">
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

<div id="b3" class="containerTab" style="display:none;">
  <h2>Experience</h2>
  <ul>
    <li><b>QA Manager – Bitxia Tech Pvt. Ltd.</b>, Gurugram (Sep 2022 – Present)</li>
    <li><b>Sr. Test Engineer – DLT LABS</b>, Noida (Jun 2021 – Sep 2022)</li>
    <li><b>Associate Team Lead – Xorlabs.com</b>, Greater Noida (Mar 2014 – Jun 2021)</li>
    <li><b>Software Test Engineer – Safenet Infotech Pvt. Ltd.</b> via Magna InfoTech, Noida (Mar 2012 – Mar 2014)</li>
  </ul>
</div>

<div id="b4" class="containerTab" style="display:none;">
  <h2>Certifications</h2>
  <ul>
    <li>ISTQB Certified Tester – Foundation Level</li>
  </ul>
</div>

<div id="b5" class="containerTab" style="display:none;">
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

<div id="b6" class="containerTab" style="display:none;">
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

<div id="b7" class="containerTab" style="display:none;">
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
    x[i].style.display = "none";
  }
  document.getElementById(tabName).style.display = "block";
}
</script>

<div class="footer">
  <p><i class='fa fa-download'></i> <a href="Resume_Bhuwan_Agrawal.pdf" download>Download Resume (PDF)</a></p>
</div>

</body>
</html>
