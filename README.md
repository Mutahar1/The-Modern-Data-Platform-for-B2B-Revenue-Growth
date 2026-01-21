# TwentyHQ The Modern Data Platform for B2B Revenue Growth

[![Build Status](https://img.shields.io/github/actions/workflow/status/twentyhq/twenty/ci.yml?branch=main&style=flat-square)](https://github.com/twentyhq/twenty/actions)
[![License](https://img.shields.io/github/license/twentyhq/twenty?style=flat-square)](https://github.com/twentyhq/twenty/blob/main/LICENSE)
[![Version](https://img.shields.io/github/package-json/v/twentyhq/twenty?style=flat-square)](https://github.com/twentyhq/twenty)
[![Issues](https://img.shields.io/github/issues/twentyhq/twenty?style=flat-square)](https://github.com/twentyhq/twenty/issues)

---

## Overview

TwentyHQ is a cutting-edge data platform designed specifically for B2B teams focused on accelerating revenue growth. It unifies, enriches, and activates customer and prospect data in real-time, empowering sales, marketing, and customer success teams to make smarter decisions and drive impactful business outcomes from a single source of truth.

---

## The Problem

B2B teams often struggle with:

- Fragmented and outdated data scattered across multiple systems  
- Low data accuracy leading to wasted outreach and missed opportunities  
- Complex and manual data enrichment processes  
- Difficulty activating clean data in operational workflows  
- Compliance challenges with data privacy regulations  

These challenges lead to inefficient sales cycles, poor customer engagement, and lost revenue potential.

---

## The Solution

TwentyHQ solves these issues by offering:

- **Unified Data Warehouse:** Centralize all your company and contact data in one clean, structured platform.  
- **Automated Enrichment:** Continuously refresh and enrich your data with accurate firmographic, technographic, and contact insights.  
- **Seamless Integrations:** Connect effortlessly with your favorite CRM, marketing automation, and analytics tools.  
- **Powerful Segmentation:** Build custom audiences and dynamic lists to drive targeted campaigns.  
- **Actionable Insights:** Activate data directly to sales and marketing workflows for timely outreach.  
- **Compliance-First:** Built with modern data privacy standards to keep your data safe and compliant.  

---

## Results & Benefits

By leveraging TwentyHQ, businesses have achieved:

- Increased sales pipeline velocity through better targeting and engagement  
- Reduced operational overhead by automating data management tasks  
- Improved marketing ROI with precise audience segmentation  
- Enhanced customer experiences via personalized interactions  
- Stronger compliance with GDPR, CCPA, and other regulations  

---

## Architecture

TwentyHQ’s modern architecture is designed for scale and reliability:

- **Data Ingestion Layer:** Aggregates data from multiple internal and external sources including CRMs and marketing platforms.
  ![image alt](https://github.com/Mutahar1/The-Modern-Data-Platform-for-B2B-Revenue-Growth/blob/a1c3d82d93c673ec42562a368b884a0c53f4e217/views-light.png)
  
- **Processing & Enrichment Layer:** Automated pipelines cleanse, de-duplicate, and enrich records continuously.

![image alt](https://github.com/Mutahar1/The-Modern-Data-Platform-for-B2B-Revenue-Growth/blob/a1c3d82d93c673ec42562a368b884a0c53f4e217/data-model-light.png)


- **Data Storage Layer:** Cloud-native, scalable warehouse to hold structured and semi-structured datasets.
![image alt](https://github.com/Mutahar1/The-Modern-Data-Platform-for-B2B-Revenue-Growth/blob/a1c3d82d93c673ec42562a368b884a0c53f4e217/plus-other-features-light.png)

- **API & Integration Layer:** Secure APIs expose data and functionality for downstream tools and applications.
![image alt](https://github.com/Mutahar1/The-Modern-Data-Platform-for-B2B-Revenue-Growth/blob/a1c3d82d93c673ec42562a368b884a0c53f4e217/permissions-light.png)

  
- **Frontend Layer:** React-based web UI offering dashboards, segmentation tools, and data management features.  

![image alt](https://github.com/Mutahar1/The-Modern-Data-Platform-for-B2B-Revenue-Growth/blob/a1c3d82d93c673ec42562a368b884a0c53f4e217/workflows-light.png)


---



## Technology Stack

- **Backend:** Node.js (v18.x), TypeScript (v5.x), PostgreSQL (v15.x), Redis (v7.x), Kafka (v3.x)  
- **Frontend:** React (v18.x), Redux (v8.x), Tailwind CSS (v3.x)  
- **Infrastructure:** AWS (S3, Lambda, RDS), Docker (v24.x), Kubernetes (v1.27.x)  
- **APIs:** RESTful, GraphQL  
- **Testing:** Jest, Cypress  

---

## Getting Started

1. **Clone the repo:**  
   `git clone https://github.com/twentyhq/twenty.git`

2. **Install dependencies:**  
   `yarn install` or `npm install`

3. **Configure environment variables:**  
   Create a `.env` file based on `.env.example` and update with your settings.

4. **Run database migrations:**  
   `yarn migrate` or `npm run migrate`

5. **Start the application:**  
   `yarn start` or `npm run start`

---

## Contribution

We welcome contributions! To contribute:

- Fork the repository  
- Create a new feature branch  
- Write clear, concise commit messages  
- Include tests for new features or bug fixes  
- Submit a pull request with detailed description and motivation  

---

## License

This project is licensed under the Apache 2.0 License. See [LICENSE](https://github.com/twentyhq/twenty/blob/main/LICENSE) for details.
