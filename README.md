# Video-Chat-Application

A lightweight, real-time **video chat system** built using **Python** and **socket programming**. This project enables direct webcam-to-webcam streaming between two devices using simple Python scripts.

---

## Overview

This application uses OpenCV and Python's socket library to establish a **client-server connection** for **real-time video transmission**. It’s perfect for learning the fundamentals of video streaming, networking, and multimedia communication in Python.

---

## Features

* Peer-to-peer streaming over sockets
* Real-time webcam feed using OpenCV
* Modular, easy-to-read code
* Works on LAN without heavy frameworks
* Cross-platform Python 3 support

---

## Project Structure

```
.
├── client.py         # Connects to server and displays received video
├── server.py         # Captures webcam feed and sends it to client
├── videofeed.py      # Frame capture & preprocessing
├── videosocket.py    # Encoding, decoding & data transmission
├── requirements.txt  # Python dependencies
└── README.md         # Project documentation
```

---

## Requirements

Install the following Python packages:

```txt
opencv-python
numpy
```

You can install all at once using:

```bash
pip install -r requirements.txt
```

---

## How to Use

### 1. Start the Server

```bash
python server.py
```

This will activate your webcam and begin sending video frames.

### 2. Start the Client

On another device (or terminal):

```bash
python client.py
```

Ensure the client connects to the correct IP address and port defined in the server.

---

## Sample Output

**Terminal Output Example** (Client):

```
Connecting to server...
Receiving video stream...
Displaying feed...
```

**Terminal Output Example** (Server):

```
Camera started.
Sending frames to client...
Connection established.
```

---

  
