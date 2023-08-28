<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<script src='https://kit.fontawesome.com/a076d05399.js'></script>



<!-- First style-->
<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
}

/* The grid: Three equal columns that floats next to each other */
.column {
  float: left;
  width: 20%;
  padding: 10px;
  text-align: center;
  font-size: 15px;
  cursor: pointer;
  color: black;
}

.containerTab {
  padding: 20px;
  color: white;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Closable button inside the container tab */
.closebtn {
  float: right;
  color: white;
  font-size: 35px;
  cursor: pointer;
}
</style>


<!-- Second style-->
  <style>
* {
  box-sizing: border-box;
}

/* Style the body */
body {
  font-family: Arial, Helvetica, sans-serif;
  margin: 0;
}

/* Header/logo Title */
.header {
  padding: 5px;
  text-align: center;
  background: LightCyan;
  color: black;
}

/* Increase the font size of the heading */
.header h1 {
  font-size: 40px;
  font-weight: bold;
  font-family: "Times New Roman", Times, serif;
}
/* Increase the font size of the heading */
.header h6 {
  font-size: 14px;
  font-weight: normal;
  font-family: "Times New Roman", Times, serif;
  text-align: left;
  line-height: 20%;
}

/* Sticky navbar - toggles between relative and fixed, depending on the scroll position. It is positioned relative until a given offset position is met in the viewport - then it "sticks" in place (like position:fixed). The sticky value is not supported in IE or Edge 15 and earlier versions. However, for these versions the navbar will inherit default position */
.navbar {
  overflow: hidden;
  background-color: #333;
  position: sticky;
  position: -webkit-sticky;
  top: 0;
}

/* Style the navigation bar links */
.navbar a {
  float: left;
  display: block;
  color: white;
  text-align: center;
  padding: 14px 20px;
  text-decoration: none;
}

/* Right-aligned link */
.navbar a.right {
  float: right;
}

/* Change color on hover */
.navbar a:hover {
  background-color: #ddd;
  color: black;
}

/* Active/current link */
.navbar a.active {
  background-color: #666;
  color: white;
}

/* Column container */
.row {  
  display: -ms-flexbox; /* IE10 */
  display: flex;
  -ms-flex-wrap: wrap; /* IE10 */
  flex-wrap: wrap;
}

/* Create two unequal columns that sits next to each other */
/* Sidebar/left column */
.side {
  -ms-flex: 30%; /* IE10 */
  flex: 30%;
  background-color: #f1f1f1;
  padding: 20px;
}

/* Main column */
.main {   
  -ms-flex: 70%; /* IE10 */
  flex: 70%;
  background-color: LightSteelBlue;
  padding: 20px;
}

/* Fake image, just for this example */
.fakeimg {
  background-color: #aaa;
  width: 100%;
  padding: 20px;
}

/* Footer */
.footer {
  padding: 20px;
  text-align: center;
  background: LightCyan;
}

/* Responsive layout - when the screen is less than 700px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 700px) {
  .row {   
    flex-direction: column;
  }
}

/* Responsive layout - when the screen is less than 400px wide, make the navigation links stack on top of each other instead of next to each other */
@media screen and (max-width: 400px) {
  .navbar a {
    float: none;
    width: 100%;
  }
}

</style>

</head>

<body>


<div class="header">
<div style="text-align:center; line-height: 1.0">
  <h2><u>CURRICULUM VITAE</u></h2>
  <img src="CTFL.png" alt="Cinque Terre" width="200" height="150" align="right" padding="10px">
  <h6 style="color:black"> <b>Name: </b>Bhuwan Agrawal</h6>
  <h6 style="color:black"><i class='fa fa-home'></i> <b>:</b> B-105 Stellar Mi Citihomes,</h6>
  <h6 style="color:black">Omicron 3, Greater Noida, 201310</h6>
  <h6 style="color:black"><i class='fas fa-mobile-alt'></i> <b>:</b> 8800149988</h6>
  <h6 style="color:black"><i class='fa fa-envelope'></i> <b>:</b> <A HREF="mailto:name@mydomain.com">bhuwan83@gmail.com</A></h6>
  <h6 style="color:black"><i class='fab fa-linkedin'></i> <b>:</b> <a href="https://www.linkedin.com/in/bhuwanagrawal">BhuwanAgrawal</a></h6>
</div>
<!--div style="text-align:center">
  <p>For detail information click on the boxes below:</p>
</div-->
</div>



<!-- Seven columns -->
<div class="row">
  <div class="column" onclick="openTab('b1');" style="background:#F5F5DC;column-rule-style:double">
    <b>Objective</b>
  </div>
  <div class="column" onclick="openTab('b2');" style="background:#F5F5DC;column-rule-style:double">
    <b>Summary</b>
  </div>
  <div class="column" onclick="openTab('b3');" style="background:#F5F5DC;column-rule-style:double">
    <b>Experience</b>
  </div>
   <div class="column" onclick="openTab('b4');" style="background:#F5F5DC;column-rule-style:double">
    <b>Certifications</b>
  </div>
  <div class="column" onclick="openTab('b5');" style="background:#F5F5DC;column-rule-style:double">
    <b>Software Skills</b>
  </div>
  <div class="column" onclick="openTab('b6');" style="background:#F5F5DC;column-rule-style:double">
    <b>Projects</b>
  </div>
   <div class="column" onclick="openTab('b7');" style="background:#F5F5DC;column-rule-style:double">
    <b>Qualification</b>
  </div>
</div>

<!-- Full-width columns: (hidden by default) -->

<div id="b1" class="containerTab" style="background:LightSteelBlue;color:black">
  <!--span onclick="this.parentElement.style.display='none'" class="closebtn">&times;</span-->
  <h2>Objective</h2>
  <div class="main">
    <p><h5>My objective is to achieve a challenging position in Software testing and Quality Management in a company, where acquired skills will be utilized towards continued growth and advancement of the organization.</h5></p>
  </div>
</div>



<div id="b2" class="containerTab" style="display:none;background:LightSteelBlue;color:black">
  <!--span onclick="this.parentElement.style.display='none'" class="closebtn">&times;</span-->
  <h2>Summary</h2>
  <div class="main">  
    <h2>A total 11.7 years of Quality Assurance experience in Software industry</h2>
    <p><h5>•	Extensive knowledge in performing Automation testing using Selenium, Ranorex and TestComplete.</h5></p>
	<p><h5>•	Proficient in VBScript.</h5></p>
	<p><h5>•	Knowledge of SDLC and STLC.</h5></p>
	<p><h5>•	Good knowledge and experience of providing quality control in web based as well as Client-server-based applications.</h5></p>
	<p><h5>•	Extensive experience in following QA Methodologies: writing Test Cases, executing and reporting.</h5></p>
	<p><h5>•	Performed Defect Reporting and Tracking throughout the defect life cycle.</h5></p>
	<p><h5>•	Experience in Black Box Testing, Database Testing and Functional Testing, Automation Testing.</h5></p>
	<p><h5>•	Testing on different Operating System Windows XP/7/10,Server 2K8</h5></p>
	<p><h5>•	Skilled on: </h5></p>
	<p><h5>&emsp;&emsp;•	Automation Testing Tool: Selenium, Ranorex and TestComplete</h5></p>
	<p><h5>&emsp;&emsp;•	Version Management Tool: SVN, Github</h5></p>
	<p><h5>&emsp;&emsp;•	Bug Reporting Tools: QC, JIRA</h5></p>
	<p><h5>&emsp;&emsp;•	Test case management tools: TestRail, TestLink</h5></p>
	<p><h5>•	Responsible for Project Planning and Estimations</h5></p>
	<p><h5>•	Team Management (Team size of 7)</h5></p>
	<p><h5>•	Efficient tasks delegation</h5></p>
	<p><h5>•	Daily Scrum / Status tracking of tasks</h5></p>
	<p><h5>•	Project/Defect status Reporting</h5></p>
	<p><h5>•	Self-starter and highly motivated with team building spirit and ability to mentor and learn from team members.</h5></p>
  </div>
</div>

<div id="b3" class="containerTab" style="display:none;background:LightSteelBlue;color:black">
  <!--span onclick="this.parentElement.style.display='none'" class="closebtn">&times;</span-->
  <h2>Experience</h2>
  <div class="main">
    <p><h5>• Working as a QA Manager in Bitxia Technology, Gurugram from Sep-2022 to Present</h5></p>
    <p><h5>• Worked as a Sr. Test Engineer in DLT LABS, Noida from June-2021 to Sep-2022</h5></p>
    <p><h5>• Worked as an Associate Team Lead in Xorlabs.com, Greater Noida from March-2014 to June-2021.</h5></p>
    <p><h5>• Worked as a Software Test Engineer in Safenet Infotech Pvt. Ltd., Noida through Magna InfoTech Pvt. Ltd., Hyderabad from March-2012 to March-2014</h5></p>
  </div>
</div>

<div id="b4" class="containerTab" style="display:none;background:LightSteelBlue;color:black">
  <!--span onclick="this.parentElement.style.display='none'" class="closebtn">&times;</span-->
  <h2>Certifications</h2>
  <div class="main">
    <p><h5>• Certified Tester Foundation Level in Software Testing</h5></p>
  </div>
</div>


<div id="b5" class="containerTab" style="display:none;background:LightSteelBlue;color:black">
  <!--span onclick="this.parentElement.style.display='none'" class="closebtn">&times;</span-->
  <h2>Software Skills</h2>
  <div class="main">
    <p><h5>• Automation Testing Tool:&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Selenium, Ranorex and TestComplete</h5></p>
    <p><h5>• Version Management Tool:&emsp;&emsp;&emsp;&emsp;&emsp;SVN, Github</h5></p>
	<p><h5>• Bug Reporting Tools:&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;QC, JIRA</h5></p>
    <p><h5>• Operating System:&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;Windows XP/7/10, Server 2K8</h5></p>
	<p><h5>• Applications:&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;&ensp;MS-Office: Excel, Word, Power Point</h5></p>
    <p><h5>• Database:&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;SQL Server</h5></p>
	<p><h5>• Test Case Management Tools:&emsp;&emsp;&emsp;&emsp;&ensp;TestRail, TestLink</h5></p>
  </div>
</div>



<div id="b6" class="containerTab" style="display:none;background:LightSteelBlue;color:black">
  <!--span onclick="this.parentElement.style.display='none'" class="closebtn">&times;</span-->
  <h2>Projects</h2>
  <div class="main">

  	<h2>•	Investor Portal Bitxia Technology, Gurugram (Sep-2022 – Till Date)</h2>
    <p><h4><b>Role: (Project Management, Manual Testing)</b></h4></p>
    <p>• Involved in Functional Testing, Retesting, Regression Testing and GUI Testing of the application.</p>
	<p>• Created Test cases in Test case management tool (TestLink) for the functionalities and executed the same.</p>
	<p>• Bug Reporting/ Maintenance done using Jira.</p>
  
	<br>
  	<h2>•	Jarvis Retail Lending Bitxia Technology, Gurugram (Sep-2022 – Apr-2023)</h2>
    <p><h5>Role: (Project Management, Manual Testing)</h5></p>
    <p>• Involved in Functional Testing, Retesting, Regression Testing and GUI Testing of the application.</p>
	<p>• Created Test cases in Test case management tool (TestLink) for the functionalities and executed the same.</p>
	<p>• Bug Reporting/ Maintenance done using Jira.</p>
  
	<br>
	<h2>•	PPD (DL Asset Track) DLT LABS, Noida (Mar-2022 – Sep-2022)</h2>
    <p><h5>Role: (Manual Testing)</h5></p>
    <p>• Involved in Functional Testing, Retesting, Regression Testing and GUI Testing of the application.</p>
	<p>• Created Test cases in Test case management tool (TestLink) for the functionalities and executed the same.</p>
	<p>• Bug Reporting/ Maintenance done using Jira.</p>
  
	<br>
    <h2>•	THOR (DL Asset Track) DLT LABS, Noida (June-2021 – Feb-2022)</h2>
    <p><h5>Role: (Manual Testing)</h5></p>
    <p>• Involved in Functional Testing, Retesting, Regression Testing and GUI Testing of the application.</p>
	<p>• Created Test cases in Test case management tool (TestLink) for the functionalities and executed the same.</p>
	<p>• Bug Reporting/ Maintenance done using Jira.</p>
	
	<br>
  	<h2>• SQLCM Xorlabs.com, Greater Noida (Jan-2020 – June-2021)</h2>
    <p><h5>Role: (Manual/Automation Testing)</h5></p>
    <p>• Involved in Manual Testing of the application.</p>
	<p>• Involved in Automation Testing of the application using Ranorex.</p>
	<p>• Created Automated Test scripts for the functionalities and executed the same through Ranorex.</p>
	<p>• Maintenance of TestComplete test scripts.</p>
	
    <br>
    <p><h2>• XMF Automation Xorlabs.com, Greater Noida (Jan-2019 – Dec-2020)</h2></p>
    <p><h5>Role: (Automation Testing)</h5></p>
    <p>• Developed a Hybrid framework using Selenium Web driver and Java.</p>
	<p>• Writing test scripts using keywords.</p>
	
	<br>
    <p><h2>• SQLCM Xorlabs.com, Greater Noida (Sep-2016 – Dec-2019)</h2></p>
    <p><h5>Role: (Manual/Automation Testing)</h5></p>
    <p>• Involved in Manual Testing of the application.</p>
	<p>• Involved in Automation Testing of the application using Ranorex.</p>
	<p>• Created Automated Test scripts for the functionalities and executed the same through Ranorex.</p>
	<p>• Maintenance of TestComplete test scripts.</p>

	<br>
    <p><h2>• CML Configurator Model Testing Xorlabs.com, Greater Noida (May-2015 – May-2019)</h2></p>
    <p><h5>Role: (Manual Testing)</h5></p>
    <p>• Involved in Functional Testing, Retesting, Regression Testing and GUI Testing of the application.</p>
	<p>• Created Test cases for the functionalities and executed the same.</p>
	<p>• Bug Reporting/ Maintenance done using Jira.</p>

	<br>
    <p><h2>• SQL Secure Xorlabs.com, Greater Noida (Aug-2017 – Oct-2017)</h2></p>
    <p><h5>Role: (Automation Testing)</h5></p>
    <p>• Involved in Automation Testing of the application.</p>
	<p>• Created Automated Test scripts for the functionalities and executed the same through TestComplete</p>

	<br>
    <p><h2>• Uptime Xorlabs.com, Greater Noida (Jan-2017– July-2017)</h2></p>
    <p><h5>Role: (Manual Testing)</h5></p>
    <p>• Involved in Functional Testing, Retesting, Regression Testing and GUI Testing of the application.</p>
    <p>• Created Test cases for the functionalities and executed the same.</p>
	<p>• Bug Reporting/ Maintenance done using Jira.</p>

	<br>
    <p><h2>• ASD	Xorlabs.com, Greater Noida (Mar-2014 – Dec-2016)</h2></p>
    <p><h5>Role: (Manual Testing)</h5></p>
    <p>• Involved in Functional Testing, Retesting, Regression Testing and GUI Testing of the application.</p>
	<p>• Created Test cases for the functionalities and executed the same.</p>
	<p>• Bug Reporting/ Maintenance done using Jira.</p>
	
	<br>
    <p><h2>• One Source Configurator (OSC) Xorlabs.com, Greater Noida (Mar-2014 – Dec-2016)</h2></p>
    <p><h5>Role: (Manual Testing/Automation Testing)</h5></p>
    <p>• Involved in Functional Testing, Retesting, Regression Testing and GUI Testing of the application.</p>
	<p>• Created Test cases for the functionalities and executed the same.</p>
	<p>• Bug Reporting/ Maintenance done using Jira.</p>
	<p>• Involved in Automation Testing of the application.</p>
	<p>• Created Automated Test scripts for the functionalities and executed the same through Selenium.</p>

	<br>
    <p><h2>• MSQT	Xorlabs.com., Greater Noida (Mar-2014 – Dec-2015)</h2></p>
    <p><h5>Role: (Manual Testing)</h5></p>
    <p>• Involved in Functional Testing, Retesting, Regression Testing and GUI Testing of the application.</p>
	<p>• Created Test cases for the functionalities and executed the same.</p>
	<p>• Bug Reporting/ Maintenance done using Jira.</p>
	<p>Some text..</p>

	<br>
    <p><h2>• Usage Reporting System	Safenet Infotech Pvt. Ltd., Noida (Dec-2012– Mar-2014)</h2></p>
    <p><h5>Role: (Manual Testing)</h5></p>
    <p>• Involved in Functional Testing, Database Testing, Retesting, Regression Testing and GUI Testing of the application.</p>
    <p>• Created Test cases for the functionalities and executed the same.</p>
    <p>• Bug Reporting/ Maintenance done using MKS/Jira.</p>

	<br>
    <p><h2>• WPS Online	Safenet Infotech Pvt. Ltd., Noida (Mar-2012 – Dec-2012)</h2></p>
    <p><h5>Role: (Manual Testing/Automation Testing)</h5></p>
    <p>• Involved in Functional Testing, Retesting, Regression Testing and GUI Testing of the application.</p>
	<p>• Created Test cases for the functionalities and executed the same.</p>
	<p>• Involved in writing/maintenance of QTP scripts (with VB script) for functional of the application.</p>
	<p>• Bug Reporting/ Maintenance done using MKS.</p>
	<br>
    <p><h2>• WPS Client	Safenet Infotech Pvt. Ltd., Noida (Mar-2012 – Dec-2012)</h2></p>
    <p><h5>Role: (Manual Testing/Automation Testing)</h5></p>
    <p>• Involved in Functional Testing, Retesting, Regression Testing and GUI Testing of the application.</p>
    <p>• Created Test cases for the functionalities and executed the same.</p>
    <p>• Involved in writing/maintenance of QTP scripts (with VB script) for functional of the application.</p>
    <p>• Bug Reporting/ Maintenance done using MKS.</p>	
  </div>
</div>


<div id="b7" class="containerTab" style="display:none;background:LightSteelBlue;color:black">
  <!--span onclick="this.parentElement.style.display='none'" class="closebtn">&times;</span-->
  <h2>Qualification</h2>
  <div class="main">
    <p><h5>• Done Master of Computer Application from UP Technical University with 64.28%</h5></p>
    <p><h5>• Done Bachelor of Computer Application from Allahabad Agriculture Institute Deemed Universitywith 7.96 CGPA</h5></p>
  </div>
</div>

<script>
function openTab(tabName) {
  var i, x;
  x = document.getElementsByClassName("containerTab");
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";
  }
  document.getElementById(tabName).style.display = "block";
}
</script>


<div class="footer">
 <div style="text-align:right">
 <p><i class='fa fa-download'></i>&ensp; : <a href="Resume_Bhuwan_Agrawal.pdf" download class="right">Download Resume</a></p>
</div>
</div>

</body>
</html>