# Malinda Wanga — Personal Portfolio

> A responsive personal portfolio website for **Malinda Wanga**, a full-stack developer based in Gauteng, South Africa.

[![Live Portfolio](https://img.shields.io/badge/Live%20Portfolio-malindawanga.me-1f2937?style=for-the-badge)](https://malindawanga.me/)
[![GitHub](https://img.shields.io/badge/GitHub-WANGAMALINDA-181717?style=for-the-badge&logo=github)](https://github.com/WANGAMALINDA)

## Overview

This repository contains the source code for Malinda Wanga's personal portfolio website. The site presents professional experience, education, technical skills, certifications, accomplishments, selected projects, and contact information in a clean, responsive interface.

The portfolio is built with standard web technologies and is designed to be fast, accessible, easy to maintain, and deployable as a static website.

## Live Website

Visit the live portfolio at:

**[https://malindawanga.me/](https://malindawanga.me/)**

## Features

- Responsive layout for desktop, tablet, and mobile screens
- Personal introduction and professional profile
- Featured project showcase with external links
- Education and experience timeline
- Technical skills grouped by frontend, backend, databases, deployment, and version control
- Professional skills and language proficiency section
- Downloadable CV
- Downloadable certification documents
- Contact links for email, telephone, and GitHub
- Custom favicon and web app manifest
- Social sharing metadata for Open Graph and Twitter/X
- Smooth reveal animations powered by the Intersection Observer API
- Mobile navigation menu with accessible labels and focus-friendly controls
- Custom domain configuration through GitHub Pages

## Featured Projects

| Project | Description | Link |
| --- | --- | --- |
| **Qhawelethu Wellness Counselling** | Client-facing counselling platform with booking and enquiry flows backed by Supabase. | [Visit site](https://qhawelethuwc.co.za) |
| **QhaWear** | Fashion-focused storefront and brand showcase website. | [Visit site](https://www.qhawear.com/) |
| **TrackServ** | Civic reporting platform that helps communities report issues and track service requests. | [View project](https://github.com/WANGAMALINDA/TrackServ) |
| **Exclusive Chillas** | Lifestyle and brand showcase with a responsive visual presentation. | [Visit site](https://wangamalinda.github.io/Exclusive-Chillas/) |
| **SpareXpress Auto** | Automotive spare-parts e-commerce experience with product listings and modern UX. | [Visit site](https://wangamalinda.github.io/SpareXpress-Auto/) |
| **Innovative Tech Solutions** | Corporate technology services showcase website. | [Visit site](https://wangamalinda.github.io/Innovative-Tech-Solutions/) |

Additional projects and work samples are available on the [live portfolio](https://malindawanga.me/#projects).

## Technology Stack

### Frontend

- HTML5
- CSS3
- JavaScript
- Responsive web design
- Google Fonts
- Devicon

### Development and Deployment

- Git
- GitHub
- GitHub Pages
- Custom domain configuration

The portfolio is intentionally lightweight and does not require a frontend framework or build system to run locally.

## Repository Structure

```text
.
├── Assets/                 # Profile images, icons, certificates, and other assets
├── CNAME                  # Custom domain used by GitHub Pages
├── Malinda_Wanga_CV.pdf   # Downloadable CV
├── favicon.ico             # Site favicon
├── index.html              # Main portfolio page
├── llms.txt               # Structured portfolio information
├── sitemap.xml             # Search-engine sitemap
└── style.css              # Main stylesheet
```

## Run Locally

### Prerequisites

Any modern web browser is enough to view the site. A local development server is recommended to ensure assets and downloads behave consistently.

### Using Python

1. Clone the repository:

   ```bash
   git clone https://github.com/WANGAMALINDA/Portfolio.git
   cd Portfolio
   ```

2. Start a local server:

   ```bash
   python -m http.server 8000
   ```

3. Open the website in your browser:

   ```text
   http://localhost:8000
   ```

### Using Visual Studio Code

If you use Visual Studio Code, install the **Live Server** extension, then open `index.html` with Live Server.

## Deployment

This project can be deployed as a static website using GitHub Pages.

1. Push the project to a GitHub repository.
2. Open the repository's **Settings** page.
3. Go to **Pages**.
4. Select the `main` branch as the deployment source.
5. Select the root folder `/`.
6. Save the configuration.
7. If using a custom domain, keep the `CNAME` file in the repository root and configure the matching DNS records with your domain provider.

The current site uses the custom domain configured in `CNAME`.

## Customisation

To update the portfolio:

- Edit the content and sections in `index.html`.
- Update colors, layout, animations, and responsive styles in `style.css`.
- Replace images and documents inside `Assets/`.
- Replace `Malinda_Wanga_CV.pdf` with an updated CV using the same filename, or update the download links in `index.html`.
- Update `sitemap.xml` when the public site URL or page structure changes.
- Keep `llms.txt` aligned with the portfolio's current projects, skills, education, and contact details.

## Contact

- **Website:** [malindawanga.me](https://malindawanga.me/)
- **GitHub:** [@WANGAMALINDA](https://github.com/WANGAMALINDA)
- **Email:** [wangamalinda4@gmail.com](mailto:wangamalinda4@gmail.com)
- **Location:** Gauteng, South Africa

## Education and Professional Focus

Malinda Wanga is completing a Diploma in Information Technology at Richfield Graduate Institute of Technology in Pretoria, with a focus on software and website development. Current areas of interest include full-stack development, responsive user interfaces, database-backed applications, cloud fundamentals, and practical technology solutions for businesses and communities.

## Certifications and Recognition

The portfolio includes certificates and recognition related to:

- Python
- JavaScript
- C++
- HTML
- React
- C#
- Ethical hacking
- AWS and cloud fundamentals
- AWS Cloud Practitioner fundamentals
- AWS Elastic VMware Services
- Academic achievement, teamwork, leadership, and project delivery

## License

No open-source license has been specified for this repository. Unless otherwise stated, the portfolio content, designs, photographs, CV, and other original materials remain the property of Malinda Wanga.
