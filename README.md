# Personal Portfolio Website

This repository showcases personal portfolio website, a digital platform designed to highlight my skills, projects, and experiences. It serves as a comprehensive overview of my professional journey and creative work.

<hr><br>

## Purpose of This Repository

This repository houses personal portfolio website, a digital showcase of my skills, projects, and experiences. It serves as a centralized platform for:

- **Self-Promotion:** Highlighting abilities and achievements.
- **Project Showcase:** Displaying a curated collection of work.
- **Professional Networking:** Connecting with potential employers and collaborators.
- **Personal Branding:** Establishing a strong online identity.

<hr><br>

## Demonstration

Here are code demonstrations of functions and components used in the portfolio website:

### HTML

```html
<!-- Example of a project card -->
<div class="project-card" id="project-1">
  <h3 id="project-title">Project Title</h3>
  <p id="project-description">Project description goes here.</p>
  <a id="project-link" href="#">View Project</a>
</div>
```

### CSS

```css
/* Example CSS for the project card */
.project-card {
  border: 1px solid #ccc;
  padding: 16px;
  margin: 16px;
  border-radius: 8px;
  transition: box-shadow 0.3s ease;
}

.project-card:hover {
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}
```

### JavaScript

```javascript
// Example function to display project details
function displayProjectDetails(projectId) {
  const project = projects.find((p) => p.id === projectId);
  if (project) {
    document.getElementById("project-title").innerText = project.title;
    document.getElementById("project-description").innerText =
      project.description;
    document.getElementById("project-link").href = project.link;
  }
}
```

<hr><br>

## Features

- Responsive design for optimal viewing on all devices.
- Interactive project gallery with detailed descriptions.
- Contact form for easy communication.
- Blog section to share insights and updates.

<hr><br>

## Technologies Used

- **Frontend:** HTML, CSS, JavaScript
- **Deployment:** Vercel

<hr><br>

## Project Setup

1. **Clone this repository**

```bash
git clone https://github.com/guanshiyin28/Personal-Portofolio-Website.git
```

2. **Navigate to the project directory**

```bash
cd Personal-Portofolio-Website
```

<hr><br>

## Steps to Run

1. **Open the `index.html` file in your browser.**

<hr><br>

## License

This project is licensed under the Apache-2.0 License. See the [LICENSE](LICENSE) file for details.

<hr><br>

<div align="center">
   <a href="https://www.instagram.com/guanshiyin_/">
      <img src="https://capsule-render.vercel.app/api?type=waving&height=200&color=100:393E46,20:F7F7F7&section=footer&reversal=false&textBg=false&fontAlignY=50&descAlign=48&descAlignY=59"/>
   </a>
</div>
