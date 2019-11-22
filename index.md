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
  background-color: white;
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
<div style="text-align:center">
  <!--h1>Resume</h1-->
   <img src="Bhuwan.jpg" alt="Cinque Terre" width="100" height="100" align="right" padding="0px">
  <h6> <b>Name: </b>Bhuwan Agrawal</h6>
  <h6><i class='fa fa-home'></i>: B-105 Stellar Mi Citihomes,</h6>
  <h6>Omicron 3, Greater Noida, 201310</h6>
  <h6><i class='fas fa-mobile-alt'></i>: 8800149988</h6>
  <h6><i class='fa fa-envelope'></i>: <A HREF="mailto:name@mydomain.com">bhuwan83@gmail.com</A></h6>
  <h6><i class='fab fa-linkedin'></i>: <a href="https://www.linkedin.com/in/bhuwanagrawal">BhuwanAgrawal</a></h6>
</div>
<div style="text-align:center">
  <p>For detail information click on the boxes below:</p>
</div>
</div>



<!-- Three columns -->
<div class="row">
  <div class="column" onclick="openTab('b1');" style="background:#F5F5DC;">
    About Me
  </div>
  <div class="column" onclick="openTab('b2');" style="background:#F5F5DC;">
    Experience
  </div>
  <div class="column" onclick="openTab('b3');" style="background:#F5F5DC;">
    Projects
  </div>
  <div class="column" onclick="openTab('b4');" style="background:#F5F5DC;">
    Education
  </div>
   <div class="column" onclick="openTab('b5');" style="background:#F5F5DC;">
    Personal Information
  </div>
</div>

<!-- Full-width columns: (hidden by default) -->

<div id="b1" class="containerTab" style="display:none;background:green">
  <!--span onclick="this.parentElement.style.display='none'" class="closebtn">&times;</span-->
  <h2>About Me</h2>
<div class="row">
  <div class="side">
    <h2>About Me</h2>
    <h5>Photo of me:</h5>
    <div class="fakeimg" style="height:200px;">Image</div>
    <p>Some text about me in culpa qui officia deserunt mollit anim..</p>
    <h3>More Text</h3>
    <p>Lorem ipsum dolor sit ame.</p>
    <div class="fakeimg" style="height:60px;">Image</div><br>
    <div class="fakeimg" style="height:60px;">Image</div><br>
    <div class="fakeimg" style="height:60px;">Image</div>
  </div>
 </div>
</div>



<div id="b2" class="containerTab" style="display:none;background:green">
  <span onclick="this.parentElement.style.display='none'" class="closebtn">&times;</span>
  <h2>Experience</h2>
<div class="row">
  <div class="side">
    <h2>About Me</h2>
    <h5>Photo of me:</h5>
    <div class="fakeimg" style="height:200px;">Image</div>
    <p>Some text about me in culpa qui officia deserunt mollit anim..</p>
    <h3>More Text</h3>
    <p>Lorem ipsum dolor sit ame.</p>
    <div class="fakeimg" style="height:60px;">Image</div><br>
    <div class="fakeimg" style="height:60px;">Image</div><br>
    <div class="fakeimg" style="height:60px;">Image</div>
  </div>
 </div>
</div>

<div id="b3" class="containerTab" style="display:none;background:blue">
  <span onclick="this.parentElement.style.display='none'" class="closebtn">&times;</span>
  <h2>Projects</h2>
  <div class="main">
    <h2>TITLE HEADING</h2>
    <h5>Title description, Dec 7, 2017</h5>
    <div class="fakeimg" style="height:200px;">Image</div>
    <p>Some text..</p>
    <p>Sunt in culpa qui officia deserunt mollit anim id est laborum consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco.</p>
    <br>
    <h2>TITLE HEADING</h2>
    <h5>Title description, Sep 2, 2017</h5>
    <div class="fakeimg" style="height:200px;">Image</div>
    <p>Some text..</p>
    <p>Sunt in culpa qui officia deserunt mollit anim id est laborum consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco.</p>
  </div>
</div>

<div id="b4" class="containerTab" style="display:none;background:red">
  <span onclick="this.parentElement.style.display='none'" class="closebtn">&times;</span>
  <h2>Education</h2>
  <p>Lorem ipsum dolor sit amet, te quo doctus abhorreant, et pri deleniti intellegat, te sanctus inermis ullamcorper nam. Ius error diceret deseruisse ad</p>
</div>


<div id="b5" class="containerTab" style="display:none;background:yellow">
  <span onclick="this.parentElement.style.display='none'" class="closebtn">&times;</span>
  <h2>Personal Information</h2>
  <p>Lorem ipsum dolor sit amet, te quo doctus abhorreant, et pri deleniti intellegat, te sanctus inermis ullamcorper nam. Ius error diceret deseruisse ad</p>
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
 <p><a href="examplefile.pdf" download class="right">Download Resume</a></p>
</div>
</div>

</body>




</html>