# User API – Node.js + MongoDB

A simple Express.js REST API that connects to MongoDB to retrieve user details by ID, with added business logic and error handling.

---

##  Features

- **GET /users/:id** — Fetch a single user by MongoDB `_id`
- **Age Restriction** — Only returns users over the age of 21
- **Graceful Error Handling** — Handles invalid ObjectIds and not-found cases
- Built with **Express** and **Mongoose**
- Clean project structure for easy scalability

---

## Getting Started

### 1. Clone the Repository

```
git clone https://github.com/tim-matthew/centivo-assessment.git
cd centivo-assessment
```

### 2. Install Dependencies

```
npm install
```

### 3. Configure Environment Variables
Create a .env file in the root:

```
PORT=3000
MONGO_URI=mongodb://localhost:27017/userdb
```
### 4. Start the Server

```
node index.js
```