# Multithreaded Web Server in Rust

A simple HTTP web server built **from scratch in Rust** to explore low-level networking and concurrency. Inspired by the final project in *The Rust Programming Language* book, this project demonstrates how to implement a basic server without relying on external web frameworks.

---

## Features

- **TCP Socket Server:** Listens for raw TCP connections using Rust’s `std::net` module.
- **HTTP Request Parsing:** Handles minimal GET requests and returns dynamic responses.
- **Custom Thread Pool:** Processes multiple client connections concurrently and safely using Rust’s ownership and threading primitives.
- **Graceful Shutdown:** Cleans up worker threads and resources on exit.

---

## Why It Matters

This project shows how to design a **high-performance backend component** without relying on frameworks, gaining direct control over networking and concurrency. The concepts—networking, concurrency, thread pools—map directly to building scalable blockchain nodes and other systems software.

---

## Tech Stack

- **Rust** (safe systems programming)
- **TCP / HTTP**
- **Threads & Message Passing**

---

## Getting Started

Clone the repository and run the server locally:

```bash
git clone https://github.com/yourusername/yourrepo.git
cd yourrepo
cargo run
