# 📔 MyDiary – Personal Web Diary Application

A full-stack web application built using **Spring MVC**, **JSP**, and **MySQL**, allowing users to securely record, update, and manage personal diary entries.

## 🌐 Features

- 🔐 User registration and login
- 📅 Add, view, edit, and delete diary entries
- 🧠 Session management
- 📦 Layered architecture: Controller → Business → DAO → Entity
- 💾 MySQL database integration
- 💡 Responsive and intuitive user interface (JSP, HTML, CSS)

## 🛠️ Tech Stack

- **Backend**: Java, Spring MVC
- **Frontend**: JSP, HTML5, CSS3
- **Database**: MySQL
- **Build Tool**: Maven

## 🗂️ Project Structure

src/main/java/com.kmk.spring.mydiary/
├── controllers/
├── business/
│ ├── EntryBusinessInterface.java
│ └── EntryBusinessInterfaceImpl.java
│ └── UserBusinessInterface.java
│ └── UserBusinessInterfaceImpl.java
├── dao/
├── entities/



## 🚀 How to Run

1. Clone the repo:  

2. Import the project as a **Maven Project** in Eclipse or IntelliJ.

3. Configure your MySQL database connection in the appropriate Spring configuration file  
   (e.g., `applicationContext.xml`, `spring-servlet.xml`, or Java-based config class).

4. Deploy the application on a local Tomcat server.

5. Access the application in your browser at:  
   `http://localhost:8080/mydiary`

---

## 👨‍💻 Author

**K Manikanta**  
📧 kmanikanta81311@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/k-manikanta)  
🔗 [GitHub](https://github.com/MAnik-1)

