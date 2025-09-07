# 💬 iChat - Real-time Chat Application

A simple real-time chat web application built with Socket.IO.

## ✨ Features

- 💨 Real-time message exchange
- ⌨️ "Typing..." indicator
- 👥 Connected users counter
- 🔊 Sound notifications
- 📱 Responsive design

## 🛠️ Technologies

- 🟢 Node.js
- ⚡ Express.js
- 🔗 Socket.IO
- 🌐 HTML/CSS/JavaScript
- ⏰ Moment.js




## 📥 Installation

**1. Clone the repository:**
```
git clone https://github.com/metisssi/websokcet.git
cd websockets
```

**2. Install dependencies:**
```
npm install
```

**3. Start the server:**
```
npm run dev
```

**4. Open your browser:**
```
http://localhost:4000
```

## 📁 Project Structure

```
websockets/
├── app.js              # 🖥️ Server logic
├── package.json        # 📦 Dependencies
├── public/
│   ├── index.html      # 🏠 Main page
│   ├── main.js         # 💻 Client-side logic
│   ├── style.css       # 🎨 Styles
│   └── message-tone.mp3 # 🔔 Notification sound
└── README.md           # 📖 Documentation
```

## 🚀 Usage

### Testing with Multiple Users

1. **Open multiple browser windows/tabs** pointing to `http://localhost:4000` to simulate different users
   
  <img width="1899" height="1029" alt="image" src="https://github.com/user-attachments/assets/cd6f3862-1d67-4f7c-bf05-c56797a3a94e" /> 

2. **Check the server console** - you'll see unique client IDs for each connection:
   
   <img width="155" height="47" alt="Server console showing client IDs" src="https://github.com/user-attachments/assets/e74461ca-9f1e-48e4-b0c3-9d8a8edef7fc" />

### Basic Chat Features

3. **Change your username** from "anonymous" to something unique:
   
   <img width="142" height="49" alt="Username input field" src="https://github.com/user-attachments/assets/69a4ab49-e49b-418d-a644-3d9145ea360a" />

4. **Typing indicators** - When you focus on the message input, other users see a typing indicator:
   
   <img width="1898" height="984" alt="Typing indicator shown to other users" src="https://github.com/user-attachments/assets/92ae2392-27e7-4f50-8081-f535a54f38cd" />

5. **Real-time typing feedback** - As you type, the indicator updates in real-time:
   
   <img width="1918" height="986" alt="Updated typing indicator while typing" src="https://github.com/user-attachments/assets/5b315dad-da16-4b43-8b10-268b0262c91a" />

6. **Multiple users typing** - Each user can see when others are typing:
   
   <img width="1895" height="941" alt="Multiple users showing typing indicators" src="https://github.com/user-attachments/assets/19690407-3255-4eb5-b5b7-27af90254f9b" />
   
   <img width="1919" height="955" alt="Another view of typing indicators" src="https://github.com/user-attachments/assets/9a012288-21ec-42d7-a592-831cd737caab" />

7. **Typing indicator disappears** when you leave the input field:
   
   <img width="1916" height="974" alt="No typing indicator when input loses focus" src="https://github.com/user-attachments/assets/91bf43f1-8da4-46fc-b1dd-eb646dfe6a6a" />

### Sending Messages

8. **Send a message** by typing and pressing Enter or clicking Send:
   
   <img width="1911" height="980" alt="Message sent and displayed in chat" src="https://github.com/user-attachments/assets/9154e1b1-ca1f-41ad-804b-4e1f9736d679" />

### User Counter

9. **Connected users counter** updates automatically as users join/leave:
   
   <img width="168" height="39" alt="Total clients counter showing 2 users" src="https://github.com/user-attachments/assets/94623223-9710-45b3-92a3-1cc76edfd819" />

10. **Adding more users** - Open another browser window to see the counter increment:
    
    <img width="1034" height="951" alt="Counter showing 3 total clients" src="https://github.com/user-attachments/assets/57a8d515-8330-4d0a-a8e8-49230bdac31a" />

### Key Features Demonstrated

- ✅ **Real-time messaging** between multiple users
- ✅ **Live typing indicators** with user names
- ✅ **Automatic user counting** and connection tracking
- ✅ **Sound notifications** for new messages
- ✅ **Responsive design** working across browser windows




 
 

   



## ⚙️ How it Works

- **🖥️ Server**: Express.js serves static files and handles Socket.IO connections
- **⚡ Real-time**: Socket.IO enables instant messaging between clients
- **👥 User Tracking**: Server maintains connected socket IDs
- **⌨️ Typing Indicators**: Broadcasts typing status to other users
- **🔊 Sound Alerts**: Plays audio notifications for new messages

## 📜 Scripts

- `npm start` - 🚀 Run in production
- `npm run dev` - 🔧 Run with nodemon for development

## 🌐 Browser Support

Works in all modern browsers that support WebSocket connections.

## 📄 License

ISC
