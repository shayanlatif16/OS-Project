# Producer-Consumer Problem in C++ (Multithreading)

This is a simple implementation of the classic **Producer-Consumer** problem using C++11 threads, mutexes, and condition variables.

## 🧵 Features

- Multiple producers and consumers
- Bounded buffer (shared queue)
- Thread synchronization using `std::mutex` and `std::condition_variable`
- Simulated production and consumption delay

## 📁 Files

- `main.cpp` — contains the full implementation.

## 🔧 Requirements

- C++11 or later
- g++ or any compatible C++ compiler

## 🚀 Build and Run

### Compile
```bash
g++ -std=c++11 -pthread main.cpp -o producer_consumer
