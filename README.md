# CampusBite
Campus Canteen Pre-Ordering System 

## 2. Problem Statement & Project Scope
### Contribution: Vedanti

### Problem Statement

College canteens often experience long queues during peak
hours. Manual food ordering and payment processes can cause
delays, crowding, and difficulty in managing multiple orders.

Students may have to wait for a long time just to place an
order and collect their food. Canteen staff may also face
challenges in managing orders during busy hours.

### Proposed Solution

CampusBite provides an online pre-ordering system where
students can browse the menu, place food orders, select
pickup time slots, and track their order status.

Canteen staff can manage incoming orders, update food
availability, and monitor daily sales through a dashboard.

### Project Scope

- Online food pre-ordering for college students.
- Food menu browsing and category selection.
- Pickup time slot selection.
- Order and pickup token management.
- Order status tracking.
- Canteen staff order and menu management.
- Basic daily sales summary.


## 3. Features & User Roles
### Contribution: Pushkar

CampusBite provides separate features for students and
canteen staff to make food ordering and management easier.

### Student Features

- Student registration and login.
- View food items by category.
- Filter Veg and Non-Veg food items.
- Add items to cart and manage quantities.
- Select pickup time slots.
- Complete mock payment checkout.
- Receive a unique pickup token.
- Track order status.
- View previous orders.

### Canteen Staff Features

- Staff login and dashboard.
- View incoming orders in a kitchen queue.
- Update order status.
- Manage food item availability.
- View daily sales summary.
- Monitor completed orders.

### User Roles

1. Student – Can browse menus, place orders, and track them.
2. Staff – Can manage menu availability and process orders.

## 4. Technologies & System Architecture
### Contribution: Aditya

CampusBite uses modern web development technologies to
provide a responsive frontend, backend services, and
database management.

### Technologies Used

- Frontend: React.js
- Backend: Node.js and Express.js
- Database: MongoDB
- Authentication: JSON Web Token (JWT)
- API Testing: Postman
- Version Control: Git and GitHub
- Code Editor: Visual Studio Code

### System Architecture

The application follows a client-server architecture.

1. React.js provides the student and staff interfaces.
2. Node.js and Express.js handle application logic and APIs.
3. MongoDB stores user, menu, time slot, and order data.
4. JWT is used to authenticate users and manage access.

### Application Flow

Student / Staff
       |
       v
React.js Frontend
       |
       v
Node.js + Express.js Backend
       |
       v
MongoDB Database

---
## 5. Database Design & API Overview
### Contribution: Arnav

CampusBite uses MongoDB to store and manage application
data through collections.

### Main Database Collections

1. Users
   Stores student and staff information, login credentials,
   and user roles.

2. Menu Items
   Stores food names, categories, prices, dietary tags,
   and availability status.

3. Time Slots
   Stores pickup slot details, order capacity, and
   availability.

4. Orders
   Stores student orders, ordered items, total amount,
   pickup token, payment status, and order status.

### Important API Endpoints

#### Authentication APIs

- POST /api/auth/register
- POST /api/auth/login

#### Menu APIs

- GET /api/menu
- PATCH /api/menu/:id/toggle

#### Time Slot APIs

- GET /api/slots

#### Order APIs

- POST /api/orders
- GET /api/orders/my-orders
- GET /api/orders/kitchen-queue
- PATCH /api/orders/:id/status

These APIs help the frontend communicate with the backend
and perform different application operations.
## Project Introduction

CampusBite is a Campus Canteen Pre-Ordering System developed
to make food ordering in college canteens easier and faster.

The system allows students to view the available menu,
add food items to their cart, place orders, and select
pickup slots without waiting in long queues.

It also provides a staff panel where canteen staff can
manage orders, update food availability, and track daily sales.

The main goal of CampusBite is to reduce waiting time,
improve canteen management, and provide a smooth
food-ordering experience for students and staff.