# 💬 Real-Time Chat Application

A real-time chat application built using **Spring Boot**, **WebSocket**, and **STOMP** that enables multiple users to communicate instantly in a shared chat room.

## 🚀 Features

* Real-time messaging using WebSocket
* STOMP protocol support
* Multiple users can join the chat room
* Responsive chat interface
* Instant message broadcasting

---

## 🛠️ Tech Stack

### Backend

* Java 17+
* Spring Boot
* Spring WebSocket
* STOMP Protocol
* Maven

### Frontend

* HTML5
* CSS3
* Bootstrap 5
* JavaScript

---

## 📂 Project Structure

```text
src
 └── main
      ├── java
      │     └── com.chat.app
      │            ├── config
      │            │      └── WebSocketConfig.java
      │            ├── controller
      │            │      └── ChatController.java
      │            ├── model
      │            │      └── ChatMessage.java
      │            └── ChatAppApplication.java
      │
      └── resources
            ├── templates
            │      └── chat.html
            └── application.properties
```

---

## ⚙️ How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/Mohammadkaif002/ChatApp.git
cd ChatApp
```

### 2. Build the project

```bash
mvn clean install
```

### 3. Run the application

```bash
mvn spring-boot:run
```

### 4. Open browser

```text
http://localhost:8080
```
