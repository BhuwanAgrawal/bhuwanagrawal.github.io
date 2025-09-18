<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<link rel="icon" type="image/png" href="profile.jpg">
<meta name="viewport" content="width=device-width, initial-scale=1">
<!-- Font Awesome kit (same as yours) -->
<script src='https://kit.fontawesome.com/1053334a8a.js' crossorigin='anonymous'></script>
<title>Bhuwan Agrawal – Resume</title>

<style>
/* ---------------------------
   Your existing styles (kept)
   with a few targeted fixes
   --------------------------- */

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

/* Container sections: show all sections (single-page resume) */
.containerTab {
  display: block; /* show sections so scroll + scroll-spy works */
  padding: 20px;
  opacity: 1;
  transition: opacity 0.5s ease-in-out;
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

/* Common block UI for all sections */
.section-block {
  margin-bottom: 20px;
  padding: 15px 20px;
  background-color: #e8f0f8;
  border-left: 4px solid #1a5276;
  border-radius: 6px;
  transition: transform 0.3s, box-shadow 0.3s;
}
.section-block:hover {
  transform: translateY(-3px);
  box-shadow: 0 4px 15px rgba(0,0,0,0.25);
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
  width: 220px;
  text-align: left;
}

/* Project experience & GitHub contributions */
.project-name, .company-name {
  color: #154360;
  font-weight: bold;
}
.contribution-list {
  list-style: none;
  padding-left: 0;
  margin: 0;
}
.contribution-list li {
  margin: 8px 0;
}
.contribution-list li a {
  text-decoration: none;
  color: #333;
  font-weight: 500;
}
.contribution-list li a:hover { color: #0073e6; }

.contribution-list li span {
  font-weight: normal;
  color: #2c3e50;
}
.responsibilities-title { margin-top: 10px; font-weight: bold; color: #1a5276; }
.responsibilities-list li { list-style-type: square; margin-left: 20px; color: #2c3e50; margin-bottom: 4px; }

/* Generic link style */
a { color: #154360; text-decoration: none; }
a:hover { text-decoration: underline; }

/* Certification logos (if you keep local images ISTQB.png, Linkedin.png, Postman.png) */
.cert-logo {
  width: 22px;
  height: 22px;
  margin-right: 8px;
  object-fit: contain;
  vertical-align: middle;
}

/* Hide auto-inserted anchor/link icons (from AnchorJS or similar) */
.anchorjs-link,
.header-link,
h2 > a.anchor,
h2 > .anchor,
h2 .anchorjs-link,
a[href^="#certifications-"] {
  display: none !important;
}

/* Make section headings consistent */
.containerTab h2 {
  margin-top: 0;
  color: #1a5276;
  font-size: 20px;
  display: flex;
  align-items: center;
  gap: 8px;
}

/* Small visual tweak for the CTFL image in header column */
.header .cert-thumb img { max-width: 140px; height: auto; }

/* Active nav link visual - ensure it stands out on sticky navbar */
.navbar a.activeLink {
  box-shadow: 0 4px 10px rgba(0,0,0,0.25);
}
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
      <h4 style="margin-top: -10px; font-family: 'Georgia', serif; color: #1a5276; text-align: left; font-size: 14px;">
        QA Manager | Automation (Playwright, Cypress) | AI-Assisted Testing | CI/CD</h4>

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
      <div style="text-align: center;" class="cert-thumb">
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
  <!-- NOTE: links are normal href="#id" (JS will handle smooth scroll + hash update) -->
  <a href="#career-objective">Career Objective</a>
  <a href="#profile-summary">Profile Summary</a>
  <a href="#technical-skills">Technical Skills</a>
  <a href="#work-experience">Work Experience</a>
  <a href="#key-projects">Project Experience</a>
  <a href="#github-portfolio">GitHub Portfolio</a>
  <a href="#certifications">Certifications</a>
  <a href="#academic-background">Academic Background</a>
</div>

<!-- Sections -->
<div id="career-objective" class="containerTab section-block">
  <h2><i class="fas fa-bullseye"></i> Career Objective</h2>
  <p>To leverage over 13+ years of experience in software quality assurance, test automation, and AI-driven testing to architect scalable QA frameworks, mentor engineering teams, and deliver high-quality products through innovative, automation-first, and AI-powered testing strategies across UI, API, database, performance, and non-functional domains.</p>
</div>

<div id="profile-summary" class="containerTab section-block">
  <h2><i class="fas fa-user"></i> Profile Summary</h2>
  <p>QA Leader with 13+ years’ experience in automation and quality engineering. Skilled in building scalable QA frameworks across UI, API, DB, and performance testing. Hands-on with Cypress, Playwright, Jenkins and GitHub Actions. Proficient in AI-assisted testing using VS Code with GitHub Copilot and Cursor, driving faster script creation, improved test coverage, and higher efficiency. Strong track record in mentoring teams, defining QA strategy, and ensuring quality-first agile delivery.</p>
</div>

<div id="technical-skills" class="containerTab section-block">
  <h2><i class="fas fa-tools"></i> Technical Skills</h2>
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

<div id="work-experience" class="containerTab section-block">
  <h2><i class="fas fa-briefcase"></i> Work Experience</h2>
  <ul>
    <li><strong>QA Manager</strong> – Bitxia Tech Pvt. Ltd., Gurugram (Sep 2022 – July 2025)</li>
    <li><strong>Sr. Test Engineer</strong> – DLT LABS, Noida (Jun 2021 – Sep 2022)</li>
    <li><strong>Associate Team Lead</strong> – Xorlabs.com, Greater Noida (Mar 2014 – Jun 2021)</li>
    <li><strong>Software Test Engineer</strong> – Safenet Infotech Pvt. Ltd. via Magna InfoTech, Noida (Mar 2012 – Mar 2014)</li>
  </ul>
</div>

<!-- Project Experience (Full restored) -->
<div id="key-projects" class="containerTab section-block">
  <h2><i class="fas fa-project-diagram"></i> Project Experience</h2>

  <!-- Bitxia Tech -->
  <h3 class="company-name">Bitxia Tech Pvt. Ltd.</h3>
  <ul class="contribution-list">
    <li><strong>eNAM 2.0 (Dec 2024 – July 2025):</strong> Digital agri-trading platform enabling farmers, traders, and FPOs to buy/sell produce online.<br><em><strong>Contribution:</strong></em> Designed and executed automation framework using Playwright for UI and API automation, ensuring faster regression cycles and improved test coverage.</li>
    <li><strong>APL Logistics COMS Application (Apr 2023 – Dec 2024):</strong> Comprehensive logistics and supply chain management solution for order, shipment, and warehouse operations.<br><em><strong>Contribution:</strong></em> Implemented Playwright-based automation integrated into CI/CD pipelines, enhancing reliability and reducing manual testing effort.</li>
    <li><strong>Investor Portal (Sep 2022 – Apr 2023):</strong> Web platform for investors to manage profiles, portfolios, and track investments.<br><em><strong>Contribution:</strong></em> Developed Cypress automation scripts for functional and regression testing, reducing manual execution time and ensuring stability across releases.</li>
    <li><strong>Jarvis Retail Lending (Sep 2022 – Apr 2023):</strong> Loan origination and management system enabling digital onboarding, credit assessment, and loan processing.<br><em><strong>Contribution:</strong></em> Built automation suite using Cypress and integrated it into CI/CD pipelines; introduced AI-assisted testing practices to improve test efficiency and reduce defect leakage.</li>
  </ul>
  <div class="responsibilities-title">Responsibilities at Bitxia:</div>
  <ul class="responsibilities-list">
    <li>Led a QA team of 5–6 members, handling client communication, project estimation, and test delivery (manual & automation).</li>
    <li>Hands-on automation experience using Cypress and Playwright for UI and API test automation, improving coverage and reducing regression cycle time.</li>
    <li>Ownership of QA automation architecture and scalability across UI, API, database, performance, and non-functional testing.</li>
    <li>Mentored QA engineers on automation best practices, framework design, scripting, and AI-assisted testing with VS Code, GitHub Copilot, and Cursor.</li>
    <li>Integrated automation frameworks into CI/CD pipelines (Jenkins, GitHub Actions) ensuring faster release cycles and deployment reliability.</li>
    <li>Defined and implemented QA governance models, test strategy, and quality standards.</li>
    <li>Collaborated closely with developers, product managers, and DevOps to embed a quality-first approach in agile delivery.</li>
  </ul>

  <!-- DLT Labs -->
  <h3 class="company-name">DLT LABS</h3>
  <ul class="contribution-list">
    <li><strong>PPD (DL Asset Track) (Mar 2022 – Sep 2022)</strong> – Manual testing of blockchain apps, TestLink, Jira.</li>
    <li><strong>THOR (DL Asset Track) (Jun 2021 – Feb 2022)</strong> – Manual & functional testing using TestLink, Jira.</li>
  </ul>

  <!-- Xorlabs -->
  <h3 class="company-name">Xorlabs.com</h3>
  <ul class="contribution-list">
    <li><strong>Projects:</strong> SQLCM, XMF Automation, CML Configurator, SQL Secure, Uptime, ASD, One Source Configurator, MSQT</li>
    <li><em><strong>Responsibilities:</strong></em> Manual & automation testing (Ranorex, Selenium, TestComplete), Jira.</li>
  </ul>

  <!-- Safenet Infotech -->
  <h3 class="company-name">Safenet Infotech Pvt. Ltd.</h3>
  <ul class="contribution-list">
    <li><strong>Projects:</strong> Usage Reporting System, WPS Online, WPS Client</li>
    <li><em><strong>Responsibilities:</strong></em> Manual & QTP automation (VBScript), functional, GUI, DB testing, MKS.</li>
  </ul>
</div>

<!-- GitHub Portfolio -->
<div id="github-portfolio" class="containerTab section-block">
  <h2><i class="fab fa-github"></i> GitHub Portfolio – Test Automation Projects</h2>
  <ul class="contribution-list">
    <li class="project-name"><a href="https://github.com/BhuwanAgrawal/Playwright-Project" target="_blank">Playwright Project</a><span> – End-to-end automation framework demonstrating UI testing using Playwright.</span></li>
    <li class="project-name"><a href="https://github.com/BhuwanAgrawal/Cypress-Project" target="_blank">Cypress Project</a><span> – Test automation suite for functional and regression testing of web applications.</span></li>
    <li class="project-name"><a href="https://github.com/BhuwanAgrawal/Selenium-KD-Project" target="_blank">Selenium Keyword Driven Project</a><span> – Keyword-driven automation framework for regression and functional testing.</span></li>
  </ul>
</div>

<!-- Certifications (formatted like GitHub Portfolio) -->
<div id="certifications" class="containerTab section-block">
  <h2><i class="fas fa-award"></i> Certifications</h2>
  <ul class="contribution-list">
    <li class="project-name">
      <a href="https://www.istqb.in/about-us/certified-tester/foundation-level/36257-bhuwan-agrawal" target="_blank">
        <!-- optional: keep ISTQB.png locally if you have it -->
        <img src="ISTQB.png" alt="ISTQB Logo" class="cert-logo" onerror="this.style.display='none'">
        ISTQB Certified Tester – Foundation Level (CTFL), 2011
      </a>
    </li>
    <li class="project-name">
      <a href="https://www.linkedin.com/learning/certificates/c5bb67e1670e6ff45ff785902220bd9570768ed590b833d63fea9745d62e6f4c?trk=share_certificate" target="_blank">
        <img src="Linkedin.png" alt="LinkedIn Logo" class="cert-logo" onerror="this.style.display='none'">
        API Testing Foundations – LinkedIn Learning, 2025
      </a>
    </li>
    <li class="project-name">
      <a href="https://www.linkedin.com/learning/certificates/19c4590084f62e0303e9d21c0caf52f38ec7b99a0b13641bf989ef6ba410143f?trk=share_certificate" target="_blank">
        <img src="Postman.png" alt="Postman Logo" class="cert-logo" onerror="this.style.display='none'">
        Postman Essential Training – LinkedIn Learning, 2025
      </a>
    </li>
  </ul>
</div>

<div id="academic-background" class="containerTab section-block">
  <h2><i class="fas fa-graduation-cap"></i> Academic Background</h2>
  <ul>
    <li>MCA – UP Technical University – 64.28%</li>
    <li>BCA – Allahabad Agriculture Institute – 7.96 CGPA</li>
  </ul>
</div>

<script>
/* Smooth navigation + hash update + scroll-spy
   - Converts navbar clicks into smooth-scrolling to sections
   - Updates the URL hash with pushState for clicks and replaceState during scrolling
   - Hides/removes auto-inserted anchors if any exist
*/

document.addEventListener('DOMContentLoaded', function() {
  const navLinks = document.querySelectorAll('.navbar a');
  const sections = Array.from(document.querySelectorAll('.containerTab'));
  const offset = 120; // adjust if your navbar height changes

  function setActiveLink(id) {
    navLinks.forEach(link => {
      link.classList.toggle('activeLink', link.getAttribute('href') === `#${id}`);
    });
  }

  // handle click on navbar links
  navLinks.forEach(link => {
    link.addEventListener('click', function(e) {
      e.preventDefault();
      const id = this.getAttribute('href').substring(1);
      const el = document.getElementById(id);
      if (!el) return;
      // smooth scroll
      el.scrollIntoView({ behavior: 'smooth', block: 'start' });
      // update history (so URL shows endpoint)
      history.pushState(null, '', `#${id}`);
      setActiveLink(id);
      // update document title based on section header
      const h2 = el.querySelector('h2');
      if (h2) document.title = `Bhuwan Agrawal – ${h2.textContent.trim()}`;
    });
  });

  // scroll spy: highlight nav and update hash while scrolling
  window.addEventListener('scroll', function() {
    let current = sections[0]?.id || '';
    for (const section of sections) {
      const rect = section.getBoundingClientRect();
      if (rect.top <= offset) {
        current = section.id;
      }
    }
    if (current) {
      setActiveLink(current);
      // replaceState to avoid cluttering history while scrolling
      history.replaceState(null, '', `#${current}`);
    }
  });

  // on initial load, if there's a hash, scroll to it
  const initialHash = window.location.hash.substring(1);
  if (initialHash) {
    const el = document.getElementById(initialHash);
    if (el) {
      // slight timeout to allow rendering
      setTimeout(() => { el.scrollIntoView(); setActiveLink(initialHash); }, 50);
    }
  } else {
    // default active link
    setActiveLink('profile-summary');
  }

  // remove any auto-inserted anchor links near headings (AnchorJS, etc.)
  // This removes elements like <a class="anchorjs-link"> or similar inserted into h2
  document.querySelectorAll('h2').forEach(h2 => {
    h2.querySelectorAll('a').forEach(a => {
      // if it's an auto anchor (href starts with '#' and has no visible text) remove it
      const href = a.getAttribute('href') || '';
      const txt = a.textContent || '';
      if ((href.startsWith('#') && txt.trim() === '') || a.classList.contains('anchorjs-link') || a.classList.contains('header-link')) {
        a.remove();
      }
    });
  });
});
</script>

</body>
</html>
