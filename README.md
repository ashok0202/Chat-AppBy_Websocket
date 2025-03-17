# ChatApp - Real-Time WebSocket Chat Application

## 📌 Overview
ChatApp is a real-time chat application built using **Spring Boot** and **WebSockets**. It enables users to send and receive messages instantly using **STOMP (Simple Text Oriented Messaging Protocol)** over WebSockets. This project is containerized using **Docker** for easy deployment.

---

## 🛠️ Technologies Used

### **Backend**
- **Java 17**
- **Spring Boot 6**
- **Spring WebSockets**
- **STOMP Protocol**
- **Maven** (Build & Dependency Management)
- **Docker** (Containerization)

### **Frontend**
- **HTML, CSS, JavaScript**
- **Bootstrap 5** (For Styling)
- **SockJS & Stomp.js** (WebSocket Client Libraries)

### **Database** (Optional for persistent chat storage)
- **MySQL / PostgreSQL** (Can be integrated for message persistence)

---

## 🚀 Features
- Real-time messaging using WebSockets
- Simple and user-friendly UI
- Supports multiple users in the chat
- Dockerized for easy deployment

---

## 🏗️ Project Structure
```
chat-app/
│── src/
│   ├── main/
│   │   ├── java/com/chat_app/
│   │   │   ├── controller/ChatController.java
│   │   │   ├── model/ChatMessage.java
│   │   │   ├── config/WebSocketConfig.java
│   ├── resources/
│   │   ├── static/
│   │   │   ├── chat.html
│   │   ├── application.properties
│── pom.xml
│── Dockerfile
│── README.md
```

---

## ⚙️ How to Run Locally
### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/your-repo/chat-app.git
cd chat-app
```

### **2️⃣ Build the Project**
```sh
mvn clean package -DskipTests
```

### **3️⃣ Run the Application**
```sh
mvn spring-boot:run
```

### **4️⃣ Open the Chat UI**
Navigate to:
```
http://localhost:8080/chat
```

---

## 🐳 Running with Docker
### **1️⃣ Build Docker Image**
```sh
docker build -t chat-app .
```

### **2️⃣ Run Docker Container**
```sh
docker run -p 8080:8080 chat-app
```

---

## 📜 WebSocket Endpoints
| Endpoint         | Description |
|-----------------|-------------|
| `/app/send`     | Send messages |
| `/topic/messages` | Receive messages |

---

## 📩 Contributions
Feel free to fork this repo, create a feature branch, and submit a pull request!

---

## 🔥 Author
**Your Name**  
📧 Email: 21ne5a0225@gmail.com  
🌐 GitHub: https://github.com/ashok0202



