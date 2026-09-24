# CampusBite
Campus Canteen Pre-Ordering System 

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