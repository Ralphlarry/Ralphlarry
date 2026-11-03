# Lanre Awe

Infrastructure and DevOps engineer in Lagos, Nigeria.

I ran the servers, network and backups for an oil and gas company for 18 years, until January 2026. Now I do the same kind of work in the cloud, and I build and host websites for clients through [Ralph Network](https://ralphnetwork.online).

I'm looking for a DevOps, cloud or platform engineering role, remote or in Lagos.

## Projects

**[petclinic-infrastructure](https://github.com/Ralphlarry/petclinic-infrastructure)**
Spring PetClinic microservices on AWS EKS, built on my own. Terraform creates the platform, GitHub Actions builds the images, Argo CD deploys them, and HPA and Karpenter handle scaling. The cluster is shut down between runs to save cost. `make up` runs Terraform and installs the add-ons and Argo CD.

**[spring-petclinic-genai-chatbot](https://github.com/Ralphlarry/spring-petclinic-genai-chatbot)**
My part of DMI Group 9's final project: getting the PetClinic app's AI chat service working on Azure OpenAI with Spring AI. The group deployed the app to AKS with Helm and Azure Pipelines.

**[epicbook-infra](https://github.com/Ralphlarry/epicbook-infra) and [epicbook-app](https://github.com/Ralphlarry/epicbook-app)**
A DMI project. I forked the course's book review app (Next.js, Express, MySQL), renamed it EpicBook and deployed it to Azure. Terraform creates the network, VMs and database, and Azure Pipelines runs Terraform and then Ansible on a self-hosted agent.

**[theepicbook](https://github.com/Ralphlarry/theepicbook)**
Another DMI project: the course's Express and Handlebars app containerised with a two-stage Dockerfile, Docker Compose, an Nginx reverse proxy and healthchecks.

## Coursework

The archived repos here are my assignments from the DevOps Micro Internship (Cohort 2, January to May 2026). I uploaded them together when the programme ended, so each has a single commit.

## Contact

[LinkedIn](https://www.linkedin.com/in/olanrewaju-awe-62761758) · ralphnetwork@gmail.com
