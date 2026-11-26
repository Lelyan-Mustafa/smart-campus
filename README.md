
# Smart Campus

Smart Campus is a mobile application designed to simplify university attendance management and improve access to campus services. It provides student and instructor interfaces for managing lecture sessions, recording attendance, and reviewing attendance history.

## Overview

The application supports live and scheduled lecture sessions. Instructors can create and manage sessions, while students can discover available sessions and check in using a session PIN.

The project includes a mobile application, a backend API, and Firebase integration.

## Features

### Student
- Student registration and login
- Browse available lecture sessions
- Discover sessions using nearby search or a session key
- Join attendance sessions using a PIN
- View attendance history
- Manage profile information

### Instructor
- Create live and scheduled lecture sessions
- Configure session duration and recurring days
- Set session discovery options
- Monitor live attendance and student check-ins
- View session history and attendance details
- Export attendance reports as CSV files

## Technologies

### Mobile Application
- React Native
- Expo
- TypeScript
- Expo Router
- NativeWind

### Backend API
- Node.js
- Express.js
- TypeScript
- RESTful APIs

### Firebase
- Firebase Authentication
- Cloud Firestore
- Firebase Admin SDK

### Additional Tools & Libraries
- Zod for validation
- Git
- Postman

## Project Structure

```text
smart-campus/
├── apps/
│   ├── mobile/       # React Native mobile app
│   └── api/          # Express backend API
├── packages/
│   ├── types/        # Shared TypeScript types
│   └── validation/   # Shared validation schemas
├── docs/              # Project documentation
├── package.json
└── turbo.json
```

## Application Screens

The mobile application includes screens and flows for:

- Login and registration
- Student home and attendance history
- Instructor dashboard and history
- Available sessions
- Session information
- Create lecture
- Live attendance
- User profiles

## Development Setup

### Requirements
- Node.js
- npm
- Firebase project configuration

### Install dependencies

```bash
npm install
```

### Start the development environment

```bash
npm run dev
```

The project uses npm workspaces and Turborepo to manage the mobile application, backend API, and shared packages.

Firebase configuration and required environment variables must be set up before running the application.

## Project Purpose

Smart Campus provides a digital solution for organizing university lecture attendance and session management, helping students and instructors access attendance-related services through a mobile application.
