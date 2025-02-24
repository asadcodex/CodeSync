# CodeSync - Modern Video Collaboration Platform

![CodeSync Banner](/public/01.png)

## 🚀 Overview

CodeSync is a comprehensive video collaboration platform built with cutting-edge technologies to provide seamless communication experiences. This application offers robust video calls, screen sharing, recording capabilities, and intuitive user management—all wrapped in a sleek, responsive interface.

Developed by Asad Raza, CodeSync represents the next generation of remote collaboration tools, designed with performance and user experience at its core.

## ✨ Features

- **Real-time Video Conferencing** - Crystal-clear video calls with support for multiple participants
- **Interactive Screen Sharing** - Share your entire screen or specific application windows
- **Screen Recording** - Capture important meetings with high-quality recording capabilities
- **Secure Authentication** - Robust user authentication and authorization powered by Clerk
- **Responsive Design** - Optimized experience across all devices and screen sizes
- **Real-time Data Synchronization** - Powered by Convex for instant updates and collaboration

## 🛠️ Tech Stack

CodeSync leverages a modern, powerful technology stack:

- **Frontend Framework**: Next.js with TypeScript
- **Real-time Communication**: Stream SDK
- **Database & Backend**: Convex
- **Authentication**: Clerk
- **Styling**: Tailwind CSS with Shadcn UI components
- **Architecture**: 
  - Server Components for improved performance
  - Client Components for interactive elements
  - Server Actions for secure, server-side operations
  - Dynamic and static routing for optimized page loading

### Setup .env file

```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=
NEXT_PUBLIC_STREAM_API_KEY=
STREAM_SECRET_KEY=
```

## 🔄 Server Components vs Client Components

CodeSync strategically uses both Server and Client Components:

- **Server Components** handle data fetching, authentication, and rendering static content for improved performance
- **Client Components** manage interactive elements like video calls and screen sharing

## 💡 Implementation Details

### Video Calls

Video calls are implemented using Stream's SDK, allowing for:
- Multi-participant video conferencing
- Dynamic video quality adjustment based on network conditions
- Audio muting and video toggling

### Screen Sharing

The screen sharing feature leverages browser APIs and Stream's SDK to:
- Share entire screens or specific application windows
- Maintain high-quality visual fidelity
- Support annotations and highlighting

### Authentication

User authentication is handled by Clerk, providing:
- Multiple sign-in methods (email, social providers)
- JWT-based session management
- Role-based authorization

### Built with ❤️ by Asad Raza