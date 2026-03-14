# 🏫 School Management System

[![GitHub stars](https://img.shields.io/github/stars/Arison99/School-Management-System?style=for-the-badge&logo=github)](https://github.com/Arison99/School-Management-System/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/Arison99/School-Management-System?style=for-the-badge&logo=github)](https://github.com/Arison99/School-Management-System/network)
[![GitHub commits](https://img.shields.io/github/commit-activity/m/Arison99/School-Management-System?style=for-the-badge&logo=github)](https://github.com/Arison99/School-Management-System/commits)
[![GitHub last commit](https://img.shields.io/github/last-commit/Arison99/School-Management-System?style=for-the-badge&logo=github)](https://github.com/Arison99/School-Management-System/commits)

[![Node.js](https://img.shields.io/badge/Node.js-20.x-339933?style=flat-square&logo=node.js)](https://nodejs.org/)
[![React](https://img.shields.io/badge/React-18.x-61DAFB?style=flat-square&logo=react)](https://reactjs.org/)
[![Express](https://img.shields.io/badge/Express-4.x-000000?style=flat-square&logo=express)](https://expressjs.com/)
[![SQLite](https://img.shields.io/badge/SQLite-3.x-003B57?style=flat-square&logo=sqlite)](https://sqlite.org/)
[![Sequelize](https://img.shields.io/badge/Sequelize-6.x-52B0E7?style=flat-square&logo=sequelize)](https://sequelize.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.x-06B6D4?style=flat-square&logo=tailwindcss)](https://tailwindcss.com/)

A modern, comprehensive web-based School Management System built with React.js and Node.js, designed to streamline educational institution operations with a focus on usability, scalability, and security.

## 🌟 Key Highlights

- **🎯 User-Centric Design** - Intuitive interface for administrators, teachers, and staff
- **🔒 Secure Authentication** - JWT-based authentication with role-based access control
- **📱 Responsive Design** - Works seamlessly across desktop, tablet, and mobile devices
- **⚡ Real-time Operations** - Fast and efficient data management
- **🔧 Modular Architecture** - Easily extensible and maintainable codebase

## 📋 Table of Contents

- [Features](#-features)
- [Technology Stack](#-technology-stack)
- [Quick Start](#-quick-start)
- [Documentation](#-documentation)
- [System Architecture](#-system-architecture)
- [Project Structure](#-project-structure)
- [API Reference](#-api-reference)
- [Contributing](#-contributing)
- [Security](#-security)
- [License](#-license)
- [Support](#-support)

## ✨ Features

### 🏢 Institution Management
- **School Profile Setup**: Complete school information management with document uploads
- **Multi-institution Support**: Designed to handle multiple educational institutions
- **Branding & Customization**: Upload school logos and customize profile information
- **Regulatory Compliance**: Track registration numbers, licenses, and TIN information

### 👥 User Management
- **Secure Authentication**: JWT-based login system with encrypted passwords
- **Role-based Access**: Different permission levels for administrators and staff
- **User Profiles**: Comprehensive user information management
- **Session Management**: Secure session handling with automatic logout

### 🎓 Academic Management
- **Class/Course Management**: Create and manage classes across different academic years
- **Student Enrollment**: Comprehensive student information system
- **Student Records**: Detailed student profiles with photos and family information
- **Bulk Operations**: Efficient handling of multiple student records

### 📊 Dashboard & Analytics
- **Real-time Statistics**: Live dashboard with key metrics
- **Visual Analytics**: Charts and graphs for data visualization
- **Report Generation**: Comprehensive reporting system
- **Data Export**: Export data in various formats

### 🔍 Search & Filter
- **Advanced Search**: Search students, classes, and records
- **Filter Options**: Multiple filtering criteria for easy data retrieval
- **Quick Access**: Fast navigation to frequently used features

## 🛠 Technology Stack

### Frontend
- **React 18.x** - Modern UI library with hooks and functional components
- **Vite** - Fast build tool and development server
- **Tailwind CSS** - Utility-first CSS framework
- **Axios** - HTTP client for API communications
- **React Router** - Client-side routing
- **Lucide React** - Modern icon library

### Backend
- **Node.js 20.x** - JavaScript runtime environment
- **Express.js 4.x** - Web application framework
- **Sequelize 6.x** - Promise-based ORM for SQL databases
- **SQLite 3.x** - Lightweight, file-based database
- **JWT** - JSON Web Tokens for authentication
- **Bcrypt** - Password hashing library
- **Multer** - File upload middleware

### Development Tools
- **ESLint** - Code linting and style enforcement
- **Nodemon** - Auto-restart development server
- **PostCSS** - CSS post-processing
- **Git** - Version control system

## 🚀 Quick Start

### Prerequisites

Ensure you have the following installed:
- [Node.js](https://nodejs.org/) (v18.0.0 or higher)
- [npm](https://www.npmjs.com/) (v8.0.0 or higher) or [yarn](https://yarnpkg.com/)
- [Git](https://git-scm.com/)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Arison99/School-Management-System.git
   cd School-Management-System
   ```

2. **Install Backend Dependencies**
   ```bash
   cd backend
   npm install
   ```

3. **Install Frontend Dependencies**
   ```bash
   cd ../frontend
   npm install
   ```

4. **Environment Setup**
   ```bash
   cd ../backend
   cp .env.example .env
   # Edit .env file with your configuration
   ```

5. **Start the Application**
   
   **Backend (Terminal 1):**
   ```bash
   cd backend
   npm run dev
   ```
   
   **Frontend (Terminal 2):**
   ```bash
   cd frontend
   npm run dev
   ```

6. **Access the Application**
   - Frontend: http://localhost:5173
   - Backend API: http://localhost:6001

### Default Access

On first run, create an account through the signup process. The system will guide you through school profile setup.

## 📚 Documentation

### Core Documentation
- [📖 **User Guide**](docs/USER_GUIDE.md) - Complete user manual with screenshots
- [🔧 **Installation Guide**](docs/INSTALLATION.md) - Detailed setup instructions
- [⚙️ **Configuration Guide**](docs/CONFIGURATION.md) - Environment and system configuration
- [🚀 **Deployment Guide**](docs/DEPLOYMENT.md) - Production deployment instructions

### Development Documentation
- [🏗️ **Architecture Guide**](docs/ARCHITECTURE.md) - System design and architecture overview
- [📡 **API Documentation**](docs/API.md) - Complete API reference and examples
- [🔒 **Security Guide**](docs/SECURITY.md) - Security implementation and best practices
- [🧪 **Testing Guide**](docs/TESTING.md) - Testing strategies and implementation

### Additional Resources
- [❓ **FAQ**](docs/FAQ.md) - Frequently asked questions and solutions
- [🐛 **Troubleshooting**](docs/TROUBLESHOOTING.md) - Common issues and fixes
- [📝 **Changelog**](CHANGELOG.md) - Version history and updates
- [🤝 **Contributing Guidelines**](CONTRIBUTING.md) - How to contribute to the project

## 🏗 System Architecture

The School Management System follows a **layered architecture** pattern:

```
┌─────────────────────────────────────────────────────────────┐
│                    Frontend (React)                         │
│  ┌─────────────┐ ┌─────────────┐ ┌─────────────────────────┐ │
│  │   Pages     │ │ Components  │ │      API Services       │ │
│  │             │ │             │ │                         │ │
│  └─────────────┘ └─────────────┘ └─────────────────────────┘ │
└─────────────────────────────────────────────────────────────┘
                               │
                          HTTP/HTTPS
                               │
┌─────────────────────────────────────────────────────────────┐
│                     Backend (Node.js)                      │
│  ┌─────────────┐ ┌─────────────┐ ┌─────────────────────────┐ │
│  │   Routes    │ │ Controllers │ │      Middleware         │ │
│  └─────────────┘ └─────────────┘ └─────────────────────────┘ │
│  ┌─────────────┐ ┌─────────────┐ ┌─────────────────────────┐ │
│  │  Services   │ │ Repositories│ │       Models            │ │
│  └─────────────┘ └─────────────┘ └─────────────────────────┘ │
└─────────────────────────────────────────────────────────────┘
                               │
                          Sequelize ORM
                               │
┌─────────────────────────────────────────────────────────────┐
│                    Database (SQLite)                       │
│  ┌─────────────┐ ┌─────────────┐ ┌─────────────────────────┐ │
│  │    Users    │ │   Schools   │ │       Classes           │ │
│  └─────────────┘ └─────────────┘ └─────────────────────────┘ │
│  ┌─────────────┐                                           │
│  │  Students   │                                           │
│  └─────────────┘                                           │
└─────────────────────────────────────────────────────────────┘
```

### Key Components

- **Frontend Layer**: React-based SPA with responsive design
- **API Layer**: RESTful Express.js server with JWT authentication
- **Business Logic**: Service layer handling core operations
- **Data Access**: Repository pattern with Sequelize ORM
- **Database**: SQLite for development, easily scalable to PostgreSQL/MySQL

## 📁 Project Structure

```
School-Management-System/
├── 📁 backend/                    # Backend server
│   ├── 📁 src/
│   │   ├── 📁 config/            # Database and app configuration
│   │   ├── 📁 controllers/       # Request handlers
│   │   ├── 📁 middleware/        # Custom middleware
│   │   ├── 📁 models/           # Database models (Sequelize)
│   │   ├── 📁 repositories/     # Data access layer
│   │   ├── 📁 routes/           # API route definitions
│   │   └── 📁 services/         # Business logic layer
│   ├── 📁 uploads/              # File upload storage
│   ├── 📄 server.js             # Server entry point
│   ├── 📄 package.json          # Backend dependencies
│   └── 📄 .env                  # Environment variables
├── 📁 frontend/                  # Frontend application
│   ├── 📁 src/
│   │   ├── 📁 api/              # API service clients
│   │   ├── 📁 assets/           # Static assets
│   │   ├── 📁 Pages/            # React page components
│   │   ├── 📄 App.jsx           # Main App component
│   │   └── 📄 main.jsx          # Application entry point
│   ├── 📄 index.html            # HTML template
│   ├── 📄 package.json          # Frontend dependencies
│   └── 📄 vite.config.js        # Vite configuration
├── 📁 docs/                     # Documentation files
├── 📄 README.md                 # This file
├── 📄 CONTRIBUTING.md           # Contribution guidelines
├── 📄 LICENSE                   # License information
└── 📄 CHANGELOG.md              # Version history
```

## 🔗 API Reference

### Quick API Overview

Base URL: `http://localhost:6001/api`

#### Authentication Endpoints
- `POST /signup` - User registration
- `POST /login` - User authentication

#### School Management
- `GET /schools/my-school` - Get current user's school
- `POST /schools` - Create school profile
- `PUT /schools` - Update school information
- `GET /schools/stats` - Get school statistics

#### Class Management
- `GET /classes` - Get all classes
- `POST /classes` - Create new class
- `PUT /classes/:id` - Update class
- `DELETE /classes/:id` - Delete class

#### Student Management
- `POST /classes/:id/students` - Add student to class
- `PUT /classes/:classId/students/:studentId` - Update student
- `DELETE /classes/:classId/students/:studentId` - Remove student
- `GET /students/search` - Search students

For detailed API documentation with examples, see [API Documentation](docs/API.md).

## 🤝 Contributing

We welcome contributions from the community! Please read our [Contributing Guidelines](CONTRIBUTING.md) for details on:

- 📝 How to submit issues
- 🔧 Setting up development environment  
- 📋 Code style and standards
- 🧪 Testing requirements
- 📤 Pull request process

### Quick Contribution Steps

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 🔒 Security

Security is a top priority. This system implements:

- **JWT Authentication** - Secure token-based authentication
- **Password Encryption** - Bcrypt hashing for password security
- **Input Validation** - Comprehensive data validation
- **SQL Injection Prevention** - Parameterized queries via Sequelize
- **File Upload Security** - Restricted file types and size limits

For detailed security information, see [Security Guide](docs/SECURITY.md).


## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 💬 Support

### Getting Help

- 📖 Check the [User Guide](docs/USER_GUIDE.md) for common tasks
- ❓ Read the [FAQ](docs/FAQ.md) for frequently asked questions
- 🐛 Review [Troubleshooting](docs/TROUBLESHOOTING.md) for common issues
- 💡 Search [existing issues](https://github.com/Arison99/School-Management-System/issues)

### Community

- 🐛 **Bug Reports**: [GitHub Issues](https://github.com/Arison99/School-Management-System/issues)
- 💡 **Feature Requests**: [GitHub Discussions](https://github.com/Arison99/School-Management-System/discussions)

### Project Maintainers

- **Lead Developer**: [Arison99](https://github.com/Arison99)
- **Contributors**: [View all contributors](https://github.com/Arison99/School-Management-System/contributors)

---

<div align="center">

**⭐ Star this repository if you find it helpful!**

[🏠 Website](https://schoolms.com) | [📖 Documentation](docs/) | [🐛 Report Bug](https://github.com/Arison99/School-Management-System/issues) | [💡 Request Feature](https://github.com/mwakidenis/School-Management-System/issues)

<!-- GitAds-Verify: A3898VA57LNIZEPDEGTSOVBB3TUDWA6H -->

Made with ❤️ by the mwakidenis

</div>

## GitAds Sponsored
[![Sponsored by GitAds](https://gitads.dev/v1/ad-serve?source=arison99/school-management-system@github)](https://gitads.dev/v1/ad-track?source=arison99/school-management-system@github)



