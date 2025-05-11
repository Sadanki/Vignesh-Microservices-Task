# Microservices-Task

## Overview
This document provides details on testing various services after running the `docker-compose` file. These services include User, Product, Order, and Gateway Services. Each service has its own endpoints for testing purposes.

---

## Services and Endpoints

### **User Service**
- **Base URL:** `http://localhost:3000`
- **Endpoints:**
  - **List Users:**  
    ```
    curl http://localhost:3000/users
    ```
    Or open in your browser: [http://localhost:3000/users](http://localhost:3000/users)
    
![image](https://github.com/user-attachments/assets/4d926b56-c684-42ab-a80c-353146c4c141)

---

### **Product Service**
- **Base URL:** `http://localhost:3001`
- **Endpoints:**
  - **List Products:**  
    ```
    curl http://localhost:3001/products
    ```
    Or open in your browser: [http://localhost:3001/products](http://localhost:3001/products)

    ![image](https://github.com/user-attachments/assets/f8523785-d954-4078-9ca5-40baa45be033)


---

### **Order Service**
- **Base URL:** `http://localhost:3002`
- **Endpoints:**
  - **List Orders:**  
    ```
    curl http://localhost:3002/orders
    ```
    Or open in your browser: [http://localhost:3002/orders](http://localhost:3002/orders)
    ![image](https://github.com/user-attachments/assets/19dc6248-e386-4f3c-8f37-6ce2f8a3750c)


---

### **Gateway Service**
- **Base URL:** `http://localhost:3003/api`
- **Endpoints:**
  - **Users:**
  - ![image](https://github.com/user-attachments/assets/aeb9916a-88ec-4b8e-b326-efb85c2a406c)

    ```
    curl http://localhost:3003/api/users
    ```
  - **Products:**

    ```
    curl http://localhost:3003/api/products
    ![image](https://github.com/user-attachments/assets/1ffd5db6-158b-4dda-961d-e9dc72ee8b1c)

    ```
  - **Orders:**  
    ```
    curl http://localhost:3003/api/orders
    ![image](https://github.com/user-attachments/assets/4ce0d041-9d0f-43f8-9d59-6f076f0195be)

    ```

---

## Instructions
1. Start all services using the `docker-compose` file:
   ```
   docker-compose up
   ```
2. Once the services are running, use the above endpoints to verify the functionality.

Happy testing!
