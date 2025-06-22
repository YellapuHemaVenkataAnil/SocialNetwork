## 📤 How to Insert Data into the Database

To insert data into the MongoDB database, follow these steps:

1. **Start the backend server** using the command:

Cd cleint

2. Install dependencies:
  
3. Start the React app:


The app will run at `http://localhost:3000`.

---

## Node.js Backend Setup

1. Go to the `server` folder:

2. Install dependencies:

3. Create a `.env` file in the `server` folder:

4. Start the backend server:


The API will be available at `http://localhost:5000`.

---

## Inserting Data into MongoDB

To insert data into the database:

1. Make a `POST` request to the backend API route (e.g. `/api/data/add`).
2. Set the header: `Content-Type: application/json`.
3. Pass your data as JSON in the request body.
4. Use tools like Postman, Thunder Client, or send it from the frontend using `fetch()` or `axios()`.

The backend will handle storing the data in MongoDB.

---

## Run Both Frontend and Backend

Use two terminal windows:

**Terminal 1 (Frontend):**
  cd client
  npm run dev

**Terminal 2 (Backend):**
  cd server
  node app

  

Optional: use `concurrently` to run both with one command.

---

## Environment

- Frontend: React (Port 3000)
- Backend: Node.js + Express (Port 5000)
- Database: MongoDB (Local or Atlas)


