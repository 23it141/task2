# MERN Portfolio

A beautiful, modern portfolio web application built using the MERN stack (MongoDB, Express.js, React, Node.js). Features include an About Me section, Projects, Contact form (with MongoDB integration), and responsive design.

## Features

- ⚡ Fast and modern React frontend (Vite)
- 🎨 Beautiful and responsive CSS (no framework)
- 📝 About Me, Projects, and Contact sections
- 📧 Contact form saves messages to MongoDB
- 🌙 Light/dark mode ready (optional)
- 📱 Mobile friendly

## Project Structure

```
internship_2/
  ├── client/      # React frontend
  └── server/      # Express backend + MongoDB
```

## Getting Started

### Prerequisites

- Node.js (v16+ recommended)
- npm
- MongoDB (local or Atlas)

---

### 1. Clone the repository

```bash
git clone https://github.com/23it141/task2.git
cd task2
```

### 2. Setup the backend

```bash
cd server
cp .env.example .env
# Edit .env and set your MongoDB URI if needed
npm install
npm run dev
```

The backend will run at `http://localhost:5000`.

---

### 3. Setup the frontend

```bash
cd ../client
npm install
npm run dev
```

The frontend will run at `http://localhost:5173` (default Vite port).

---

## Usage

- Visit the frontend URL in your browser.
- Use the Contact form to send a message. Messages are saved to MongoDB.
- Add your own projects and bio by editing the React components in `client/src/components/`.

---

## Environment Variables

Backend (`server/.env`):

```
PORT=5000
MONGO_URI=mongodb://localhost:27017/portfolio
```

---

## Deployment

You can deploy the frontend and backend separately to services like Vercel/Netlify (frontend) and Render/Heroku (backend). Make sure to update environment variables accordingly.

---

## License

This project is open source and available under the [MIT License](LICENSE).