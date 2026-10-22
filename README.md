# Shiela Rose Marilao — IT Support & Operations Portfolio

This repository contains the source for Shiela Rose Marilao's portfolio website, positioned for IT support, technical operations, infrastructure support, and troubleshooting opportunities.

## Featured hands-on projects
- **AWS Static Website & CI/CD:** S3, CloudFront, CodePipeline, and GitHub.
- **Containerized Application Infrastructure:** Terraform, AWS EC2, Docker Compose, Redmine, MySQL, and NGINX.
- **Infrastructure Monitoring & Incident Notifications:** Prometheus, Grafana, Uptime Kuma, n8n, and Telegram. The local incident-summary component is experimental.

Projects are presented as personal hands-on projects, not employment assignments.

## Website files
The deployable static website is in the `files/` directory:
- `index.html` — main portfolio
- `styles.css` — responsive styling
- `script.js` — navigation and scroll effects
- `cicd.html`, `hybrid-redmine.html`, `cloud-monitoring.html` — project detail pages
- `images/` — website images
- `Shiela_Rose_Marilao_Resume.pdf` — downloadable résumé

## Deploying with Vercel
Configure the Vercel project to use `files` as the Root Directory if this repository's folder structure is deployed as-is. This is a static HTML/CSS/JavaScript site and does not require a build command. Set the output directory to `.` (or leave the framework preset as Other with the root directory set to `files`). After committing changes to the connected Git branch, Vercel should deploy automatically.

Review the published website and test all links after deployment.
