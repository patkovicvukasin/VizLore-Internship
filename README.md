# ZEST Data Service – Internship Project

This project was developed during an internship at VizLore LLC and focuses on
exploring data management and system integration using FIWARE technologies.

The application is designed to transform structured CSV data into multiple formats
(JSON, JSON-LD, NGSI v2) and publish the processed data to a FIWARE context broker.

## Features
- CSV file upload and validation
- Conversion of CSV data into:
  - JSON
  - JSON-LD
  - NGSI v2 entities
- Publishing transformed data to FIWARE Orion Context Broker
- Simple web interface for data upload
- Containerized development environment using Docker
- CI pipeline setup using GitHub Actions

## Architecture
The project is composed of several services orchestrated via Docker:

- **Backend**
  - Node.js & Express
  - Data transformation logic
  - Integration with FIWARE Orion Context Broker
- **Frontend**
  - React-based user interface
  - CSV upload form and basic interaction
- **Infrastructure**
  - FIWARE Orion Context Broker
  - MongoDB
  - Redis
  - Docker & Docker Compose

## Tech Stack
- Node.js
- Express
- React
- Docker & Docker Compose
- MongoDB
- Redis
- FIWARE Orion Context Broker
- GitHub Actions

## Notes
This repository contains a cleaned version of the internship project.
The focus is on demonstrating system integration, data transformation workflows,
and modern development practices rather than production deployment.

This project was developed as an academic and showcase application.


