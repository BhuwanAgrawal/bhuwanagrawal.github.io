<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bhuwan Agrawal – Resume</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f9f9f9;
      color: #333;
    }
    .navbar {
      display: flex;
      justify-content: center;
      background: #222;
      padding: 10px;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    .navbar a {
      color: #fff;
      text-decoration: none;
      margin: 0 12px;
      padding: 6px 10px;
      border-radius: 5px;
      transition: background 0.3s;
    }
    .navbar a:hover,
    .navbar a.activeLink {
      background: #0073e6;
    }
    .containerTab {
      display: none;
      max-width: 900px;
      margin: 40px auto;
      padding: 20px;
      background: #fff;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    .containerTab.activeTab {
      display: block;
    }
    h2 {
      margin-top: 0;
      font-size: 22px;
      color: #0073e6;
      border-bottom: 2px solid #eee;
      padding-bottom: 5px;
    }
    .contribution-list {
      list-style: none;
      padding: 0;
      margin: 0;
    }
    .contribution-list li {
      margin: 10px 0;
    }
    .contribution-list a {
      text-decoration: none;
      color: #333;
      font-weight: 500;
    }
    .contribution-list a:hover {
      color: #0073e6;
    }
  </style>
</head>
<body>

  <!-- 🔹 Navigation -->
  <div class="navbar">
    <a href="#career-objective">Career Objective</a>
    <a href="#profile-summary">Profile Summary</a>
    <a href="#technical-skills">Technical Skills</a>
    <a href="#work-experience">Work Experience</a>
    <a href="#key-projects">Project Experience</a>
    <a href="#github-portfolio">GitHub Portfolio</a>
    <a href="#certifications">Certifications</a>
    <a href="#academic-background">Academic Background</a>
  </div>

  <!-- 🔹 Career Objective -->
  <div id="career-objective" class="containerTab activeTab">
    <h2><i class="fas fa-bullseye"></i> Career Objective</h2>
    <p>To leverage my expertise in QA Automation and Business Analysis to contribute to innovative projects in the Cards and Payments domain.</p>
  </div>

  <!-- 🔹 Profile Summary -->
  <div id="profile-summary" class="containerTab">
    <h2><i class="fas fa-user"></i> Profile Summary</h2>
    <p>Over 10 years of experience in QA Automation, Business Analysis, and API Testing. Skilled in tools like Cypress, Playwright, and Postman.</p>
  </div>

  <!-- 🔹 Technical Skills -->
  <div id="technical-skills" class="containerTab">
    <h2><i class="fas fa-tools"></i> Technical Skills</h2>
    <ul>
      <li>Cypress, Playwright, Selenium</li>
      <li>Postman, REST APIs, Newman</li>
      <li>Jenkins, GitHub Actions, CI/CD</li>
      <li>SQL, JIRA, Confluence</li>
    </ul>
  </div>

  <!-- 🔹 Work Experience -->
  <div id="work-experience" class="containerTab">
    <h2><i class="fas fa-briefcase"></i> Work Experience</h2>
    <p><strong>Confiable Consultancy</strong> – Business Analyst (2023–Present)</p>
    <p>Leading requirements gathering, API testing strategies, and client communications.</p>
  </div>

  <!-- 🔹 Key Projects -->
  <div id="key-projects" class="containerTab">
    <h2><i class="fas fa-tasks"></i> Project Experience</h2>
    <ul>
      <li>Education Management System – PRD & FRS creation</li>
      <li>Time Tracking & Invoicing Application – Requirement Analysis</li>
      <li>Payments API Testing – Postman & Jenkins Integration</li>
    </ul>
  </div>

  <!-- 🔹 GitHub Portfolio -->
  <div id="github-portfolio" class="containerTab">
    <h2><i class="fab fa-github"></i> GitHub Portfolio</h2>
    <ul class="contribution-list">
      <li class="project-name"><a href="https://github.com/bhuwan-agrawal/Cypress-Project" target="_blank">Cypress Automation Project</a></li>
      <li class="project-name"><a href="https://github.com/bhuwan-agrawal/Playwright-Tests" target="_blank">Playwright Automation Tests</a></li>
    </ul>
  </div>

  <!-- 🔹 Certifications -->
  <div id="certifications" class="containerTab">
    <h2><i class="fas fa-award"></i> Certifications</h2>
    <ul class="contribution-list">
      <li class="project-name"><a href="https://www.istqb.in/about-us/certified-tester/foundation-level/36257-bhuwan-agrawal" target="_blank">ISTQB Certified Tester – Foundation Level (CTFL), 2011</a></li>
      <li class="project-name"><a href="https://www.linkedin.com/learning/certificates/c5bb67e1670e6ff45ff785902220bd9570768ed590b833d63fea9745d62e6f4c?trk=share_certificate" target="_blank">API Testing Foundations – LinkedIn Learning, 2025</a></li>
      <li class="project-name"><a href="https://www.linkedin.com/learning/certificates/19c4590084f62e0303e9d21c0caf52f38ec7b99a0b13641bf989ef6ba410143f?trk=share_certificate" target="_blank">Postman Essential Training – LinkedIn Learning, 2025</a></li>
    </ul>
  </div>

  <!-- 🔹 Academic Background -->
  <div id="academic-background" class="containerTab">
    <h2><i class="fas fa-graduation-cap"></i> Academic Background</h2>
    <p>Bachelor of Engineering in Computer Science – 2010</p>
  </div>

  <!-- 🔹 Scripts -->
  <script>
    const tabs = document.querySelectorAll(".containerTab");
    const navLinks = document.querySelectorAll(".navbar a");

    function openTab(tabName) {
      tabs.forEach(tab => tab.classList.remove("activeTab"));
      navLinks.forEach(link => link.classList.remove("activeLink"));

      const activeTab = document.getElementById(tabName);
      const activeLink = document.querySelector(`.navbar a[href="#${tabName}"]`);

      if (activeTab) {
        activeTab.classList.add("activeTab");
        if (activeLink) activeLink.classList.add("activeLink");

        // Update URL hash
        history.pushState(null, "", `#${tabName}`);
        window.scrollTo({ top: 0, behavior: 'smooth' });
      }
    }

    // Nav click event
    navLinks.forEach(link => {
      link.addEventListener("click", e => {
        e.preventDefault();
        const tabName = link.getAttribute("href").substring(1);
        openTab(tabName);
      });
    });

    // Scroll spy effect
    window.addEventListener("scroll", () => {
      let current = "";
      tabs.forEach(section => {
        const sectionTop = section.offsetTop - 100;
        if (pageYOffset >= sectionTop) {
          current = section.getAttribute("id");
        }
      });
      navLinks.forEach(link => {
        link.classList.remove("activeLink");
        if (link.getAttribute("href") === `#${current}`) {
          link.classList.add("activeLink");
          history.replaceState(null, "", `#${current}`);
        }
      });
    });

    // On load, open tab from hash
    window.addEventListener("load", () => {
      const hash = window.location.hash.substring(1);
      if (hash) openTab(hash);
    });
  </script>
</body>
</html>
