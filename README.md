# DevOps Workshop - Assignment 1

[README PORTFOLIO](https://barmoshe.github.io/DevOps_Workshop_Assignment1/)

## Overview

This assignment marks the beginning of the DevOps Workshop at Wix, focusing on setting up critical DevOps tools and practicing Git workflows. The goal is to configure necessary environments such as GitHub with SSH keys, install essential software like Terraform and AWS CLI, and push the initial commit to a new GitHub repository.

## Prerequisites

- GitHub account
- Familiarity with Git commands and SSH
- macOS or Linux (for Homebrew and command-line setups)

## Steps

### 1. Create GitHub Account and Generate SSH Keys

SSH keys ensure secure communication with GitHub. Follow the instructions in the [GitHub documentation](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) to generate and add your SSH key for authentication.

### 2. Install Homebrew (Package Manager)

Homebrew simplifies the installation of software on macOS and Linux, making it an essential tool for managing dependencies in DevOps:
- [Install Homebrew](https://brew.sh/)

### 3. Install Terraform (Infrastructure as Code)

Terraform is a key tool for Infrastructure as Code (IaC), allowing us to manage and provision cloud resources efficiently:
- [Install Terraform](https://tfswitch.warrensbox.com/Installation/)

In the workshop, we will work extensively with Terraform to manage infrastructure on AWS using Amazon EKS (Elastic Kubernetes Service). You'll learn to automate resource management through code, which is an industry-standard practice for scalable infrastructure setups.

### 4. Install AWS CLI (Command Line Interface)

The AWS CLI allows you to interact with AWS services from your terminal, automating tasks like provisioning infrastructure and managing resources:
- [Install AWS CLI](https://formulae.brew.sh/formula/awscli)

### 5. Set Up AWS Keys

You will receive your AWS Access Keys on the first day of the workshop. Once provided, configure them using the following command:
```bash
aws configure
```
This will prompt you to input the AWS access and secret keys.

### 6. Create a New GitHub Repository

Follow these steps to create and initialize your project:

1. **Create a new repository** on GitHub from the web interface.
2. **Clone** the repository locally:
```bash
git clone <repository-url>
```
3. **Create a README.md file** with this content.
4. **Stage the file** for commit:
```bash
git add README.md
```
5. **Commit your changes**:
```bash
git commit -m "Initial commit for DevOps Workshop"
```
6. **Push the changes** to GitHub:
```bash
git push origin main
```

### 7. Practice Git Commands

Familiarize yourself with the following Git commands. These commands are essential for managing your codebase throughout the workshop:

- **Clone a repository**:
```bash
git clone <repo-url>
```
- **Switch branches**:
```bash
git checkout <branch-name>
```
- **Stage files for commit**:
```bash
git add <file-name>
```
- **Undo changes** with reset:
```bash
git reset
```
- **Commit changes** with a message:
```bash
git commit -m "Commit message"
```
- **Push changes** to the remote repository:
```bash
git push origin <branch-name>
```
- **Pull the latest changes** from the remote repository:
```bash
git pull origin <branch-name>
```
- **View commit history**:
```bash
git log
```

For more advanced commands like branching and rebasing, see the [Git documentation](https://git-scm.com/doc) for further learning.

---

### Additional Learning:
- **Terraform**: Throughout the workshop, we will deploy infrastructure using Terraform and automate configurations with Helm Charts on AWS EKS. By the end of this workshop, you'll be able to create scalable infrastructure, manage microservices, and leverage DNS and Helm for deployment.

- **AWS CLI**: Mastering AWS CLI will be crucial for automating AWS services, particularly as we work with VPCs, EC2 instances, and EBS storage.

---
