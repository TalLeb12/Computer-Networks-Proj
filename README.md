# Computer Networks Project

## Overview

This repository contains a Python project developed as part of a **Computer Networks course** during my Computer Science studies.

The project focuses on understanding how network communication works by implementing both **packet analysis tools** and a **client–server communication system using sockets**.

The repository is divided into two main parts:

1. **Packet Analysis Tool** – parsing and analyzing captured network packets.
2. **Client–Server Chat System** – implementing communication between multiple clients and a server using sockets.

---

## Technologies

* Python 
* TCP sockets
* Basic UI using Python
* Network packet analysis
* Wireshark packet data

---

## Project Structure

```text
Computer-Networks-Proj
│
├── Part 1 (packet_analyzer)
│
├── Part 2 (chat_system)
│   ├── Server.py
│   └── Client - GUI.py
│
└── README.md
```

---

## Part 1 – Packet Analyzer

This component processes captured packets exported from **Wireshark**.

The program extracts and displays useful information from network packets such as:

* Source IP address
* Destination IP address
* Protocol information
* Packet structure fields

The goal of this part was to better understand how network packets are structured and transmitted.

---

## Part 2 – Client–Server Chat System

The second part of the project implements a **simple communication system using sockets**.

The system includes:

* A **server** that manages connections
* Multiple **clients** that connect to the server
* A basic **UI for sending and receiving messages**

### Key Concepts Demonstrated

* TCP socket communication
* Client-server architecture
* Message transmission between connected clients
* Handling multiple connections
* Basic user interface for interaction

---

## How the System Works

1. The server starts and listens for incoming connections.
2. Clients connect to the server using sockets.
3. Messages are transmitted through the server between connected clients.

Architecture:

```text
Client A
   \
    \ 
     Server
    /
Client B
```

---

## Running the Chat System

1. Start the server:

```bash
python Server.py
```

2. Run one or more clients:

```bash
python Client - GUI.py
```

3. Send messages between connected clients through the server.

---

## Purpose

The goal of this project was to gain hands-on experience with:

* Network communication protocols
* Socket programming
* Client-server system design
* Understanding how network data is transmitted and analyzed

---

## Academic Context

This project was developed as part of a **Computer Networks course** during my Computer Science degree.
