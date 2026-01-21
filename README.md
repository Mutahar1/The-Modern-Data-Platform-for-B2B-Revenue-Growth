# TwentyHQ  The Modern Data Platform for B2B Revenue Growth

[![Build Status](https://img.shields.io/github/actions/workflow/status/twentyhq/twenty/ci.yml?branch=main&style=flat-square)](https://github.com/twentyhq/twenty/actions)
[![License](https://img.shields.io/github/license/twentyhq/twenty?style=flat-square)](https://github.com/twentyhq/twenty/blob/main/LICENSE)
[![Version](https://img.shields.io/github/package-json/v/twentyhq/twenty?style=flat-square)](https://github.com/twentyhq/twenty)
[![Issues](https://img.shields.io/github/issues/twentyhq/twenty?style=flat-square)](https://github.com/twentyhq/twenty/issues)


TwentyHQ is a powerful and modern data platform designed to help B2B teams accelerate revenue by unifying, enriching, and activating customer and prospect data seamlessly.

With TwentyHQ, businesses can get accurate, real-time company and contact data to power smarter sales, marketing, and customer success workflows all from a single, easy-to-use platform.

---

## Why TwentyHQ?

In today’s fast-paced B2B environment, having clean, reliable, and up-to-date data is critical. TwentyHQ offers:

- **Comprehensive B2B Data**: Access millions of companies and contacts with deep firmographic and technographic insights.
- **Real-time Data Enrichment**: Enrich your CRM and marketing systems with fresh, verified data continuously.
- **Flexible Integrations**: Connect with popular CRMs, marketing tools, and BI platforms effortlessly.
- **Custom Segmentation & Targeting**: Build tailored audiences for personalized campaigns and outreach.
- **Data Activation**: Sync clean data directly into your sales, marketing, and analytics tools to drive action.
- **Compliance & Privacy**: Adheres to modern data protection standards, keeping your data safe and compliant.

---

## Core Features

- **Unified Data Warehouse**: Consolidate disparate data sources into one clean, organized repository.
- **Enrichment Pipelines**: Automate the updating and cleansing of company and contact records.
- **Segment Builder**: Create dynamic segments using flexible filters and attributes.
- **Integrations**: Native connectors to Salesforce, HubSpot, Marketo, Outreach, Slack, and more.
- **API Access**: Full-featured REST APIs to access and manipulate your data programmatically.
- **User-Friendly UI**: Intuitive dashboards and visualizations to monitor data quality and engagement.

---

## Architecture Overview

TwentyHQ is built on a modern microservices architecture that ensures scalability, reliability, and flexibility:

- **Data Ingestion Layer**: Ingests data from multiple sources including CRMs, marketing platforms, and external data providers.
- **Processing & Enrichment Layer**: Cleanses, de-duplicates, and enriches data continuously using automated pipelines.
- **Storage Layer**: Stores structured and semi-structured data in a scalable, cloud-native data warehouse.
- **API & Integration Layer**: Exposes data and features through secure APIs and integrations.
- **Frontend Layer**: A React-based web interface providing easy access to data management and insights.

---

## Tech Stack

- Backend: Node.js (v18.x), TypeScript (v5.x), PostgreSQL (v15.x), Redis (v7.x), Kafka (v3.x)  
- Frontend: React (v18.x), Redux (v8.x), Tailwind CSS (v3.x)  
- Infrastructure: AWS (S3, Lambda, RDS), Docker (v24.x), Kubernetes (v1.27.x)  
- APIs: RESTful APIs, GraphQL  
- Testing: Jest, Cypress  

---

## Getting Started

1. **Clone the repository:**  
   `git clone https://github.com/twentyhq/twenty.git`

2. **Install dependencies:**  
   `yarn install` or `npm install`

3. **Configure environment variables:**  
   Create a `.env` file based on `.env.example` and add your configuration.

4. **Run migrations:**  
   `yarn migrate` or `npm run migrate`

5. **Start the application:**  
   `yarn start` or `npm run start`

---

## Contribution

We welcome contributions from the community! To contribute:

- Fork the repo  
- Create a feature branch  
- Write tests for your changes  
- Submit a pull request with clear description and rationale

---

## License

Licensed under the Apache 2.0 License.
