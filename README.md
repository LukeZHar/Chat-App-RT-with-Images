# Chatsworth - Real-Time Chat Application with Image Sharing

A modern, feature-rich real-time chat application built with React and Node.js, featuring instant messaging, image sharing, multiple themes, and user authentication.

## 🌟 Features

- **Real-time messaging** powered by Socket.IO
- **Image sharing** with Cloudinary integration
- **User authentication** (signup/login/logout)
- **Profile management** with avatar uploads
- **Online status indicators**
- **Multiple theme support** (30+ beautiful themes)
- **Responsive design** that works on all devices
- **Message history** persistence
- **Secure authentication** with JWT tokens

## 🚀 Live Demo

**Live App:** https://chat-app-rt-with-images.onrender.com

**Test Account:**

- Email: `luke@email.com`
- Password: `123456`

## 🔗 Links

- **GitHub Repository:** https://github.com/LukeZHar/Chat-App-RT-with-Images
- **YouTube Demo:** https://youtu.be/Si60nmq6fac?si=kVEY9sUkh92MA6yN

## 🛠️ Tech Stack

### Frontend

- **React 19** - Modern UI library
- **Vite** - Fast build tool and dev server
- **Tailwind CSS** - Utility-first CSS framework
- **DaisyUI** - Beautiful component library
- **Socket.IO Client** - Real-time communication
- **Zustand** - Lightweight state management
- **React Router DOM** - Client-side routing
- **Axios** - HTTP client
- **React Hot Toast** - Elegant notifications
- **Lucide React** - Beautiful icons

### Backend

- **Node.js** - JavaScript runtime
- **Express.js** - Web application framework
- **Socket.IO** - Real-time bidirectional communication
- **MongoDB** with **Mongoose** - Database and ODM
- **JWT** - Authentication tokens
- **bcryptjs** - Password hashing
- **Cloudinary** - Image storage and optimization
- **CORS** - Cross-origin resource sharing
- **Cookie Parser** - Cookie handling

## ⚡ Getting Started

### Prerequisites

- Node.js (v18 or higher)
- MongoDB database
- Cloudinary account (for image uploads)

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/LukeZHar/Chat-App-RT-with-Images.git
   cd Chat-App-RT-with-Images
   ```

2. **Install dependencies**

   ```bash
   npm run build
   ```

3. **Environment Variables**

   Create a `.env` file in the `backend` directory:

   ```env
   PORT=5000
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   NODE_ENV=development

   CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
   CLOUDINARY_API_KEY=your_cloudinary_api_key
   CLOUDINARY_API_SECRET=your_cloudinary_api_secret
   ```

4. **Run the application**

   **Development mode:**

   ```bash
   # Start backend (from backend directory)
   npm run dev

   # Start frontend (from frontend directory)
   npm run dev
   ```

   **Production build:**

   ```bash
   # From root directory
   npm run build
   npm run start
   ```

## 📱 Usage

1. **Sign up** for a new account or **log in** with existing credentials
2. **Update your profile** with a custom avatar
3. **Select a user** from the sidebar to start chatting
4. **Send text messages** and **share images** in real-time
5. **Customize your experience** with 30+ available themes
6. **See online status** of other users instantly

## 🎨 Features in Detail

### Real-Time Communication

- Instant message delivery using Socket.IO
- Live online/offline status updates
- Real-time typing indicators
- Message read receipts

### Image Sharing

- Drag & drop image uploads
- Image compression and optimization
- Preview before sending
- Support for multiple image formats

### Theme Customization

- 30+ professionally designed themes
- Dark and light mode options
- Real-time theme preview
- Persistent theme selection

### User Management

- Secure user registration and authentication
- Profile customization with avatar uploads
- User search and discovery
- Online presence indicators

## 📂 Project Structure

```
├── backend/
│   ├── src/
│   │   ├── controllers/     # Route handlers
│   │   ├── lib/            # Utilities (DB, Socket, Cloudinary)
│   │   ├── middleware/     # Auth middleware
│   │   ├── models/         # Database schemas
│   │   ├── routes/         # API routes
│   │   └── index.js        # App entry point
│   └── package.json
├── frontend/
│   ├── src/
│   │   ├── components/     # Reusable UI components
│   │   ├── pages/         # Route components
│   │   ├── store/         # State management
│   │   ├── lib/           # Utilities and configs
│   │   └── App.jsx        # Main app component
│   └── package.json
└── package.json           # Root package.json
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🙏 Acknowledgments

- Socket.IO for real-time communication
- Cloudinary for image management
- DaisyUI for beautiful UI components
- MongoDB for robust data storage
- Render for hosting services
- Udemy course - 100 Hours Web Development Bootcamp - Build 23 React Projects


---

⭐ Star this repository if you found it helpful!
