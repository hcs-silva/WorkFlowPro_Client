# **WorkFlowPro - Freelance Job & Proposal Platform**

## **Project Overview**

**WorkFlowPro** is a web-based freelance job platform that connects clients and developers for project collaboration. Clients can post job listings, and developers can submit proposals, chat in real-time, manage tasks, and track progress. The platform also includes review systems for both clients and developers after project completion.

---

## **Tech Stack**

### **Frontend Tech Stack**

- React (Vite for fast build and bundling)
- Tailwind CSS (Utility-first CSS framework)
- React Router (For navigation)
- Axios (For API calls)
- Socket.io (For real-time messaging)
- Formik & Yup (For forms and validation)

### **Backend Tech Stack**

- Node.js & Express (For the server)
- MongoDB with Mongoose (For data storage)
- JWT (JSON Web Tokens for authentication)
- bcrypt (For password hashing)
- Cloudinary/S3 (For file uploads)
- Stripe (Optional for payment processing)
- Socket.io (For real-time communication)

### **Project Deployment**

- Frontend: Netlify
- Backend: Render/Vercel
- Database: MongoDB Atlas

---

## **Core Features**

### 1. **Authentication & User Roles**

- **Client & Developer roles**: Separate user flows for clients posting jobs and developers submitting proposals.
- **JWT-based Authentication**: Secure login and registration using JWT tokens.
- **Google OAuth (Optional)**: Quick social sign-up/login with Google.

### 2. **Job Posting & Job Board**

- **Client Dashboard**: Clients can post job listings, edit, and delete them.
- **Job Categories & Filters**: Developers can filter job listings by categories, budgets, and timelines.
- **Job Detail View**: Clicking a job listing reveals detailed information like description, budget, timeline, and required skills.

### 3. **Proposal Submission & Management**

- **Developers Submit Proposals**: Developers can submit proposals to jobs with estimated timelines, prices, and a cover letter.
- **Proposal Review & Status**: Clients can review proposals, short-list developers, and accept or reject them.
- **Proposal Notification**: Developers are notified when their proposal is accepted or rejected.

### 4. **Real-Time Messaging (Socket.io)**

- **Instant Chat**: Once a proposal is accepted, clients and developers can chat in real-time to discuss project details.
- **Message Notifications**: Users receive notifications for unread messages and project updates.

### 5. **Project Dashboard & File Uploads**

- **Project Timeline**: Clients and developers can track project progress in a task-based timeline.
- **File Uploads**: Both parties can upload project-related files (designs, documents, code).
- **Project Status Updates**: Users can update the project status (In Progress, Submitted, Completed).

### 6. **Reviews & Ratings**

- **After Project Completion**: Both clients and developers can leave reviews and ratings for each other.
- **Profile Ratings**: The average rating is displayed on user profiles for transparency.

### 7. **Admin Panel (Optional)**

- **User Management**: Admin can manage clients, developers, and projects.
- **Content Moderation**: Admin can remove inappropriate content or flag problematic users.

---

## **Installation**

### **1. Clone the Repository**

```bash
git clone https://github.com/yourusername/workflowpro.git
cd workflowpro
```

### **2. Backend Setup**

Navigate to the `server/` directory.

Create a `.env` file based on `.env.example` for environment variables (MongoDB URI, JWT secret, etc.).

```bash
cd server
npm install
npm start
```

### **3. Frontend Setup**

Navigate to the `client/` directory.

Install the required dependencies.

```bash
cd client
npm install
npm run dev
```

### **4. Database Setup**

Set up MongoDB (MongoDB Atlas or local).

Ensure the `MONGO_URI` environment variable is correctly set in your `.env` file.

---

## **Usage**

- **Sign Up & Log In**: Create an account as a client or developer. You can also sign in using Google OAuth (if enabled).
- **Post Jobs**: As a client, go to the "Post a Job" section to create new job listings.
- **Submit Proposals**: As a developer, browse job listings and submit proposals to clients.
- **Chat with Clients/Developers**: Use the real-time messaging feature to communicate once a proposal is accepted.
- **Manage Projects**: Use the project dashboard to track your progress and upload deliverables.
- **Leave Reviews**: After completing a project, leave feedback for the client/developer you worked with.

---

## **Deployment**

### **Frontend**

Deploy the frontend to Vercel or Netlify for fast and seamless hosting.

### **Backend**

Deploy the backend to Heroku, Render, or Railway. Be sure to set your environment variables properly.

---

## **Future Features / Enhancements**

- **Payment Integration**: Implement Stripe for handling payments between clients and developers.
- **Job Notifications**: Real-time notifications for job posting updates.
- **Admin Dashboard**: A more feature-rich admin panel for managing users and content.

---

## **Contributing**

1. Fork the repo.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to your branch (`git push origin feature/your-feature-name`).
5. Create a pull request.

---

## **License**

Distributed under the MIT License. See `LICENSE` for more information.

---

## **Contact**

Your Name: [LinkedIn](www.linkedin.com/in/hernani-silva-webdev) | [Email](hcsilvamatos5@gmail.com)
