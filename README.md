# rudder-stack-task
# Alert Manager

## Overview
This project sets up an alert management system that receives alerts via a webhook, enriches the alert data, and sends a notification to Slack.

## Setup

### Prerequisites
- Docker
- Kubernetes cluster
- Prometheus and Alertmanager set up in your Kubernetes cluster

### Steps

1. **Build Docker Image:**
   docker build -t your-dockerhub-username/alert-manager:latest .

2. **Push Docker Image:**
   docker push your-dockerhub-username/alert-manager:latest
