

# AvatarLab - Interactive Avatar Creation Platform

🚀 **Transform static images into dynamic talking avatars with cutting-edge technology**

## ✨ Features

- **🎭 Avatar Creation** - Upload any image and bring it to life
- **🎤 Voice Generation** - Convert text to natural speech
- **🎬 Video Production** - Generate synchronized talking avatar videos
- **👤 User Management** - Secure accounts with generation history
- **📱 Modern UI** - Sleek, responsive React interface
- **⚡ Real-time Processing** - Fast on-demand avatar generation

## 🏗️ Architecture

```
avatarLab/
├── frontend/      # React web application
├── backend/       # Flask REST API
├── static/        # Generated media files
└── README.md
```

## 🛠️ Tech Stack

### Frontend
- **React 18** - Modern component-based UI
- **React Router** - Smooth navigation
- **Axios** - API communication
- **React Dropzone** - File uploads
- **React Hot Toast** - User notifications

### Backend
- **Flask** - Python web framework
- **MongoDB** - NoSQL database
- **JWT** - Secure authentication
- **BCrypt** - Password hashing

## � Quick Start

### Prerequisites
- Node.js (v16+)
- Python (v3.8+)
- MongoDB

### Installation

1. **Clone & Setup**
```bash
git clone <repository-url>
cd avatarLab
```

2. **Backend Setup**
```bash
cd backend
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

3. **Frontend Setup**
```bash
cd ../frontend
npm install
```

4. **Environment Configuration**
Create `.env` in backend/:
```
MONGODB_URI=mongodb://localhost:27017/
JWT_SECRET=your-secret-key
```

5. **Run Application**
```bash
# Start MongoDB
mongod

# Start Backend (Terminal 1)
cd backend
python app.py

# Start Frontend (Terminal 2)
cd frontend
npm start
```

## 🌐 Usage

1. **Sign Up** - Create your account
2. **Upload Image** - Choose any portrait or character
3. **Add Script** - Type what you want the avatar to say
4. **Generate** - Create your talking avatar video
5. **Download** - Save your creation

## 🎬 Demo

Check out our avatar generation in action:

https://github.com/nehaatapasvi/AvatarLab/assets/videos/sadtalker.mp4

*See how static images come to life with synchronized speech and natural lip movements*

*Alternatively: [📹 Download Demo Video](assets/videos/sadtalker.mp4)*

## � API Endpoints

- `POST /api/auth/register` - User registration
- `POST /api/auth/login` - User authentication
- `POST /api/generate_avatar` - Create avatar video
- `GET /api/history` - User generation history
- `GET /api/dashboard` - User statistics

## � Security Features

- JWT-based authentication
- Encrypted password storage
- CORS protection
- Input validation and sanitization

## 🎯 Perfect For

- **Content Creators** - Spokesperson videos
- **Education** - Animated learning content
- **Marketing** - Product demonstrations
- **Social Media** - Engaging avatar content
- **Personal Use** - Custom video messages

## � Project Stats

- **Frontend**: 13+ React components
- **Backend**: Full REST API with authentication
- **Database**: MongoDB with user and generation collections
- **Features**: Complete avatar generation pipeline

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**🎭 Create Amazing Avatars with AvatarLab!**

*Built with passion for interactive digital experiences*
