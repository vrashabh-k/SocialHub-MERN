# SocialHub-MERN

A full-stack social media application built using the MERN stack (MongoDB, Express, React, Node.js).

## 🚀 Setup Instructions

### 1. Clone the Repository

```bash
git clone <repo-link>
cd SocialHub-MERN
```

### 2. Install Dependencies

Run the following commands in both the `client` and `server` directories:

```bash
cd client
npm install

cd ../server
npm install
```

### 3. Configure Environment Variables

Inside the `server` folder:

```bash
cp .env.example .env
```

Open the `.env` file and update it with your actual credentials (e.g., MongoDB URI, JWT secret, etc.).

### 4. (Optional) Seed the Database

To seed the database:

- Open `server/index.js`
- Uncomment the two lines in mongoose setup.
- Start the server:

```bash
node index.js
```
- After seeding, comment the lines again.

## 📦 Scripts

### Start Client

```bash
cd client
npm start
```

### Start Server

```bash
cd server
node index.js
```

## ✅ Requirements

- Node.js
- MongoDB (local or Atlas)
- Environment variables configured in `.env`