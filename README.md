# Home Lab Kubernetes

A personal home-lab Kubernetes cluster designed for continuous learning, experimentation, and best-practice development.

---

## Overview

This repository contains all of the code, configuration and documentation needed to stand up a resilient, promotable Kubernetes cluster in my home environment. It’s a safe space to “Find Learnings” as I explore:

- Cluster architecture and networking  
- CI/CD  
- DevOps pipelines (CI/CD)  
- AI enablement scenarios on Kubernetes  

> **Note:** This is a living repository. Expect significant changes as my skill and understanding evolves.

---

## Technologies & Tools

- **Talos Linux** (Kubernetes OS)
- **Argo CD** (GitOps for Kubernetes)
- **Helm** (package management)    
- **YAML** (configuration driven)
 
---

## Repository Structure

```text
.
├── envs/
  ├── development/
    ├── apps/
    ├── platform/
      ├── argocd/
  ├── staging/
  ├── production/
└── README.md
