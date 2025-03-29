# DevSecOps Pipeline Implementation for a NodeJS Application

This document outlines the requirements and stages for implementing a DevSecOps pipeline for “OWASP Juice Shop,” a popular open-source deliberately vulnerable e-commerce application.

## Project Description

### Title: DevSecOps Pipeline Implementation for Deliberately Vulnerable Application

Description: This project focuses on implementing a DevSecOps pipeline for “OWASP Juice Shop,” a Node.js and Angular application designed to teach developers about common security vulnerabilities and how to secure applications against them.
Repository Link: OWASP Juice Shop

Application Architecture:

- Modern web application
- Backend: Node.js
- Frontend: Angular
- RESTful architecture
- Containerized with Docker

Requirements

- Pipeline Stages:
- Static Application Security Testing (SAST)
- Dynamic Application Security Testing (DAST)
- Software Bill of Materials (SBOM)
- Software Composition Analysis (SCA)
- Secrets Scanning

Reporting Mechanism: Findings from each stage must be aggregated into a single open-source platform like DefectDojo (https://github.com/DefectDojo).
CI/CD Platform: Utilize an open-source CI/CD platform (e.g., GitHub Actions, GitLab CI/CD, Jenkins) to orchestrate the pipeline.

Submission Requirements: Submit your code as a Gitlab repository containing screenshots of successful scans and identified vulnerabilities.

Reporting Platform
Name: DefectDojo
Link: https://github.com/DefectDojo/django-DefectDojo

Description: Use DefectDojo to consolidate and report findings from all pipeline stages (SAST, DAST, SBOM, SCA, Secrets Scanning).
Submission Guidelines

Repository: Submit your project as a public GitLab repository.
Screenshots: Include screenshots of all successful scans and the vulnerabilities found in your repository.
