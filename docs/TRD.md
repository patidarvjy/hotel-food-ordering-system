# Technical Requirements Document (TRD)

## System Overview

Web-based hotel food ordering system with React frontend and Spring Boot backend.

## Modules

* User Module
* Menu Module
* Order Module
* Kitchen Dashboard
* Admin Module

## Roles

* GUEST
* KITCHEN
* ADMIN

## APIs

### Menu

GET /api/menu
POST /api/menu
PUT /api/menu/{id}
DELETE /api/menu/{id}

### Orders

POST /api/orders
GET /api/orders/{id}
GET /api/orders/user/{userId}
PUT /api/orders/{id}/status

### Users

POST /api/users
GET /api/users/{id}

## Order Status

CREATED
CONFIRMED
PREPARING
READY
DELIVERED

## Entities

User

* id
* name
* role
* roomNumber

MenuItem

* id
* name
* description
* price
* available

Order

* id
* userId
* status
* createdAt

OrderItem

* id
* orderId
* menuItemId
* quantity

## Security

JWT authentication
Role-based authorization

## Validation

* Menu item must exist
* Quantity > 0
* Room number required for guest
