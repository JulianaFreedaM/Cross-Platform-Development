# Cross-Platform-Development
# Video Sharing Application - API Specifications

This repository contains the **OpenAPI (Swagger 3.0.3)** specifications for the microservices of a video sharing platform. These specs define the API contracts and are useful for documentation, client SDK generation, and integration.

---

## Microservices Overview

### 1.Content Service - https://github.com/Sneha-kb1/Content-Service
- **File:** `content_service.yaml`
- **Responsibilities:**
  - Upload videos
  - Fetch videos by name or platform
  - Retrieve all video metadata

### 2.Subscription Service - https://github.com/Sneha-kb1/Subscription-Service
- **File:** `subscription_service.yaml`
- **Responsibilities:**
  - Manage user subscriptions
  - OTT video subscriptions
  - Check and list user-specific OTT subscriptions

### 3.User Service - https://github.com/Sneha-kb1/User-Service
- **File:** `user_service.yaml`
- **Responsibilities:**
  - Register new users
  - User login
  - Change user passwords

### Other services used 
- API Gateway - https://github.com/Sneha-kb1/API-Gateway
- Service Discovery - https://github.com/Sneha-kb1/Service-Discovery
- Front-End - https://github.com/JulianaFreedaM/frontend
---

