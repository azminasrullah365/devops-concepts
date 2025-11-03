# Cloud & DevOps Technology Summary

This repository provides a quick reference guide summarizing key terms and services discussed in modern cloud computing and DevOps practices.

---

## ☁️ General & Foundational IT Concepts

# 🌐 Cloud, CI/CD, and AI Glossary

A curated glossary of cloud computing, DevOps, and AI-related terms — for quick reference and onboarding.

---

## 📖 Table of Contents

- ⚡ [General Cloud Terms](#-general-cloud-terms)
  - [CDN (Content Delivery Network)](#cdn-content-delivery-network)
  - [Vendor Lock-in](#vendor-lock-in)
  - [DigitalOcean](#digitalocean)
  - [SonarQube](#sonarqube)
- 🚀 [Google Cloud Platform (GCP) Services](#-google-cloud-platform-gcp-services)
  - [Cloud Run](#cloud-run)
  - [Google Cloud Build](#google-cloud-build)
  - [GKE (Google Kubernetes Engine)](#gke-google-kubernetes-engine)
  - [Vertex AI](#vertex-ai)
- 🛒 [Amazon Web Services (AWS) Services](#-amazon-web-services-aws-services)
  - [AWS RDS (Relational Database Service)](#aws-rds-relational-database-service)
  - [AWS S3 (Simple Storage Service)](#aws-s3-simple-storage-service)
  - [AWS ECS (Elastic Container Service)](#aws-ecs-elastic-container-service)
  - [AI Inference on AWS](#ai-inference-on-aws)
  - [AWS Bedrock AgentCore](#aws-bedrock-agentcore)
  - [Jakarta Region](#jakarta-region)
- 🛠️ [CI/CD, Configuration, & AI Protocols](#️-cicd-configuration--ai-protocols)
  - [cloud-init](#cloud-init)
  - [GitLab Runner](#gitlab-runner)
  - [GitHub Actions](#github-actions)
  - [Cloudflare Workers](#cloudflare-workers)
  - [MCP (Model Context Protocol)](#mcp-model-context-protocol)

---

## ⚡ General Cloud Terms

### CDN (Content Delivery Network)
A globally distributed network of servers that caches web content (images, videos, pages) and delivers it from the location physically closest to the end-user, reducing latency and improving site speed.

### Vendor Lock-in
A situation where a customer cannot easily migrate from one vendor's product or service to a competitor's without significant technical difficulties, high costs, or business disruption (often due to proprietary tech or high data egress fees).

### DigitalOcean
A cloud infrastructure provider known for its simple, developer-friendly platform, affordable "Droplet" VMs, and straightforward pricing, catering primarily to startups and SMBs.

### SonarQube
An open-source platform that performs continuous static analysis of source code to identify bugs, security vulnerabilities (SAST), and code smells across many programming languages.

---

## 🚀 Google Cloud Platform (GCP) Services

### Cloud Run
A serverless platform for running containerized applications that automatically scales based on demand (even to zero), ideal for web requests and event-driven workloads.

### Google Cloud Build
A serverless CI/CD platform that automates the building, testing, and deployment of software using a series of steps defined in a configuration file.

### GKE (Google Kubernetes Engine)
A fully managed Kubernetes orchestration service that simplifies deploying, managing, and scaling containerized applications by handling control plane management and automation.

### Vertex AI
Google Cloud's unified platform for managing the entire AI/ML lifecycle, combining data science tools, MLOps, and generative AI interfaces (like Gemini and AutoML).

---

## 🛒 Amazon Web Services (AWS) Services

### AWS RDS (Relational Database Service)
A managed service that automates the setup, operation, scaling, and patching of popular relational databases (Aurora, MySQL, PostgreSQL, Oracle, etc.).

### AWS S3 (Simple Storage Service)
A highly durable, scalable, object storage service used for data lakes, backups, static website hosting, and general application storage.

### AWS ECS (Elastic Container Service)
A fully managed container orchestration service for Docker, offering both EC2 (self-managed VM) and Fargate (serverless) compute options.

### AI Inference on AWS
The process of running trained machine learning models in production using AWS services (like SageMaker) and specialized hardware (like Inferentia chips) to make real-time predictions.

### AWS Bedrock AgentCore
A suite of serverless services for building, deploying, and operating highly capable AI agents at scale, providing infrastructure for security, memory management, and tool integration.

### Jakarta Region
AWS's operational data center region in Indonesia (Asia Pacific - Jakarta, ap-southeast-3), launched in December 2021.

---

## 🛠️ CI/CD, Configuration, & AI Protocols

### cloud-init
An open-source tool used for automating the initial configuration of virtual machines (VMs) upon their first boot (e.g., setting hostname, users, running setup scripts).

### GitLab Runner
The execution agent that runs the jobs defined within a GitLab CI/CD pipeline.

### GitHub Actions
A CI/CD platform built into GitHub for automating workflows (builds, tests, deploys) using runners.

### Cloudflare Workers
A serverless edge computing platform that runs JavaScript/WASM code physically close to users via V8 isolates, providing ultra-low latency execution.

### MCP (Model Context Protocol)
A new open-source standard that provides a standardized, secure way for AI models (LLMs) to access real-time external data and execute actions using tools/APIs.

---

📘 *Maintained by [Your Name or GitHub Handle]*  
💡 *Contributions welcome! Feel free to submit a pull request with additional terms or corrections.*
