# Vinod-Assignment-
# Note-Taking App

A full-stack, mobile-friendly note-taking app with email/OTP and Google authentication.

## Tech Stack

- **Frontend:** ReactJS (TypeScript)
- **Backend:** Node.js (TypeScript, Express)
- **Database:** MongoDB (default, can switch to MySQL/Postgres)
- **Auth:** JWT, Google OAuth, Email + OTP

## Setup

### 1. Clone the repository

```sh
git clone https://github.com/your-username/note-taking-app.git
cd note-taking-app
```

### 2. Install Dependencies

#### Frontend

```sh
cd frontend
npm install
```

#### Backend

```sh
cd ../backend
npm install
```

### 3. Environment Variables

- Copy `.env.example` to `.env` in backend and fill in values.
- For Google OAuth, set up credentials in Google Cloud Console and add them to `.env`.

### 4. Running Locally

#### Backend

```sh
cd backend
npm run dev
```

#### Frontend

```sh
cd frontend
npm run dev
```

### 5. Deployment

- Deploy frontend (e.g., Vercel/Netlify).
- Deploy backend (e.g., Railway, Render, Heroku).
- Use MongoDB Atlas for managed MongoDB.

## Features

- Email + OTP signup/login
- Google OAuth signup/login
- JWT-protected APIs
- Create/Delete notes
- Responsive design; closely matches provided assets

## License

MIT
