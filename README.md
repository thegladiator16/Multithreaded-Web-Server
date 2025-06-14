# 🔥 Multithreaded Web Server in C++ (epoll + POSIX Threads)

This project implements a high-performance, multithreaded HTTP web server using low-level system programming concepts such as **epoll**, **POSIX threads**, and **thread pooling**. It supports persistent connections, static file serving, graceful shutdown, and is designed to scale to 1000+ concurrent clients.

---

## 📌 Features

- ✅ **Built in C++** with manual socket and thread handling
- ✅ **Non-blocking I/O** using `epoll` (edge-triggered)
- ✅ **Thread Pool** with custom job queue for high concurrency
- ✅ **Persistent Connections** via HTTP keep-alive
- ✅ **Static File Serving**
- ✅ **Graceful Shutdown** via signal handling
- ⚠️ **Request Pipelining** coming soon

---

## 🛠️ Technologies Used

- **C++**
- **POSIX Threads (pthreads)**
- **epoll**
- **Sockets API**
- **Linux System Calls**

---

## 🚀 Setup Instructions

```bash
# Clone the repository
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

# Build the project
mkdir build && cd build
cmake .. && make -j4

# Run the server
./http_server
