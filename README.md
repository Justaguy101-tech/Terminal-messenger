
# Terminal messenger 

A simple socket-based client-server chat application built in Python. This project demonstrates how TCP sockets work and is a great intro to networking fundamentals.

![Python](https://img.shields.io/badge/python-3.8+-blue)
![Status](https://img.shields.io/badge/status-working-green)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

---

## Features

- Real-time messaging between client and server
- Clean shutdown with "exit" command
- Error handling
- Beginner-friendly code with clear structure

---

## How It Works

1. The server listens for a connection.
2. The client connects to the server using IP and port.
3. Both can send and receive messages.
4. Typing `"exit"` closes the connection.

---

## Files

- `server.py` â€” Runs the chat server
- `client.py` â€” Connects to the server and starts the chat

---

## Project Structure

```
python-socket-chat/
â”œâ”€â”€ client.py
â”œâ”€â”€ server.py
â””â”€â”€ README.md
```

---

## How to Run

### Start the Server
```bash
python3 server.py
```

### Start the Client (in a separate terminal)
```bash
python3 client.py
```

Make sure both are on the same network or adjust the IP address in `client.py`.

---

## Requirements

- Python 3.x

No external libraries requiredâ€”just sockets and Python!

---

## Learning Outcomes

- Socket programming basics
- TCP protocol (vs UDP)
- Client-server communication
- Basic network security concepts

---

## License

MIT License â€” feel free to fork, hack, and improve this.

---

## Author

Nico Estellore

If this project helped you learn sockets or helped in your repo, give it a star!
