
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="Create a professional CV online for free with Smart CV Maker.">
<title>Smart CV Maker - Free Resume Builder</title>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  background: #f1f5f9;
  color: #172033;
}

header {
  background: #102b56;
  color: white;
  padding: 20px;
  text-align: center;
}

header h1 {
  font-size: 25px;
}

header p {
  margin-top: 7px;
  color: #cbd5e1;
  font-size: 13px;
}

.container {
  max-width: 1100px;
  margin: auto;
  padding: 20px;
}

.layout {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 22px;
  align-items: start;
}

.panel {
  background: white;
  padding: 22px;
  border-radius: 12px;
  box-shadow: 0 4px 15px #0000000b;
}

h2 {
  color: #1d4ed8;
  font-size: 21px;
  margin-bottom: 18px;
}

h3 {
  font-size: 16px;
  margin: 20px 0 12px;
  color: #102b56;
}

label {
  display: block;
  font-size: 13px;
  font-weight: bold;
  margin: 13px 0 6px;
}

input, textarea {
  width: 100%;
  padding: 12px;
  border: 1px solid #cbd5e1;
  border-radius: 7px;
  font-size: 14px;
  font-family: inherit;
}

textarea {
  resize: vertical;
  min-height: 75px;
}

input:focus, textarea:focus {
  outline: 2px solid #93c5fd;
  border-color: #2563eb;
}

button {
  border: none;
  padding: 13px 18px;
  border-radius: 7px;
  cursor: pointer;
  font-weight: bold;
  font-size: 14px;
}

.download {
  background: #2563eb;
  color: white;
  width: 100%;
  margin-top: 18px;
}

.clear {
  background: #e2e8f0;
  color: #172033;
  width: 100%;
  margin-top: 9px;
}

#cv {
  background: white;
  padding: 28px;
  min-height: 700px;
  box-shadow: 0 4px 15px #00000012;
  overflow-wrap: anywhere;
}

.cv-header {
  border-bottom: 3px solid #2563eb;
  padding-bottom: 18px;
  margin-bottom: 20px;
}

.cv-header h1 {
  font-size: 29px;
  color: #102b56;
  margin-bottom: 7px;
}

.cv-header h4 {
  color: #2563eb;
  font-weight: normal;
  margin-bottom: 10px;
}

.contact {
  color: #475569;
  font-size: 12px;
  line-height: 1.8;
}

.cv-section {
  margin: 20px 0;
}

.cv-section h3 {
  color: #2563eb;
  border-bottom: 1px solid #dbeafe;
  padding-bottom: 7px;
  margin: 0 0 10px;
  text-transform: uppercase;
  letter-spacing: 1px;
}

.cv-section p {
  font-size: 13px;
  line-height: 1.7;
  white-space: pre-line;
  color: #334155;
}

.skills {
  display: flex;
  flex-wrap: wrap;
  gap: 7px;
}

.skill {
  background: #eff6ff;
  color: #1d4ed8;
  padding: 6px 10px;
  border-radius: 5px;
  font-size: 12px;
}

footer {
  text-align: center;
  color: #64748b;
  font-size: 12px;
  padding: 20px;
}

@media(max-width: 750px) {
  .layout {
    grid-template-columns: 1fr;
  }

  .container {
    padding: 12px;
  }

  .panel {
    padding: 16px;
  }

  #cv {
    padding: 20px;
  }
}

@media print {
  body {
    background: white;
  }

  header, .editor, footer, .preview-title {
    display: none !important;
  }

  .container {
    padding: 0;
    max-width: none;
  }

  .layout {
    display: block;
  }

  .panel {
    padding: 0;
    box-shadow: none;
  }

  #cv {
    box-shadow: none;
    min-height: auto;
    padding: 15mm;
    width: 100%;
  }

  @page {
    size: A4;
    margin: 0;
  }
}
</style>
</head>

<body>

<header>
  <h1>Smart CV Maker</h1>
  <p>Create Your Professional CV For Free</p>
</header>

<div class="container">

<div class="layout">

<!-- CV FORM -->

<div class="panel editor">

<h2>Build Your CV</h2>

<h3>Personal Information</h3>

<label>Full Name</label>
<input id="name" placeholder="Enter your full name">

<label>Professional Title</label>
<input id="job" placeholder="Web Developer / Designer">

