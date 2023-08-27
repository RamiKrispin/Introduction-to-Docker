# Introduction to Docker for Data Scientists  🐳.

🚧WIP 🏗️, pre spell checking🛠️

Docker has a variety of applications in the domain of data science and MLOps. It enables a high level of reproducibility, which is one of the core foundations of data science. Along with its benefits, Docker has some learning curve, and the goal of this tutorial is to reduce the entry barrier for data scientists to Docker.


**Table of Content:**
- Motivation
- Installation
- General workflow
- The Dockerfile
- Build an image
- Run a container


## Motivation

In my data science career, one of the major technical milestones was (after learning how to code and adopting Git) - learning and starting to use Docker. It opened a new world of opportunities, from automating processes to deploying data science work in production. This section defines what Docker is and its data science applications. 

### What is Docker?

Docker is a CI/CD tool that enables seamless code deployment from development to production environments. By creating OS-level virtualization, it can package an application and its dependencies in a virtual container and ship it between different environments. The main advantages of using Docker within your development environment are:
- **Reproducibility -** Docker enables you to seamlessly package your code and its dependencies into a single container and execute, test, share, and deploy it with a high level of consistency
- **Collaboration -** Docker solves the dependencies madness when a team of developers works together on a specific project. Having a unified environment saves a ton of time during the development step. For example, if one developer gets some error, it is easy for other developers to reproduce the error and help debug it
- **Deployment -** Docker simplifies the code shipment from the development environment to the production

### Docker for Data Science
