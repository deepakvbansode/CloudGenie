# CloudGenie — AI-Powered Internal Developer Platform (IDP)

## Overview

CloudGenie is an AI-powered Internal Developer Platform (IDP) built for the modern DevOps and developer teams.
It allows users to describe their application or infrastructure in natural language, and the AI automatically creates the Git repository, generates manifests, and deploys resources via Crossplane and ArgoCD — using GitOps best practices.

CloudGenie’s goal is to make application deployment as easy as saying:

“Deploy a Node.js service with MongoDB in dev and staging environments.”

## Primary Use Case

1. Developer Git SSO Login:
   As a developer, I should be able to log in using Git-based Single Sign-On (SSO), ensuring secure and seamless authentication with my existing GitHub or GitLab credentials.

2. Project Creation via Command:
   As a developer, when I issue a command to create a new project, the system should automatically generate the project scaffold (repository, CI/CD pipeline, and default configurations).

   If the command lacks specific details (e.g., database type or language runtime), the AI assistant should ask clarifying questions such as:
   “Do you need a database for this project?” or “Which language or framework do you want to use?”

   Once clarified, the system should create the full project structure accordingly.

3. DevOps Rule Enforcement and Template Creation:
   As a DevOps engineer, I should be able to define and enforce organizational standards and best practices via templates. For example:

   Database provisioning rules (naming conventions, instance types, regions).

   Microservice scaffolding templates with pre-defined CI/CD, logging, and monitoring setups.

   Security and compliance guardrails applied automatically during project creation.

4. AI-Assisted DevOps Configuration
   As a DevOps engineer, I can use AI to generate or refine templates, rules, and infrastructure configurations.

   I can describe desired behavior in natural language (e.g., “Create a template for a Node.js microservice with PostgreSQL and Prometheus monitoring”) and the AI will generate the YAML/Terraform templates automatically.

   The AI can also validate configurations against best practices or compliance rules and suggest improvements.

## Deliverables for Hackathon

1. Working demo with AI prompt → Git → ArgoCD → Deployed app
2. CloudGenie hosted on the AWS
3. Short video demo + pitch deck
4. Public GitHub repo with all code and manifests
5. Clear README & screenshots
