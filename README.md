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