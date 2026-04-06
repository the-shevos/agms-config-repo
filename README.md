# 🌱 AGMS Microservices Project

This is a Spring Boot microservices-based system for agriculture management (AGMS).  
It includes services like authentication, sensor data, automation, crop inventory, zone management, and API gateway.

---

## 🚀 Technologies Used

- Java 17+
- Spring Boot
- Spring Cloud (Gateway, Eureka, Config Server)
- MySQL
- JWT Authentication
- REST APIs

---

## 🧩 Microservices

### 1. API Gateway
- Port: 8080
- Routes all requests to services
- Handles authentication filter

### 2. Auth Service
- Port: 8085
- Manages user login & JWT token generation

### 3. Zone Service
- Port: 8081
- Manages zone-related data

### 4. Sensor Service
- Port: 8082
- Handles sensor data and IoT integration

### 5. Automation Service
- Port: 8083
- Manages automation rules (temperature, humidity)

### 6. Crop Inventory Service
- Port: 8084
- Manages crop data and inventory

---

## 🗄️ Databases

Each service uses its own MySQL database:

- agms_auth_db
- agms_zone_db
- agms_sensor_db
- agms_automation_db
- agms_crop_db

---

