# System Architecture

## High Level Architecture

Guest Browser
→ React Frontend
→ Spring Boot API
→ MySQL Database

Kitchen Dashboard
→ React
→ Spring Boot

Admin Panel
→ React
→ Spring Boot

## Components

Frontend

* Menu UI
* Cart UI
* Order Tracking
* Kitchen Dashboard
* Admin Panel

Backend

* Menu Service
* Order Service
* User Service
* Auth Service

Database

* Users
* MenuItems
* Orders
* OrderItems

## Deployment

Browser
→ Nginx
→ Spring Boot
→ MySQL

## Security Layer

JWT authentication
Role-based access

## Scalability

Stateless backend
DB indexing on orders
