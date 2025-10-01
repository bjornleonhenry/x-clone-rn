# X Clone (React Native) - Mobile Social Platform

A comprehensive React Native mobile application that replicates the core features of X (formerly Twitter), including authentication, posting, interactions, and real-time messaging.

## Features

- 🔐 **Secure Authentication** - Login and user management
- 🏠 **Home Feed** - Post text and images from gallery/camera
- ❤️ **Interactions** - Like, comment, and share functionality
- 🔔 **Notifications** - Real-time notification system
- 📬 **Direct Messages** - Private messaging with chat history
- 👤 **User Profiles** - Editable profile management
- 🔎 **Search & Discovery** - Find users and trending content
- 📱 **Cross-Platform** - Works on Android and iOS

## Tech Stack

- **React Native** - Cross-platform mobile framework
- **Expo** - Development platform and build tools
- **TypeScript** - Type-safe development
- **Express.js** - Backend API server
- **MongoDB** - Database for user data and posts
- **Socket.io** - Real-time messaging
- **Image Upload** - File storage and management

---

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn
- MongoDB database
- Expo CLI (for mobile development)

### Environment Variables

#### Backend (.env)
```env
PORT=5001
NODE_ENV=development
MONGO_URI=your_mongodb_connection_uri
# Add other API keys for services as needed
```

#### Mobile (.env)
```env
EXPO_PUBLIC_API_URL=http://localhost:5001
# Add other public environment variables
```

### Installation

1. **Backend Setup:**
```bash
cd backend
npm install
npm run dev
```

2. **Mobile Setup:**
```bash
cd mobile
npm install
npx expo start
```

3. Access the application:
   - Backend API: `http://localhost:5001`
   - Mobile app: Scan QR code from Expo or run on device/emulator

## Building for Production

### Backend
```bash
cd backend
npm run build
```

### Mobile
```bash
cd mobile
npx expo build
```

## Deployment

- **Backend**: Deploy to VPS, Railway, Render, or similar Node.js hosting
- **Mobile**: Build and submit to App Store/Google Play Store
- **Database**: MongoDB Atlas or self-hosted MongoDB instance
