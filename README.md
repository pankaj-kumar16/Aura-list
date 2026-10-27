# 🎵 MelodyHub — Music Streaming Web App

MelodyHub is a full-stack music streaming web application designed to provide users with a simple and interactive music listening experience. Users can explore music, play tracks, manage playlists, save their favorite songs, and keep track of their listening history.

## ✨ Features

- **User Authentication:** Register and log in securely using password hashing and JWT-based authentication.
- **Music Discovery:** Browse the available music catalog and discover tracks.
- **Music Player:** Play music through an interactive web-based player.
- **Liked Songs:** Save favorite tracks and manage your liked songs.
- **Custom Playlists:** Create, rename, and delete playlists and manage their tracks.
- **Listening History:** Keep track of previously played songs.
- **Responsive Interface:** Access the application through a modern web interface.
- **REST API:** Backend endpoints for authentication, music, playlists, likes, and listening history.

## 🛠️ Tech Stack

**Frontend**
- HTML5
- CSS3
- Vanilla JavaScript

**Backend**
- Node.js
- Express.js
- REST APIs
- JSON Web Tokens (JWT)
- bcryptjs for password hashing

**Data Storage**
- JSON file-based storage

**Other Tools and Services**
- Jamendo API integration
- dotenv for environment configuration
- Git and GitHub for version control

## 📁 Project Structure

```text
MelodyHub/
├── backend/
│   ├── middleware/
│   ├── routes/
│   └── services/
├── data/
├── public/
│   ├── css/
│   ├── js/
│   ├── app.html
│   ├── index.html
│   └── register.html
├── scripts/
├── .env.example
├── .gitignore
├── package.json
├── package-lock.json
└── server.js
```

## ⚙️ Installation and Setup

### Prerequisites

- Node.js and npm installed
- Git installed
- A Jamendo API client ID if required by your music integration

### 1. Clone the repository

```bash
git clone https://github.com/pankaj-kumar16/MelodyHub.git
```

### 2. Navigate to the project

```bash
cd MelodyHub
```

### 3. Install dependencies

```bash
npm install
```

### 4. Configure environment variables

Create a `.env` file in the project root using `.env.example` as a reference.

```env
PORT=3000
JWT_SECRET=replace_with_a_secure_random_secret
JAMENDO_CLIENT_ID=your_jamendo_client_id
```

Use your own API credentials and a strong, private JWT secret. Never commit your real `.env` file to GitHub.

### 5. Start the application

```bash
npm start
```

For development with automatic server restart:

```bash
npm run dev
```

### 6. Open the application

Visit:

```text
http://localhost:3000
```

## 🎧 How It Works

1. Users register or log in to their account.
2. They explore the available music catalog.
3. They play tracks using the music player.
4. They can like songs and organize tracks into playlists.
5. Authenticated users can access their saved playlists, liked songs, and listening history.

## 🔐 Security

- Passwords are hashed before storage.
- JWT tokens are used for authentication.
- Protected API routes require authentication.
- Environment variables are used for configurable secrets and API credentials.

**Note:** This project is intended as a learning and portfolio project. Before production deployment, review authentication security, data persistence, API usage, and secret management.

## 🚀 Future Improvements

- Migrate JSON file storage to MongoDB or PostgreSQL.
- Add advanced search, filters, and music recommendations.
- Improve mobile responsiveness and accessibility.
- Add automated testing and deployment.
- Introduce a dedicated cloud database and production monitoring.

## 👨‍💻 Author

**Pankaj Kumar**

GitHub: [@pankaj-kumar16](https://github.com/pankaj-kumar16)

---

If you find this project useful, consider giving the repository a ⭐ on GitHub.
