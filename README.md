# Resources for Blog Post: "Invoking LLM from Cloud Integration Responsibly – Made Easy with Generative AI Hub in SAP AI Core"

This repository is a collection of resources for the blog post **"Invoking LLM from Cloud Integration Responsibly – Made Easy with Generative AI Hub in SAP AI Core"**.

## Contents

1. **CAP Project Reference**: A Cloud Application Programming (CAP) project designed to manage Business Partner data. This project demonstrates how to structure and implement a CAP-based service for handling Business Partner details.

2. **CPI iFlow**: A zip archive containing the CPI iFlow. This iFlow ensures that Business Partner changes trigger compliant AI-generated email notifications, while maintaining data consistency in HANA Cloud. It leverages SAP Advanced Event Mesh, CAP, and Generative AI Hub for an automated end-to-end process.

## CAP Project Overview

The CAP project is located in the `businesspartner_srv/` directory and includes:

- **Domain Models**: Defined in `db/schema.cds`.
- **Service Logic**: Implemented in `srv/cat-service.js` and `srv/cat-service.cds`.
- **Deployment Configuration**: Specified in `mta.yaml`.

## CPI iFlow Overview

The CPI iFlow is provided as a zip archive (`AEM_GenAI_BPMailGenerator_blog.zip`) and can be imported into Cloud Integration capability of SAP Integration Suite. It integrates with the CAP service, AI Core Orchestration service, and SAP Advanced Event Mesh to trigger complaint AI-generated email notifications.

## Getting Started

Refer to the respective README files in the CAP project directory for setup instructions. For the CPI iFlow, import the zip archive into your SAP Integration Suite tenant and configure it as per the blog post instructions.

## Learn More

For detailed implementation steps and insights, visit the [blog post](https://community.sap.com/).