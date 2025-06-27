# Scalable Static Website with S3 + CloudFront + GitHub Actions
This project demonstrates a scalable, secure, and automated static website deployment using **AWS S3** for hosting, **CloudFront** for global CDN + HTTPS, and **GitHub Actions** for CI/CD.

##  Objective
> Host and auto-deploy a static website using S3 (Free Tier) with global delivery via CloudFront and HTTPS support. Deployments are triggered automatically on GitHub pushes.

## Tools & Technologies
- **AWS S3** – Static website hosting (Free Tier)
- **Amazon CloudFront** – Global CDN + HTTPS
- **GitHub Actions** – CI/CD workflow to sync files to S3
- **HTML/CSS** – Static site content
- **Git** – Version control and scripting

##  Project Structure
├── index.html
├── error.html
└── .github/
└── workflows/
└── deploy.yml
