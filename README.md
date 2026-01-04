

---

# NexusChat 💬

A WebSocket-based real-time chat app built with **Python (Flask, SocketIO, Gunicorn)** and a lightweight **HTML/CSS/JS** frontend.
Supports multiple chat rooms, instant message delivery (<100ms), and a simple dark mode toggle.

👉 https://chat-app-jq0d.onrender.com
---

## ✨ Features

* Real-time communication with **Flask-SocketIO + WebSockets**
* Join/leave multiple rooms dynamically
* Messages broadcast instantly (<100ms latency)
* Persistent 7-day chat history (SQLite backend)
* Supports **50+ concurrent sessions**
* Responsive UI with **Bootstrap**
* **Dark mode toggle** for better user experience

---

## 🚀 Tech Stack

* **Backend:** Python, Flask, Flask-SocketIO, Gunicorn, Eventlet
* **Frontend:** HTML, CSS, JavaScript, Bootstrap
* **Database:** SQLite (for storing chat history)


---

## ⚡ Getting Started (Local Setup)

1. Clone this repository

   ```bash
   git clone https://github.com/sarv-projects/chat-app.git
   cd chat-app
   ```

2. Create a virtual environment & install dependencies

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```

3. Run the server

   ```bash
   python3 app.py
   ```



## 📜 License

MIT License. Free to use and modify.

---

## 👤 Author

**Sarvesh Bhattacharyya**


