# 🎥 Video Meet (V2) - WEB Video Conferencing App

A modern, dark-mode video conferencing application built with Node.js, WebRTC, and Socket.io. Features a beautiful iOS-inspired dark theme with Google Meet/Zoom-style controls.

![Video Meet](https://cdn-icons-png.flaticon.com/512/15047/15047720.png)

## ✨ Features

### 🎨 Modern Dark Mode Design
- **Complete Dark Theme**: Pure black background with dark gray elements
- **iOS-Inspired**: Apple system fonts and modern design patterns
- **Glassmorphism Effects**: Backdrop blur and subtle shadows
- **Responsive Design**: Optimized for desktop and mobile devices

### 🎥 Video Call Features
- **Real-time Video/Audio**: WebRTC-powered video conferencing
- **Screen Sharing**: Share your screen with participants
- **Recording**: Record video calls or screen sharing sessions
- **Picture-in-Picture**: Click local video for PiP mode
- **Multiple Participants**: Support for multiple users in a room

### 🎛️ Control Interface
- **Centered Control Bar**: Modern pill-shaped control bar at bottom
- **Custom Icons**: Beautiful Flaticon icons for all controls
- **Smart Button States**: Visual feedback for mute, video off, recording
- **Mobile Optimized**: Touch-friendly controls for mobile devices

### 💬 Chat System
- **Real-time Messaging**: Live chat during video calls
- **Chat Notifications**: "New" badge for unread messages
- **Easy Close**: Close button for mobile-friendly chat dismissal
- **Dark Theme Chat**: Consistent dark mode chat interface

### 🔧 Technical Features
- **WebRTC**: Peer-to-peer video/audio streaming
- **Socket.io**: Real-time communication
- **Node.js Backend**: Scalable server architecture
- **Cross-platform**: Works on all modern browsers

## 🚀 Quick Start

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn
- Modern web browser with WebRTC support

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd Video-Call-App-NodeJS
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the server**
   ```bash
   npm start
   ```

4. **Open in browser**
   ```
   http://localhost:3000
   ```

## 📱 How to Use

### Creating a Room
1. Enter a room name and your name
2. Click "Create Room"
3. Share the generated room link with participants
4. Click the link to join the room

### Joining a Room
1. Enter your name
2. Click "Join Room"
3. Allow camera and microphone permissions
4. Start your video call!

### Control Buttons
- **🎤 Microphone**: Toggle audio on/off
- **📹 Camera**: Toggle video on/off
- **🖥️ Screen Share**: Share your screen
- **🔴 Record**: Start/stop recording
- **💬 Chat**: Open/close chat panel
- **📞 End Call**: Leave the room

### Chat Features
- Click the chat button to open the chat panel
- Type messages and press Enter or click Send
- Click the × button to close chat
- Chat notifications appear when new messages arrive

## 🎨 Design Features

### Dark Mode Color Palette
- **Primary Blue**: #0A84FF (accent color)
- **Success Green**: #30D158
- **Error Red**: #FF453A
- **Warning Orange**: #FF9F0A
- **Background**: #000000 (pure black)
- **Card Background**: #1C1C1E
- **Secondary Background**: #2C2C2E

### Custom Icons
All control buttons use high-quality Flaticon icons:
- Microphone On/Off icons
- Camera On/Off icons
- Screen Share icon
- Recording icon
- Chat icon
- End Call icon

### Responsive Design
- **Desktop**: Full-featured interface with side-by-side layout
- **Mobile**: Optimized touch controls and compact design
- **Tablet**: Adaptive layout for medium screens

## 🛠️ Technical Stack

### Frontend
- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS Grid and Flexbox
- **JavaScript (ES6+)**: Modern JavaScript features
- **WebRTC**: Real-time video/audio communication
- **Socket.io Client**: Real-time messaging

### Backend
- **Node.js**: Server runtime
- **Express.js**: Web framework
- **Socket.io**: Real-time communication
- **WebRTC**: Peer-to-peer connections

### Dependencies
```json
{
  "express": "^4.21.0",
  "serve-favicon": "^2.5.0",
  "socket.io": "^4.7.5"
}
```

## 📁 Project Structure

```
Video-Call-App-NodeJS/
├── src/
│   ├── app.js                 # Main server file
│   ├── index.html             # Main HTML file
│   ├── favicon.png            # App icon
│   ├── assets/
│   │   ├── css/
│   │   │   └── app.css        # Main stylesheet
│   │   └── js/
│   │       ├── rtc.js         # WebRTC functionality
│   │       ├── events.js      # Event handlers
│   │       ├── helpers.js     # Utility functions
│   │       └── autolink.js    # Auto-linking utility
│   └── ws/
│       └── stream.js          # Socket.io stream handling
├── package.json               # Dependencies and scripts
├── package-lock.json          # Locked dependencies
└── README.md                  # This file
```

## 🔧 Development

### Running in Development Mode
```bash
npm run watch
```
This will start the server with nodemon for automatic restarts on file changes.

### Building for Production
```bash
npm start
```

## 🌐 Browser Support

- **Chrome**: 60+
- **Firefox**: 55+
- **Safari**: 11+
- **Edge**: 79+

## 📱 Mobile Support

- **iOS Safari**: 11+
- **Chrome Mobile**: 60+
- **Firefox Mobile**: 55+
- **Samsung Internet**: 7+

## 🔒 Security Features

- **HTTPS Recommended**: Use HTTPS in production
- **WebRTC Security**: Built-in encryption for video/audio
- **Input Sanitization**: XSS protection for chat messages
- **Session Management**: Secure room access

## 🚀 Deployment

### Local Development
```bash
npm start
```

### Production Deployment
1. Set up a Node.js server
2. Install dependencies: `npm install --production`
3. Start the server: `npm start`
4. Configure reverse proxy (nginx/Apache) if needed
5. Set up SSL certificate for HTTPS

### Environment Variables
- `PORT`: Server port (default: 3000)
- `NODE_ENV`: Environment (development/production)

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is licensed under the ISC License.

## 🙏 Acknowledgments

- **Flaticon**: For the beautiful custom icons
- **FontAwesome**: For additional UI icons
- **WebRTC**: For real-time communication technology
- **Socket.io**: For real-time messaging

## 📞 Support

For support and questions:
- Create an issue on GitHub
- Check the documentation
- Review the code comments

---

**Made with ❤️ for modern video conferencing**

*Video Meet - Where dark mode meets video calls* 