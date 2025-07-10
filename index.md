<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Bhuwan Agrawal – Resume</title>
  <link rel="icon" type="image/png" href="favicon.png" sizes="32x32">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <script src="https://kit.fontawesome.com/1053334a8a.js" crossorigin="anonymous"></script>
  <style>
    body { margin: 0; font-family: Arial, sans-serif; }

    .navbar {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 8px;
      padding: 10px;
      background-color: #1a5276;
      border-top: 2px solid #f1c40f;
      border-bottom: 2px solid #f1c40f;
    }

    .navbar a {
      font-size: 13px;
      padding: 10px 20px;
      color: white;
      background-color: #1a5276;
      text-decoration: none;
      transition: background-color 0.3s, box-shadow 0.3s;
      border-radius: 20px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.2);
      border: 2px solid transparent;
    }

    .navbar a:hover {
      background-color: #154360;
      border-color: #f1c40f;
    }

    .navbar a.activeLink {
      background-color: #154360;
      border-color: #f1c40f;
      font-weight: bold;
      text-decoration: underline;
    }

    .containerTab {
      display: none;
      padding: 20px;
      background: LightSteelBlue;
      color: black;
      opacity: 0;
      transition: opacity 0.4s ease;
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
        font-size: 14px;
        padding: 16px 24px;
        border-radius: 0;
        border-bottom: 3px solid transparent;
      }
      .navbar a:hover {
        background-color: #154360;
        border-bottom: 3px solid #f1c40f;
      }
      .navbar a.activeLink {
        border-bottom: 3px solid #f1c40f;
      }
    }
  </style>
</head>
<body>

<div style="background-color: LightCyan; padding: 20px;">
  <h1 style="font-size: 36px; color: #1a5276; letter-spacing: 2px; text-transform: uppercase; text-align: center; margin-bottom: 20px;"><u>Curriculum Vitae</u></h1>
  <div class="header" style="display: flex; justify-content: space-between; align-items: flex-start; flex-wrap: wrap;">
    <div style="flex: 1 1 60%; min-width: 300px; background-color: #f5f9fc; padding: 15px; border-radius: 10px; border: 1px solid #cfdce6;">
      <h2 style="margin-top: 0; font-size: 28px; font-family: 'Georgia', serif; color: #1a5276;">Bhuwan Agrawal</h2>
      <h4 style="margin-top: -10px; font-family: 'Georgia', serif; color: #1a5276;">QA Manager</h4>
      <p><i class='fas fa-map-marker-alt'></i> B-105 Stellar Mi Citihomes,<br>Omicron 3, Greater Noida, 201310</p>
      <p><i class='fas fa-mobile-alt'></i> 8800149988 | <i class='fa fa-envelope'></i> <a href="mailto:bhuwan83@gmail.com">bhuwan83@gmail.com</a></p>
      <p><i class='fab fa-linkedin'></i> <a href="https://www.linkedin.com/in/bhuwanagrawal" target="_blank" rel="noopener noreferrer">linkedin.com/in/bhuwanagrawal</a></p>
      <p><a href="Resume_Bhuwan_Agrawal.pdf" download style="color: inherit; text-decoration: none;"><i class='fas fa-file-download'></i> Download Resume (PDF)</a></p>
    </div>
    <div style="flex: 0 1 35%; min-width: 180px; display: flex; flex-direction: column; align-items: center;">
      <div style="margin-bottom: 15px;">
        <img src="profile.jpg" alt="Profile Photo" style="width: 110px; height: 110px; border-radius: 8px; object-fit: cover; object-position: top center; box-shadow: 0 0 8px rgba(0,0,0,0.2); border: 2px solid #1a5276;">
      </div>
      <div style="text-align: center;">
        <a href="https://www.istqb.in/about-us/certified-tester/foundation-level/36257-bhuwan-agrawal" target="_blank" rel="noopener noreferrer">
          <img src="CTFL.png" alt="Certification" style="width: 140px; height: auto; border: 2px solid #1a5276; border-radius: 8px;">
        </a>
        <a href="https://www.istqb.in/about-us/certified-tester/foundation-level/36257-bhuwan-agrawal" target="_blank" style="text-decoration: none; color: #1a5276;">
          <div style="margin-top: 5px; font-size: 14px; display: flex; align-items: center; gap: 5px; justify-content: center;">
            <i class="fas fa-certificate"></i>
            ISTQB Certified
          </div>
        </a>
      </div>
    </div>
  </div>
</div>

<div class="navbar" role="navigation" aria-label="Resume navigation">
  <a href="#career-objective" onclick="openTab('career-objective'); return false;">Career Objective</a>
  <a href="#profile-summary" onclick="openTab('profile-summary'); return false;">Profile Summary</a>
  <a href="#work-experience" onclick="openTab('work-experience'); return false;">Work Experience</a>
  <a href="#key-projects" onclick="openTab('key-projects'); return false;">Key Projects</a>
  <a href="#technical-skills" onclick="openTab('technical-skills'); return false;">Technical Skills</a>
  <a href="#certifications" onclick="openTab('certifications'); return false;">Certifications</a>
  <a href="#academic-background" onclick="openTab('academic-background'); return false;">Academic Background</a>
</div>

<!-- Resume Sections (unchanged from your version, not duplicated here for brevity) -->
<!-- Paste your full section content here: career-objective, profile-summary, etc. -->

<!-- Example section: -->
<div id="career-objective" class="containerTab">
  <h2>Career Objective</h2>
  <p>To achieve a challenging position in Software Testing and Quality Assurance, leveraging my skills to contribute to the organization's success and personal growth.</p>
</div>

<!-- ... include your other sections as they are ... -->

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
    setTimeout(() => activeTab.classList.add("activeTab"), 10);
    if (activeLink) activeLink.classList.add("activeLink");

    // Scroll to top
    window.scrollTo({ top: 0, behavior: 'smooth' });

    // Update title
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

// Load tab based on URL hash
window.onload = function () {
  const hash = window.location.hash.substring(1);
  const defaultTab = document.getElementById(hash) ? hash : "profile-summary";
  openTab(defaultTab);
};
</script>

</body>
</html>
