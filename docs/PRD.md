# Product Requirements Document (PRD)

## Product Name

Hotel Food Ordering System

## Problem Statement

Hotel guests currently place food orders via phone which causes delays, miscommunication, and lack of tracking.
The hotel needs a digital system for room service ordering and kitchen management.

## Goals

* Allow guests to order food from room
* Allow kitchen to manage orders
* Allow admin to manage menu
* Provide real-time order tracking

## Actors

* Guest
* Kitchen Staff
* Admin

## User Personas

### Guest

Hotel customer staying in a room who wants to order food easily.

### Kitchen Staff

Hotel kitchen employee preparing and delivering orders.

### Admin

Hotel manager maintaining menu and monitoring orders.

## User Stories

### Guest

* I want to browse menu so I can choose food
* I want to add items to cart
* I want to place order to my room
* I want to track order status

### Kitchen

* I want to see incoming orders
* I want to update order status
* I want to mark order ready

### Admin

* I want to add menu items
* I want to update menu items
* I want to view reports

## Functional Requirements

* Menu browsing
* Cart management
* Order placement
* Order tracking
* Kitchen dashboard
* Menu management

## Non-Functional Requirements

* Response time < 2s
* Mobile responsive
* Secure access by roles
* High availability

## Success Metrics

* 95% orders placed digitally
* Avg preparation time < 30 min
* Order errors reduced by 80%

## Scope

Single hotel deployment
Web application

## Non-Goals

* Payment gateway
* Multi-hotel support
* External delivery integration

