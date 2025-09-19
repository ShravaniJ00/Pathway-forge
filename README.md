## Project Overview
Pathway-forge is a comprehensive learning platform designed to help users navigate their educational journey in computer science and programming. The platform provides structured learning roadmaps, company-specific preparation guides, and practice questions to enhance users' skills and knowledge.

## Project Structure
The project is divided into three main components:

### 1. Frontend
A React-based user interface that provides the main learning platform for users.

- **Technology Stack**: React, React Router, Bootstrap
- **Key Features**:
  - Learning roadmaps for various topics (DSA, OOP, Web Development)
  - Company profiles with preparation guides
  - Practice questions and exercises
  - Interactive UI with responsive design

### 2. Backend
An Express.js server that handles API requests, database operations, and file uploads.

- **Technology Stack**: Node.js, Express, MongoDB, Mongoose, JWT, Multer
- **Key Features**:
  - RESTful API endpoints for CRUD operations
  - Authentication and authorization using JWT
  - File upload functionality for images
  - MongoDB integration for data persistence

### 3. Admin Panel
A separate React application built with Vite for administrative tasks.

- **Technology Stack**: React, Vite, React Router
- **Key Features**:
  - Add/edit/delete practice questions
  - Manage user accounts
  - Content management system

## Main Features

### Learning Roadmaps
The platform offers structured learning paths for various computer science topics:

- **Data Structures & Algorithms**:
  - Arrays, Strings, Linked Lists, Stacks, Queues, Trees, Graphs
  - Detailed explanations and implementation guides

- **Object-Oriented Programming**
  - Core concepts and principles
  - Implementation examples

- **Web Development**
  - Frontend and backend technologies
  - Best practices and frameworks

### Company Profiles
Detailed information about various tech companies and preparation guides:

- MasterCard, Adobe, Amazon, PhonePe, Barclays, Trilogy Innovation, Deutsche Bank, Veritas, BNY, Microsoft, Goldman Sachs
- Company-specific interview preparation materials
- Technical requirements and expectations

### Practice Questions
Interactive practice questions to test and enhance knowledge:

- Multiple-choice questions with answers
- Topic-specific exercises
- Progress tracking

## Installation and Setup

### Prerequisites
- Node.js (v14 or higher)
- MongoDB
- npm or yarn

### Frontend Setup
```bash
cd frontend
npm install
npm start
```
The frontend will be available at http://localhost:3000

### Backend Setup
```bash
cd backend
npm install
node index.js
```
The backend server will run on http://localhost:4000

### Admin Panel Setup
```bash
cd admin
npm install
npm run dev
```
The admin panel will be available at http://localhost:5173

## Database Configuration
The application uses MongoDB for data storage. The connection string is configured in the backend/index.js file.

## File Structure

```
├── admin/               # Admin panel application
│   ├── public/          # Public assets
│   └── src/             # Source code
│       ├── Components/  # React components
│       ├── Pages/       # Page components
│       └── assets/      # Static assets
├── backend/             # Backend server
│   ├── Upload/          # Uploaded files
│   └── index.js         # Main server file
└── frontend/           # Frontend application
    ├── public/          # Public assets
    └── src/             # Source code
        ├── Components/  # React components
        ├── Pages/       # Page components
        └── assets/      # Static assets
```

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## License
This project is licensed under the ISC License.

## Contact
For any questions or suggestions, please open an issue in the repository.
