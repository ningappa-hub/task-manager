# Backend - Task Manager API

Node.js Express API for Task Manager application with MongoDB.

## Setup

```bash
cd backend
npm install
```

## Environment Variables

Create a `.env` file based on `.env.example`:

```bash
cp .env.example .env
```

Set the following variables:
- `MONGODB_URI`: MongoDB connection string
- `PORT`: Server port (default: 5000)
- `JWT_SECRET`: Secret key for JWT tokens
- `NODE_ENV`: Environment (development/production)

## Development

```bash
npm run dev
```

Server will run on `http://localhost:5000`

## Production

```bash
npm start
```

## Folder Structure

```
models/         # MongoDB schemas
routes/         # API routes
controllers/    # Route controllers/logic
middleware/     # Custom middleware
server.js       # Main server file
```

## Technology Stack

- Node.js & Express
- MongoDB & Mongoose
- JWT Authentication
- CORS
- Bcryptjs (password hashing)
