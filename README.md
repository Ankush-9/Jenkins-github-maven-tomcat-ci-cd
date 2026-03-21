# CI/CD Pipeline using Jenkins, GitHub, Maven and Tomcat

This project demonstrates a basic CI/CD pipeline setup using Jenkins by integrating GitHub, Maven, and Apache Tomcat. The focus is on understanding how these tools work together in a practical workflow.

---

## Project Overview

In this setup:

* GitHub is used to reference the application repository
* Jenkins is used to automate the build and deployment process
* Maven is used to package the application into a `.war` file
* Tomcat is used as the deployment server

The pipeline is triggered manually using the "Build Now" option in Jenkins (no Poll SCM or webhooks are configured). Each time the job runs, Jenkins pulls the latest code, builds it, and deploys it to the Tomcat server.

---

## Workflow (High-Level)

```
GitHub → Jenkins → Maven Build → WAR File → Tomcat → Browser
```

---

## Repository Overview

This repository mainly focuses on documentation and demonstration of the CI/CD setup rather than storing the actual application code.

* `docs/` contains the complete theory and detailed explanation of the setup
* `screen-shots/` contains images that provide an overview of key steps, configurations, and successful execution stages
* `README.md` provides a summary of the project

The screenshots are not a full step-by-step guide but help in understanding the overall flow and major milestones.

The actual application used in the pipeline is fetched from an external GitHub repository during the Jenkins build process.

For detailed command-based setup, configurations, and step-by-step explanation, refer to:
`docs/theory.txt`

---

## What This Project Shows

* Basic understanding of a CI/CD pipeline
* Integration of Jenkins with GitHub, Maven, and Tomcat
* Manual build and deployment process
* Practical understanding of a DevOps workflow

---

## Credits

The sample application used in this project is taken from:
https://github.com/Haider7214/SpringApp.git

---

## Final Note

This project is a simple demonstration of how a CI/CD pipeline works. It focuses on the flow from pulling code to deployment and helped build a practical understanding of integrating multiple DevOps tools.

