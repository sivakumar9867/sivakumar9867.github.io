# Siva Kumar — Portfolio 2026

Personal portfolio for **Derangula Siva Kumar**, a Computer Science & Engineering student specializing in Artificial Intelligence at Parul University.

🌐 **Portfolio:** [sivakumar.tech](https://sivakumar.tech)

## Introduction

The homepage introduces Siva Kumar as a developer focused on building scalable applications and automating workflows to turn ideas into execution. The visual direction is an **engineering fieldbook**: warm paper surfaces, graphite typography, restrained oxide-copper accents, numbered notes and evidence-led project storytelling. The hero includes a seven-slide, manually navigable field-note carousel covering the five selected software projects, the ongoing LeetCode / DSA practice feature and the featured AWS VPC Peering build. Its slide counter is fixed in a consistent footer position.

## Portfolio sections

- About, education, professional interests and an Experience timeline covering four internship experiences
- Five selected projects, each with its own internal project-detail page, repository link and README link
- LeetCode / DSA practice feature linking to a C++ repository with problem-wise solutions, topic-wise practice and a progress dashboard
- Skills across programming, development, tools, AI/ML and AWS cloud technologies
- AWS Labs: a featured VPC Peering detail page and 17 individual AWS task detail pages, with previews, technical steps, learning outcomes and evidence PDFs
- Certificates, including internship credentials, the SAP Generative AI Developer certification and the NPTEL Elite Introduction to Internet of Things certificate
- Additional certificates with previews and source documents
- Academic Honors & Scholarships, including the Yuva Unstoppable Merit Scholarship
- Contact links, downloadable resume and a document viewer for PDFs and certificate images

## Selected projects

1. [SAP Generative AI-Based Customer Feedback Analysis and Issue Prioritization System](https://github.com/sivakumar9867/sap-generative-ai-feedback-analyzer) — SAP AI Launchpad Prompt Editor workflow for sentiment analysis, issue classification, order/product reference extraction, structured JSON, multi-issue prioritization and actionable resolution points. Its internal case-study page includes six screenshots and a task-specific comparison of Gemini 2.5 Flash Lite, GPT-4.1 nano and GPT-5-Mini. The observed Gemini result is described as a project example, not a universal benchmark.
2. [Employee Salary Prediction](https://github.com/sivakumar9867/Employee-Salary-Prediction) — Adult Census Income classification; project README reports KNN 82.69%, Logistic Regression 82.73%, and MLP 85.18% accuracy.
3. [Mana Cinema — Telugu Movie Recommendation System](https://github.com/sivakumar9867/movie-recommendation-system) — content-based recommendations using TF-IDF and cosine similarity, served through Flask.
4. [MARKS / LAB — Result Studio](https://github.com/sivakumar9867/marks-calculator) — Flask application with live total/average previews, validation, per-subject result indicators and a print-friendly report.
5. [Personal Portfolio Website](https://github.com/sivakumar9867/sivakumar9867.github.io) — responsive portfolio built with HTML, CSS and JavaScript, deployed through GitHub Pages with a custom domain, project case studies, document viewer and AWS evidence.

Each project case study opens at `project.html?project=<project-id>` in the **same browser tab**. It retains the Fieldbook navigation and offers Back to Projects and Back to Portfolio controls.

## DSA practice

The [LeetCode Solutions repository](https://github.com/sivakumar9867/leetcode-solutions) is presented as a half-width project-style card within the selected-work grid, using the same visual panel and content layout as the other cards. It contains C++ problem-wise solutions, topic-wise practice and an automatically maintained progress dashboard. The card links to the repository, the progress dashboard and the root README; live practice statistics remain in the repository dashboard rather than being hardcoded on the website.

## Experience and certificates

The Experience timeline presents four internship experiences. The NPTEL **Introduction to Internet of Things** certificate is featured separately in the Certificates section. The 12-week course ran from July–October 2026 and was completed with an Elite certificate, a 62% consolidated score, 25/25 in online assignments, 36.75/75 in the proctored exam and 4 recommended credits. The original certificate is available at `assets/certificates/nptel-introduction-to-internet-of-things.pdf` through the website's document viewer.

## AWS hands-on work

The AWS section features a dedicated VPC Peering page with the problem statement, internship context, architecture diagram, configuration notes, test outcomes and 17 individually explained evidence screenshots. The other 17 hands-on tasks are grouped into networking and security; compute, storage and hosting; and identity, data and monitoring. Each task opens its own detail route at `aws-project.html?task=<number>` in the same browser tab. VPC Peering uses `aws-project.html?type=vpc-peering`.

## Document viewer

Local resume, certificate and AWS evidence links open through `document.html`. It provides Back and Download actions, an embedded PDF viewer, and an image viewer with fit, zoom, 100%, download and print controls. All internal navigation stays in the current tab; GitHub, LinkedIn and Credly are genuine external destinations and also open in the current tab.

## Folder structure

```text
.
├── assets/
│   ├── aws-vpc-peering/    # VPC Peering evidence screenshots
│   ├── aws-vpc-peering-architecture.svg
│   ├── aws-vpc-peering-project-report.pdf
│   ├── aws-vpc-peering-target-architecture.png
│   ├── aws-previews/       # AWS task preview images
│   ├── aws-proofs/         # Individual AWS evidence PDFs
│   ├── certificates/      # Certificate originals and selected previews
│   ├── previews/           # Optimized WebP thumbnails and other certificate previews
│   └── Siva_Kumar_Resume.pdf
├── CNAME
├── index.html
├── project.html
├── aws-project.html
├── document.html
├── human-centered-ai-resume.html
└── README.md
```

## Deployment

Static HTML, CSS and JavaScript site intended for GitHub Pages. Keep the complete `assets/` folder beside all five HTML files, including `human-centered-ai-resume.html`, so relative image, certificate, resume and evidence links continue to work.

## Contact

- Email: sivakumar986@outlook.com
- LinkedIn: https://linkedin.com/in/sivakumar986
- GitHub: https://github.com/sivakumar9867

## Crafted by

Designed, developed and crafted by **Derangula Siva Kumar**. The portfolio's content, implementation, page structure and custom refinements were created for this personal website.

## Image assets and optimization

The site uses lightweight WebP thumbnails for images that appear in the page layout:

- `assets/previews/siva-kumar-profile.webp` — the 36 × 36 px navigation portrait used across the homepage, project details, AWS details and document viewer.
- `assets/previews/ewb-aws-internship-completion.webp` — AWS internship certificate card preview.
- `assets/previews/sap-certified-generative-ai-developer.webp` — SAP certification card preview.
- `assets/previews/nptel-introduction-to-internet-of-things.webp` — NPTEL IoT certificate card preview.

The original profile PNG and certificate PNG/PDF files are retained. The original profile image remains available for social-preview metadata, while the original certificate documents are opened in the document viewer for full-quality viewing and download. The four WebP thumbnails total 115,556 bytes, compared with 4,519,195 bytes for the corresponding original PNGs (approximately 97.4% less image data for these four page thumbnails).

## Accessibility and loading

The six primary certificate cards in the homepage Certificates section start loading eagerly and use asynchronous image decoding, so they can be ready before visitors scroll to that section. The longer Additional Certifications gallery remains lazy-loaded to avoid fetching every lower-page thumbnail during initial page load.

- Main pages include a keyboard-accessible “Skip to main content” link and a focusable main landmark.
- The shared muted text colour was darkened to improve contrast against the site's paper and card backgrounds.
- Google Fonts use stylesheet links with preconnect hints rather than CSS `@import`.
- Certificate-card images use lazy loading and asynchronous decoding; reduced-motion preferences and visible keyboard focus styles are retained.

## Latest visual refinements

- The navigation brand uses the optimized Siva Kumar WebP portrait at the same 36 × 36 px footprint as the former SK stamp.
- The About section keeps the introduction and the Education, Target Roles and Goals panels without a duplicate profile card.
