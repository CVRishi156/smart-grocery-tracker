# **Smart Grocery Expiry Tracking System (Smart-GETS)** 🛒⏰   
![Flask](https://img.shields.io/badge/Flask-2.3-blue)
![React](https://img.shields.io/badge/React-18.2-blue)
![MySQL](https://img.shields.io/badge/MySQL-8.0-blue)   

A **web-based application** to track grocery expiry dates, reduce food waste, and send timely notifications. Built with a responsive frontend and secure backend.  

**Live Demo**:  

---

## **Key Features** ✨  
✔ **Expiry Alerts** – Notifications for items nearing expiry.  
✔ **CRUD Operations** – Add, update, or delete items easily.  
✔ **Search & Filter** – Find items by name, category, or expiry date.  
✔ **User Authentication** – Secure login/registration with encrypted passwords.  
✔ **Responsive UI** – Works on desktop, tablet, and mobile.  

---

## **Technology Stack** 🧰  
| **Frontend** | **Backend**| **Database**|  
|--------------|------------|-------------|  
| HTML5        |  Flask     | MySQL       |  
| CSS3         |            |             |
| JavaScript   |            |             |  

---

## **Installation** ⚙️  

### **1. Clone the Repository**  
```bash
git clone https://github.com/CVRishi156/Smart-GETS.git
cd Smart-GETS
```

### **2. Install Dependencies**  
```bash
npm install
```

### **3. Set Up MySQL Database**  
1. Create a database:  
   ```sql
   CREATE DATABASE smart_gets;
   ```  
2. Import the schema from `database/schema.sql`.  
3. Configure `.env` file:  
   ```env
   DB_HOST=localhost
   DB_USER=root
   DB_PASSWORD=yourpassword
   DB_NAME=smart_gets
   JWT_SECRET=your_jwt_secret
   ```

### **4. Run the backend**  
```bash
python app.py
```
Access at: `http://localhost:5000`  

### **5. Run the Frontend** 
```bash
npm run dev
```

---

## **Project Structure** 📂  
![image](https://github.com/user-attachments/assets/15b193de-7092-4d70-b91b-88521e55a2b6)


```
---

## **How to Contribute** 🤝  
1. **Fork** the repository.  
2. Create a branch:  
   ```bash
   git checkout -b feature/your-feature
   ```  
3. Commit changes:  
   ```bash
   git commit -m "Add awesome feature"
   ```  
4. Push and open a **Pull Request**.  

---





---

🚀 **Happy Tracking! Reduce Waste, Save Money!** 🚀  

---

### **Need Help?**  
- **MySQL Setup**: Refer to [MySQL Docs](https://dev.mysql.com/doc/).  
- **Node.js Issues**: Check [Stack Overflow](https://stackoverflow.com/).  
