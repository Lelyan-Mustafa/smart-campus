
# Smart Campus

Smart Campus is a mobile application developed as a graduation project to simplify university attendance and improve access to campus services. The application provides dedicated experiences for students and instructors, making attendance management and lecture session tracking more organized and accessible.

## Project Overview

The application supports live and scheduled lecture sessions, allowing instructors to manage attendance while students discover and join available sessions.

The project was developed using a mobile application architecture with a backend API and Firebase integration.

## Key Features

### Student Features
- Create an account and sign in.
- Browse and discover available lecture sessions.
- Find sessions through nearby location discovery or a session key.
- Join live attendance sessions using a session PIN.
- View attendance history.
- Manage profile information.

### Instructor Features
- Create live or scheduled lecture sessions.
- Configure session duration and recurring days.
- Set session discovery options, including nearby discovery and search keys.
- Monitor live attendance and student check-ins.
- View lecture history and attendance details.
- Export attendance reports in CSV format.

## Technologies Used

### Mobile Application
- React Native
- Expo
- TypeScript
- Expo Router
- NativeWind

### Backend
- Node.js
- Express.js
- TypeScript
- RESTful API

### Database & Authentication
- Firebase Authentication
- Cloud Firestore
- Firebase Admin SDK

### Tools
- Git
- Postman

## Project Structure

```text
smart-campus/
├── apps/
│   ├── mobile/       # Mobile application
│   └── api/          # Backend API
├── packages/
│   ├── types/        # Shared TypeScript types
│   └── validation/   # Shared validation schemas
├── docs/              # Project documentation
└── package.json       # Workspace configuration
```

## Getting Started

### Prerequisites
- Node.js
- npm
- Firebase project configuration

### Installation

Clone the repository:

```bash
git clone https://github.com/Lelyan-Mustafa/smart-campus.git
cd smart-campus
```

Install dependencies:

```bash
npm install
```

Configure the required environment variables for the mobile application and backend using the provided `.env.example` files.

Start the development environment:

```bash
npm run dev
```

Additional Firebase configuration and permissions are required for the application to work correctly.

## Graduation Project

This project was developed as a team graduation project as part of the Software Engineering program.

It demonstrates the application of mobile development, backend integration, database management, authentication, and software development practices in a university attendance management solution.

