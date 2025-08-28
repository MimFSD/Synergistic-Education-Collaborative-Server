Sever Site of Synergistic-Education-Collaborative  :
Online Group Study -
Assessment Server


## 🛠 Prerequisites

* **Node.js & npm** installed → check with:

  ```bash
  node -v
  npm -v
  ```
* **MongoDB** running locally (`mongodb://127.0.0.1:27017`) or an Atlas cluster.
* **Git** (if you’re cloning from GitHub).

---

## 🚀 Run Instructions (Backend Only)

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Synergistic-Education-Collaborative-Server.git
cd Synergistic-Education-Collaborative-Server
```

### 2. Install dependencies

```bash
npm install
```

### 3. Create `.env` file

Inside the root folder, add:

```env
PORT=5000
MONGO_URI=mongodb://127.0.0.1:27017/educationDB
JWT_SECRET=yourSecretKey
```

*(adjust values depending on your project setup)*

### 4. Start MongoDB (if using local DB)

On another terminal:

```bash
mongod
```

### 5. Run the server

For dev mode (with hot reload via Nodemon):

```bash
npm run dev
```

For normal start:

```bash
npm start
```

---

## ✅ Verify

Once running, open browser/Postman:

* `http://localhost:5000/` → (may return API status / welcome message)
* `http://localhost:5000/api/...` → check routes

---


