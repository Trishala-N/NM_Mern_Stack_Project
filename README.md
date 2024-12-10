Lancers - A Freelancing Application Using MERN Stack

Lancers is a next-generation freelancing platform designed to revolutionize how clients connect with skilled freelancers. The platform provides a seamless experience for project posting, bidding, collaboration, and secure transactions, ensuring transparency and efficiency for both clients and freelancers.

Table of Contents
- Project Overview
- Features
- System Architecture
- Setup Instructions
- API Documentation
- User Interfaces
- Technologies Used
- Contributors

Project Overview

Lancers empowers:
- Clients: Post projects, review freelancer proposals, and manage projects efficiently.
- Freelancers: Browse projects, submit bids, and build a reputation through successful projects.

Key features include:
- Real-time communication tools.
- Integrated feedback and review system.
- Secure payment processing.
- A reputation-building system for freelancers.

Features

For Clients
- Project Posting: Intuitive interface to post detailed projects.
- Freelancer Selection: Access to profiles, portfolios, and reviews.
- Communication Tools: Real-time chat for collaboration.
- Feedback and Ratings: Provide reviews for completed work.

For Freelancers
- Project Discovery: Filterable project listings.
- Proposal Submission: Submit tailored bids with portfolio samples.
- Profile Management: Showcase skills and completed projects.
- Reputation Building: Gain visibility through client feedback.

Admin Features
- User Management: Monitor and manage user accounts.
- Project Oversight: Track and manage all projects.
- Dispute Resolution: Address conflicts between clients and freelancers.

System Architecture

Frontend
- Frameworks and Libraries: React.js, Bootstrap, Material-UI.
- Features:
  - Responsive user dashboards.
  - Real-time chat system.
  - Notification system for updates.

Backend
- Framework: Express.js with Node.js runtime.
- Features:
  - Role-based access control.
  - API handling for users, projects, and messaging.
  - Secure transaction processing.

Database
- Type: MongoDB (NoSQL)
- Stored Data:
  - User profiles, project details, bids, and transactions.
  - Real-time chat records.

Setup Instructions

Prerequisites
1. Install Node.js, npm, and MongoDB.
2. Recommended IDE: Visual Studio Code.

Backend Setup
1. Navigate to the backend directory:
   cd server
2. Install dependencies:
   npm install
3. Start the backend server:
   node index.js

Frontend Setup
1. Navigate to the frontend directory:
   cd client
2. Install dependencies:
   npm install
3. Start the development server:
   npm start

API Documentation

API base URL: http://localhost:5000/api

Endpoints Overview
1. User Management:
   - Register: POST /users/register
   - Login: POST /users/login
   - Fetch User: GET /users/:id

2. Project Management:
   - Create Project: POST /projects
   - Get Projects: GET /projects
   - Update Status: PUT /projects/:projectId/status

3. Chat Management:
   - Fetch Chat: GET /chats/:id
   - Send Message: POST /chats/:id

[Full API documentation available in the repository.]

User Interfaces

Freelancer Interface
- Dashboard with stats and notifications.
- Project listings and bidding system.
- Real-time chat with clients.

Client Interface
- Dashboard for active and completed projects.
- Tools for posting projects and reviewing applications.

Admin Interface
- Comprehensive management dashboards for users and projects.
- Tools for resolving disputes and monitoring transactions.

Technologies Used
- Frontend: React.js, Bootstrap, Material-UI
- Backend: Node.js, Express.js
- Database: MongoDB
- Communication: RESTful APIs, WebSocket
- Version Control: Git

Contributors
- Jai J
- Niroshini v
- Trishala
- Vidya J
