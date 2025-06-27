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

##  GitHub Actions CI/CD Workflow
├── index.html
├── error.html
└── .github/
└── workflows/
└── deploy.yml

##  Live Website
[https://d25s3q6kn8penm.cloudfront.net](https://d25s3q6kn8penm.cloudfront.net)

## Cloudfrount + S3 integration steps
### Steps Completed:

1.Created S3 bucket (nishant-devops-website) with static website hosting enabled

2.Uploaded index.html and error.html

3.Disabled "Block Public Access" and applied a public bucket policy

4.Created a CloudFront distribution
- Origin set to: nishant-devops-website.s3-website-us-east-2.amazonaws.com
- Set Viewer Protocol Policy to Redirect HTTP to HTTPS

5.Linked CloudFront to the bucket with OAC. 


