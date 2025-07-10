# Stack Overflow Clone

This is a basic Stack Overflow clone built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It includes core features such as user authentication, asking questions, answering, and voting. This project serves as a practical implementation of a full-stack web application with a clean and responsive UI.

## Features

- User registration and login (JWT-based authentication)
- Post and view questions
- Submit and view answers
- Upvote and downvote answers
- View user profiles

## Tech Stack

- **Frontend:** React.js, HTML5, CSS3, Axios, React Router
- **Backend:** Node.js, Express.js, JWT, bcrypt.js
- **Database:** MongoDB with Mongoose

## Installation & Setup Instructions

### Prerequisites

- Node.js (v18 or higher)
- npm
- MongoDB installed locally or MongoDB Atlas URI

### Step-by-Step Setup

1. **Clone the Repository**

```bash
git clone https://github.com/your-username/stackoverflow-clone.git
cd stackoverflow-clone
```

2. **Install Backend Dependencies**

```bash
cd server
npm install
```

3. **Set Up Environment Variables**

Create a `.env` file in the `server` folder and add:

```
PORT=5000
MONGO_URL=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
```

4. **Start the Backend Server**

```bash
npm start
```

Backend will run on: `http://localhost:5000`

5. **Install Frontend Dependencies**

Open a new terminal:

```bash
cd ../client
npm install
```

6. **Start the React App**

```bash
npm run dev
```

Frontend will run on: `http://localhost:3000`

## Folder Structure

```
client/   --> React frontend
server/   --> Node + Express backend
```

## License

This project is licensed for educational purposes under the MIT License.
