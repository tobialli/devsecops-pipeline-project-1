# DevSecOps Pipeline for NexusCore Technologies

![Security Pipeline](https://img.shields.io/badge/Security-Pipeline-green)
![GitHub Actions](https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-blue)
![AWS](https://img.shields.io/badge/Cloud-AWS-orange)

## Project Overview

This repository demonstrates a production-ready DevSecOps pipeline built for **NexusCore Technologies**, a Series A fintech startup processing $2M in daily transactions. The pipeline implements automated security scanning at every stage of the development lifecycle.

### Business Context
- **Client**: NexusCore Technologies (Fintech - Payment Processing)
- **Challenge**: 3 security incidents in Q4, investors demanding improved security posture
- **Solution**: Shift-left security approach with automated scanning in CI/CD

## Security Tools Implemented

| Tool | Purpose | Stage |
|------|---------|-------|
| **CodeQL** | Static Application Security Testing (SAST) | Build |
| **Trivy** | Dependency & Container Scanning (SCA) | Build |
