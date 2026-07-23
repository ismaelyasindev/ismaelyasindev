<div align="center">

# Hi, I'm Ismael Yasin

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=36BCF7&center=true&vCenter=true&width=800&height=45&lines=Cloud+%26+DevOps+Engineer;AWS+%7C+Terraform+%7C+Docker+%7C+Kubernetes+%7C+CI%2FCD;I+build+production-ready+infrastructure;Automate+everything" alt="Typing SVG" /></a>

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-ismaelyasin.site-2c5364?style=for-the-badge&logo=googlechrome&logoColor=white)](https://www.ismaelyasin.site)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ismael-yasin-782bbb320)
[![Email](https://img.shields.io/badge/Email-Get%20in%20touch-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ismaelsusulyman@gmail.com)

![Profile Views](https://komarev.com/ghpvc/?username=ismaelyasindev&color=36BCF7&style=flat-square&label=Profile+Views)

</div>

---

## About Me

I'm a Cloud and DevOps engineer who builds and runs real infrastructure on AWS. I like taking a project all the way from an empty account to something that serves live traffic, with the whole thing described in Terraform and deployed by a pipeline instead of by hand.

- Currently building NEXHost, an AI-powered restaurant management platform
- I work day to day with Terraform, multi-AZ VPCs, private subnets, and ECS
- Every project here deploys through GitHub Actions, from Docker build to Terraform apply to a post-deploy health check
- Right now I'm going deeper on Kubernetes and cloud-native design
- Open to Cloud and DevOps roles, and happy to talk shop any time

---

## Featured Projects

Each of these is running in production right now. The infrastructure is written in Terraform and shipped by a GitHub Actions pipeline.

### 🥇 [Threat Composer on ECS](https://github.com/ismaelyasindev/end-to-end-Threat-composer-ecs)

Live: [threat.ismaelawsdashboard.site](https://threat.ismaelawsdashboard.site)

A production deployment of Amazon's open-source threat modelling tool on AWS ECS Fargate. It runs behind an Application Load Balancer with SSL from ACM, sits in private subnets across two availability zones, and pulls its images from ECR. Three GitHub Actions workflows handle the Docker build, the Terraform apply, and a health check that confirms the deploy actually came up.

`AWS ECS` `Terraform` `Docker` `GitHub Actions` `ALB` `Route 53` `ECR` `React`

---

### 🥈 [UK Broadband Checker](https://github.com/ismaelyasindev/Uk_Broadband_Checker_S3_static_app)

Live: [ismaelbroadband.online](https://ismaelbroadband.online/)

A broadband availability checker modelled on Ofcom's official tool. The frontend is React, Vite and TypeScript served from S3 behind CloudFront, and the backend is a Node.js 20 Lambda. The Lambda validates every request before trusting it, keeps user data handling GDPR-conscious, caches lookups to cut repeat calls, and remembers its config from SSM. The test suite mocks the AWS SDK and covers the handler fully.

`S3` `CloudFront` `Lambda` `React` `TypeScript` `Tailwind CSS` `Vitest` `SSM`

---

### 🥉 [AWS Cost Dashboard on ECS](https://github.com/ismaelyasindev/AWS-cost-dasbord-ECS)

Live: [dashboard.ismaelawsdashboard.site](https://dashboard.ismaelawsdashboard.site)

A full-stack app for tracking AWS spend across accounts, with service breakdowns, a regional view, and budget alerts. A React frontend talks to a Node.js backend, both running as separate services on ECS across two availability zones, with scaling and monitoring wired in.

`AWS ECS` `Terraform` `Docker` `Node.js` `React` `GitHub Actions` `CloudWatch`

---

## Tech Stack

<div align="center">

**Cloud Platforms**

<img src="https://skillicons.dev/icons?i=aws,azure&theme=dark" alt="Cloud" />

**Infrastructure as Code & CI/CD**

<img src="https://skillicons.dev/icons?i=terraform,ansible,githubactions,git,github&theme=dark" alt="IaC and CI/CD" />

**Containers & Orchestration**

<img src="https://skillicons.dev/icons?i=docker,kubernetes,nginx&theme=dark" alt="Containers" />

**Monitoring & Observability**

<img src="https://skillicons.dev/icons?i=prometheus,grafana&theme=dark" alt="Monitoring" />

**OS & Scripting**

<img src="https://skillicons.dev/icons?i=linux,bash,python&theme=dark" alt="OS and Scripting" />

</div>

---

## GitHub Stats

<div align="center">

<img height="180" src="https://github-readme-stats-sigma-five.vercel.app/api?username=ismaelyasindev&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub Stats" />
<img height="180" src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=ismaelyasindev&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />

<br/>

<img src="https://streak-stats.demolab.com?user=ismaelyasindev&theme=tokyonight&hide_border=true" alt="GitHub Streak" />

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=ismaelyasindev&theme=tokyo-night&hide_border=true&area=true" alt="Contribution Activity Graph" />

</div>

---

## Contribution Graph

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ismaelyasindev/ismaelyasindev/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ismaelyasindev/ismaelyasindev/output/github-contribution-grid-snake.svg" />
  <img alt="Contribution snake animation" src="https://raw.githubusercontent.com/ismaelyasindev/ismaelyasindev/output/github-contribution-grid-snake.svg" />
</picture>

</div>

---

<div align="center">

### Get in touch

Open to Cloud and DevOps roles. Feel free to reach out.

</div>
