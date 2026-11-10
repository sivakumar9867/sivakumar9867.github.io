# Siva Kumar — Portfolio 2026

Personal portfolio for **Derangula Siva Kumar**, a Computer Science & Engineering student specializing in Artificial Intelligence at Parul University.

🌐 **Portfolio:** [sivakumar.tech](https://sivakumar.tech)

## Introduction

The homepage introduces Siva Kumar as a developer focused on building scalable applications and automating workflows to turn ideas into execution. The visual direction is an **engineering fieldbook**: warm paper surfaces, graphite typography, restrained oxide-copper accents, numbered notes and evidence-led project storytelling. The hero includes a six-slide, manually navigable field-note carousel covering the five selected projects and the featured AWS VPC Peering build. Its slide counter is fixed in a consistent footer position.

## Portfolio sections

- About, education, professional interests and internship experience
- Five selected projects, each with its own internal project-detail page, repository link and README link
- Skills across programming, development, tools, AI/ML and AWS cloud technologies
- AWS Labs: a featured VPC Peering detail page and 17 individual AWS task detail pages, with previews, technical steps, learning outcomes and evidence PDFs
- Internship certificates, including the SAP Generative AI Developer certification and original EWB AWS internship completion certificate
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
│   ├── aws-previews/       # AWS task preview images
│   ├── aws-proofs/         # Individual AWS evidence PDFs
│   ├── certificates/      # Certificate originals and selected PNGs
│   ├── previews/           # Certificate card previews
│   └── Siva_Kumar_Resume.pdf
├── CNAME
├── index.html
├── project.html
├── aws-project.html
├── document.html
└── README.md
```

## Deployment

Static HTML, CSS and JavaScript site intended for GitHub Pages. Keep the complete `assets/` folder beside all four HTML files so relative image, certificate, resume and evidence links continue to work.

## Contact

- Email: sivakumar986@outlook.com
- LinkedIn: https://linkedin.com/in/sivakumar986
- GitHub: https://github.com/sivakumar9867

## Crafted by

Designed, developed and crafted by **Derangula Siva Kumar**. The portfolio's content, implementation, page structure and custom refinements were created for this personal website.

The visual direction was informed by [UnsLOP](https://github.com/heydamir/unslop) by Damir Sokolovsky, licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

The visible site edition label is **Portfolio 2026**.


## Profile image

The About/Profile section uses the original profile photograph at `assets/siva-kumar-profile.png`.

## Latest visual refinements

- The navigation brand uses the supplied Siva Kumar portrait at the same 36 × 36 px footprint as the former SK stamp.
- The About section keeps the introduction and the Education, Target Roles and Goals panels without a duplicate profile card.
