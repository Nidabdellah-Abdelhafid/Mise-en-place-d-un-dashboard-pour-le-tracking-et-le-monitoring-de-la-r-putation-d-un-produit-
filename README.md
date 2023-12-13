# Product Reputation Tracking and Monitoring Dashboard

## Overview

This repository contains the necessary components to set up a dashboard for tracking and monitoring the reputation of a product. The system is designed to collect data from various sources, process it, and visualize it through a dashboard for insightful analysis.

## Workflow

### 1. Add Source Image

Before setting up the dashboard, ensure that you have the necessary source images related to the product's reputation. Place these images in the designated folder.

### 2. Execution of Docker Compose

To deploy the necessary services, use the provided `docker-compose.yml` file. Follow the steps below:

#### Step 1: Initialize Airflow

```bash
docker-compose up airflow-init
