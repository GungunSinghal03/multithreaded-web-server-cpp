# Multithreaded HTTP Web Server (C++)

## 🚀 Overview

This project is a high-performance multithreaded HTTP web server built using C++ and socket programming. It handles multiple client requests concurrently and serves static web content.

## 🧠 Features

* TCP socket-based server
* Multithreading using std::thread
* Handles multiple client connections concurrently
* Parses HTTP GET requests
* Serves static HTML files
* Error handling (404 Not Found)
* Modular and scalable design

## ⚙️ Tech Stack

* C++
* Socket Programming (TCP/IP)
* Multithreading (std::thread)
* File Handling

## 📂 Project Structure

```
src/
 ├── server.cpp
 ├── request_handler.cpp
 ├── thread_pool.cpp
 └── utils.cpp
```

## ▶️ How to Run

### Compile:

```bash
g++ src/*.cpp -o server -pthread
```

### Run:

```bash
./server
```

Open browser:

```
http://localhost:8080
```

## 📸 Example Request

```
GET /index.html HTTP/1.1
```

## 🧪 Learning Outcomes

* Understanding of socket programming
* Multithreading and concurrency
* HTTP protocol basics
* System-level programming in C++

## 📌 Future Improvements

* Thread Pool implementation
* Non-blocking I/O
* Performance optimization
* Load testing

## 👩‍💻 Author

Gungun Singla