<label>Email Address</label>
<input id="email" type="email" placeholder="your@email.com">

<label>Phone Number</label>
<input id="phone" placeholder="+880 1XXXXXXXXX">

<label>Address</label>
<input id="address" placeholder="Your city, country">

<h3>Professional Summary</h3>

<label>About Yourself</label>
<textarea id="summary"
placeholder="Write a short professional introduction..."></textarea>

<h3>Education</h3>

<label>Education Details</label>
<textarea id="education"
placeholder="BSc in Computer Science&#10;University Name&#10;2022 - 2026"></textarea>

<h3>Work Experience</h3>

<label>Experience Details</label>
<textarea id="experience"
placeholder="Job Title - Company Name&#10;2024 - 2026&#10;Describe your work..."></textarea>

<h3>Skills</h3>

<label>Your Skills (Separate with commas)</label>
<textarea id="skills"
placeholder="HTML, CSS, JavaScript, Communication"></textarea>

<h3>Projects</h3>

<label>Project Details</label>
<textarea id="projects"
placeholder="Project name and description"></textarea>

<button class="download" onclick="downloadCV()">
Download / Print CV as PDF
</button>

<button class="clear" onclick="clearForm()">
Clear All Information
</button>

</div>

<!-- LIVE CV PREVIEW -->

<div class="panel">

<h2 class="preview-title">Live CV Preview</h2>

<div id="cv">

<div class="cv-header">
<h1 id="out-name">Your Name</h1>
<h4 id="out-job">Your Professional Title</h4>
<div class="contact" id="out-contact">
Email | Phone | Address
</div>
</div>

<div class="cv-section">
<h3>Professional Summary</h3>
<p id="out-summary">Your professional summary will appear here.</p>
</div>

<div class="cv-section">
<h3>Education</h3>
<p id="out-education">Your education details will appear here.</p>
</div>

<div class="cv-section">
<h3>Work Experience</h3>
<p id="out-experience">Your experience will appear here.</p>
</div>

<div class="cv-section">
<h3>Skills</h3>
<div class="skills" id="out-skills">
<span class="skill">Your Skills</span>
</div>
</div>

<div class="cv-section">
<h3>Projects</h3>
<p id="out-projects">Your projects will appear here.</p>
</div>

</div>
</div>

</div>
</div>

<footer>
<p>Smart CV Maker © 2026 | Create Your Future</p>
</footer>

<script>

const fields = [
  "name", "job", "email", "phone",
  "address", "summary", "education",
  "experience", "skills", "projects"
];

function safeText(value) {
  return value.replace(/[&<>"']/g, function(char) {
    return {
      "&": "&amp;",
      "<": "&lt;",
      ">": "&gt;",
      '"': "&quot;",
      "'": "&#39;"
    }[char];
  });
}

function updateCV() {

  const get = id =>
    document.getElementById(id).value.trim();

  document.getElementById("out-name").textContent =
    get("name") || "Your Name";

  document.getElementById("out-job").textContent =
    get("job") || "Your Professional Title";

  const contacts = [
    get("email"),
    get("phone"),
    get("address")
  ].filter(Boolean);

  document.getElementById("out-contact").textContent =
    contacts.join(" | ") || "Email | Phone | Address";

  const sections = [
    ["summary", "out-summary",
     "Your professional summary will appear here."],
    ["education", "out-education",
     "Your education details will appear here."],
    ["experience", "out-experience",
     "Your experience will appear here."],
    ["projects", "out-projects",
     "Your projects will appear here."]
  ];

  sections.forEach(([input, output, placeholder]) => {
    document.getElementById(output).textContent =
      get(input) || placeholder;
  });

  const skills = get("skills")
    .split(",")
    .map(s => s.trim())
    .filter(Boolean);

  document.getElementById("out-skills").innerHTML =
    skills.length
    ? skills.map(skill =>
        `<span class="skill">${safeText(skill)}</span>`
      ).join("")
    : '<span class="skill">Your Skills</span>';
}

fields.forEach(id => {
  document.getElementById(id)
    .addEventListener("input", updateCV);
});

function downloadCV() {
  updateCV();
  window.print();
}

function clearForm() {
  if (!confirm("Are you sure you want to clear all information?")) {
    return;
  }

  fields.forEach(id => {
    document.getElementById(id).value = "";
  });

  updateCV();
}

updateCV();

</script>

</body>
</html>
