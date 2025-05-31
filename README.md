---

# Backend API for The hive website {}

This is the backend for a  platform for tech services employment. It provides a RESTful API for  user authentication, and administrative operations.

## Features

* 🔐 **User Authentication** – Register, login, and protect routes using JWT.
* 💾 **MongoDB Integration** – Stores data efficiently with Mongoose.
* ❗ **Error Handling** – Graceful error responses and input validation.

## Tech Stack

* **Backend**: Node.js, Express.js
* **Database**: MongoDB with Mongoose
* **Authentication**: JSON Web Tokens (JWT)
* **Environment**: dotenv

## Getting Started

### Prerequisites

* Node.js (v14 or higher)
* MongoDB (Atlas or local instance)
* npm or yarn

### Installation

1. **Clone the repository**

```bash
git clone https://github.com/Olawale223/backend.git
cd backend
```

2. **Install dependencies**

```bash
npm install
```

3. **Set up environment variables**

Create a `.env` file in the root directory and add:

```env
PORT=5000
MONGO_URI=mongodb://localhost:27017/your-db-name
JWT_SECRET=your_jwt_secret
```

4. **Start the development server**

```bash
npm run dev
# or
yarn dev
```

The server will start at `http://localhost:5000`.



## Folder Structure

```
backend/
├── controllers/
├── models/
├── routes/
├── lib/
├── .env
├── server.js
```

## License

MIT © [Olawale223](https://github.com/Olawale223)

---

