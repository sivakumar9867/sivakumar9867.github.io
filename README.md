# Siva Kumar — Developer Portfolio

Personal portfolio for **Derangula Siva Kumar**, a Computer Science & Engineering student specializing in Artificial Intelligence at Parul University.

🌐 **Portfolio:** [sivakumar.tech](https://sivakumar.tech)

## Portfolio sections
- About and professional experience
- Four README-informed projects with individual repository and README links
- Skills, including AI/ML and AWS & Cloud Computing
- AWS Labs with a featured AWS VPC Peering project, featured VPC Peering project, three category overview cards and 17 grouped hands-on tasks, each with a preview and its own evidence PDF
- Internship certificates as separate files with individual previews and links, including the SAP Generative AI Developer certification and original EWB AWS internship completion certificate
- Full additional-certification collection with previews and source documents
- Academic Honors & Scholarships, including the Yuva Unstoppable Merit Scholarship
- Career interests: SAP Technical Consultant, Software Engineering, Energy Data Analytics, Systems Engineer, and Associate Product Engineer
- Document viewer navigation with Back, Certificates, Foundation & Future, and Experience links; external LinkedIn/GitHub/repository/README links open in the same tab so browser Back returns to the portfolio

## Selected projects
1. [SAP Generative AI-Based Customer Feedback Analysis and Issue Prioritization System](https://github.com/sivakumar9867/sap-generative-ai-feedback-analyzer) — SAP AI Launchpad Prompt Editor workflow for sentiment analysis, issue classification, order/product reference extraction, structured JSON, multi-issue prioritization and actionable resolution points. Includes a six-image screenshot gallery and a task-specific comparison of Gemini 2.5 Flash Lite, GPT-4.1 nano and GPT-5-Mini. The observed Gemini result is described as a project example, not a universal benchmark.
2. [Employee Salary Prediction](https://github.com/sivakumar9867/Employee-Salary-Prediction) — Adult Census Income classification; README reports KNN 82.69%, Logistic Regression 82.73%, and MLP 85.18% accuracy.
3. [Movie Recommendation System](https://github.com/sivakumar9867/movie-recommendation-system) — content-based recommendations using TF-IDF and cosine similarity, served through Flask.
4. [Marks Calculator](https://github.com/sivakumar9867/marks-calculator) — Flask application with live total/average previews, validation, per-subject result indicators, and a print-friendly report.

## Featured AWS VPC Peering project
The AWS section features a dedicated VPC Peering project page with the problem statement, internship context, architecture diagram, configuration notes, test outcomes and individually explained screenshot evidence.

## AWS hands-on tasks
The AWS landing section shows three category cards. Select a category to open its dedicated page, then use “View Project” to open an individual task page with technical details and an embedded evidence PDF. Back links and browser history return you to the previous level:
- **Networking & Security:** VPC and private subnet, Security Groups, Network ACLs, Route 53 Private DNS
- **Compute, Storage & Hosting:** EC2 and Application Load Balancer, Auto Scaling, S3 tasks, EBS, EFS and lifecycle/monitoring setup
- **Identity, Data & Monitoring:** Lambda, IAM, RDS MySQL, DynamoDB Streams and CloudWatch alarms

All 17 task cards include preview images, expandable technical steps and learning outcomes, and individual PDF evidence.

## Folder structure
```text
.
├── assets/
│   ├── aws-vpc-peering/    # VPC peering evidence screenshots
│   ├── aws-vpc-peering-architecture.svg
│   ├── aws-previews/       # 17 AWS task preview images
│   ├── aws-proofs/         # 17 individual task evidence PDFs
│   ├── certificates/       # PDF originals for full viewing/download, plus PNG card previews
│   ├── previews/           # Certificate preview images
│   └── Siva_Kumar_Resume.pdf
├── CNAME
├── README.md
└── index.html
```

## Deployment
Static HTML/CSS/JavaScript site intended for GitHub Pages. Upload the full folder so relative asset links continue to work.

## Contact
- Email: sivakumar986@outlook.com
- LinkedIn: https://linkedin.com/in/sivakumar986
- GitHub: https://github.com/sivakumar9867


## Recent polish
- Experience summaries now align with the README-supported model comparison and Marks Calculator features.
- The additional certification section is titled **Foundation & Future**, with five compact cards per row on wide desktop screens and responsive columns on smaller screens.
- Internship certificates link to individual certificate files rather than relying on a combined PDF. The SAP certification is first, and the AWS internship card uses the original EWB certificate rather than a demo preview.
- Academic scholarship wording specifies renewal each year.

## Section navigation
Contextual navigation links use the existing button styles and link to relevant portfolio sections, individual project repositories/READMEs, resume, certificates, email, GitHub, and LinkedIn. No layout, color, typography, card sizing, or animation redesign was made for this update.
## Contextual navigation

Section-end navigation is intentionally selective to avoid clutter. Projects keep repository and README links on their own cards; AWS Labs links to cloud skills and certificates; Skills links to related projects, AWS Labs and certifications; internship certificates link to the additional collection and resume; Foundation & Future links to certificates and related skills; Academic Honors links to credentials and LinkedIn. The existing layout, colors, typography, spacing, cards and animations are preserved.


## Navigation update
- The hero Cloud Technology card now reads “Building scalable solutions”.
- Removed extra navigation shortcut rows below sections; the main navbar remains unchanged.
- Local resume, certificate, and AWS evidence links open in the current tab so browser Back returns to the portfolio.

## Navigation and document viewing
- External destinations (LinkedIn, GitHub, repositories and READMEs) open in a new tab, leaving the portfolio open in its original tab. The portfolio cannot inject a back button into third-party websites.
- Local resume, certificate and AWS evidence links open through `document.html`, which provides a visible **Back to Portfolio** button and a download action.
- The homepage hero includes a direct **Download Resume** button, and the AI / ML orbit card reads **Ideas into reality**.
