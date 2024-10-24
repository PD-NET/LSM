[![SAST CODEQL](https://img.shields.io/badge/SAST-CODEQL-voilet.svg)](https://github.com/github/codeql)
[![DAST: WAPITI](https://img.shields.io/badge/DAST-WAPITI-indigo.svg)](https://github.com/wapiti-scanner/wapiti)
[![Functional Testing: Selenium](https://img.shields.io/badge/:Functional_Testing-Selenium-blue.svg)](https://github.com/SeleniumHQ/selenium)
[![Dynamic Testing: Code_Coverage](https://img.shields.io/badge/:Dynamic_Testing-Code_Coverage-green.svg)](https://github.com/marketplace/codecov)
[![Container: Docker](https://img.shields.io/badge/:Container-Docker-yellow.svg)](https://github.com/docker/getting-started)
[![IAC: Terraform](https://img.shields.io/badge/:IAC-Terraform-orange.svg)](https://github.com/hashicorp/terraform)

# PG DISSERTATION MANAGEMENT SYSTEM

## INTRODUCTION TO THE PROJECT

The PG dissertation is a partial requirement for fulfilling the PG degree. Major steps include:

- Selection of topics based on departmental thrust ideas.
- Maintaining student-guide ratios.
- Avoiding duplication and addressing ethical issues.

## CI/CD
### CONTINUOUS INTEGRATION
```mermaid
graph LR;
    A[PLAN]-->B[CODE];
    B-->C[BUILD];
    C-->D[TEST];
    D-->B;
