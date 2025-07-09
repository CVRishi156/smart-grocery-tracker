# **Smart Grocery Expiry Tracking System (Smart-GETS)** 🛒⏰  
![Flask](https://img.shields.io/badge/Flask-2.3-blue)
![React](https://img.shields.io/badge/React-18.2-blue)
![MySQL](https://img.shields.io/badge/MySQL-8.0-blue)

A **web-based application** to track grocery expiry dates, reduce food waste, and send timely notifications. Built with a responsive frontend and secure backend.

🔗 **Live Demo**: _Coming Soon_

---

## 🚀 **Key Features**

- ✅ **Expiry Alerts** – Notifications for items nearing expiry  
- ✅ **CRUD Operations** – Add, update, delete grocery items  
- ✅ **Search & Filter** – Filter items by name, expiry date, etc.  
- ✅ **User Authentication** – Login/register with secure JWT  
- ✅ **Responsive UI** – Works on desktop, tablet, and mobile  

---

## 🧰 **Technology Stack**

| **Frontend**          | **Backend**    | **Database**    | **Other Tools & Libraries**             |
|-----------------------|----------------|------------------|------------------------------------------|
| HTML5                 | Flask (Python) | MySQL / MariaDB  | Postman – API testing                    |
| CSS3                  | Flask-CORS     |                  | JWT – Authentication (PyJWT)            |
| JavaScript (ES6)      | bcrypt         |                  | `mysql-connector` – DB connector        |
| React.js (Planned UI) | Flask-Restful  |                  | dotenv – Environment variable handler   |

---

## ⚙️ **Installation**

### 🔹 1. Clone the Repository

```bash
git clone https://github.com/CVRishi156/Smart-GETS.git
cd Smart-GETS
```

---

### 🔹 2. Install Frontend Dependencies (if React UI is added)

```bash
npm install
```

---

### 🔹 3. Set Up MySQL Database

1. Create a database:

```sql
CREATE DATABASE grocery_db;
```

2. Start MySQL and Apache using **XAMPP Control Panel**

3. Open **phpMyAdmin**:  
👉 [http://localhost/phpmyadmin](http://localhost/phpmyadmin)

4. Create a table inside `grocery_db`:

### 🗃️ Database Schema

```sql
CREATE TABLE groceries (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(255) NOT NULL,
    expiry_date DATE NOT NULL,
    quantity INT NOT NULL
);
```

✅ Click **Go** in phpMyAdmin.

---

### 🔹 4. Configure `.env` File

```env
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=           # Leave empty if no password is set
DB_NAME=grocery_db
```

```env
JWT_SECRET=your_jwt_secret   # Optional but recommended for secured routes
```

---

### 🔹 5. Run the Backend

```bash
python app.py
```

Access backend at: [http://localhost:5000](http://localhost:5000)

---

### 🔹 6. Run the Frontend (Optional)

```bash
npm run dev
```

---

### 🔹 7. Test with Postman

#### ➕ Add a Grocery Item

- **POST** `http://localhost:5000/add`  
- Body:
```json
{
  "name": "Milk",
  "expiry_date": "2025-07-10",
  "quantity": 2
}
```

#### 📦 Get All Items

- **GET** `http://localhost:5000/groceries`

---

## 📂 **Project Structure**

```
Smart-GETS/
├── app.py                 # Flask backend
├── .env                   # Environment variables
├── schema.sql             # SQL for table creation
├── static/                # (Optional) Frontend assets
└── README.md              # Project documentation
```

---

## 🤝 **How to Contribute**

1. **Fork** the repository  
2. Create a branch:
```bash
git checkout -b feature/your-feature
```
3. Commit changes:
```bash
git commit -m "Add new feature"
```
4. Push and open a **Pull Request**

---

## 📚 **Resources**

- [Flask Documentation](https://flask.palletsprojects.com/)
- [MySQL Documentation](https://dev.mysql.com/doc/)
- [React Documentation](https://reactjs.org/)
- [Postman Guide](https://learning.postman.com/)

---

### 🙌 **Happy Tracking – Reduce Waste, Save Money!** 🎯