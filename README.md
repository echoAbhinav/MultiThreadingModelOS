# Multithreading Simulator - Threading Models Implementation

This module demonstrates different threading models implementation including Many-to-One, One-to-Many, and Many-to-Many threading models using C++.

## Features
- Simulation of different threading models:
  - Many-to-One (M:1)
  - One-to-Many (1:N)
  - Many-to-Many (M:N)
- Thread state visualization
- CPU scheduling simulation
- Thread state transitions (Ready, Running, Blocked, Terminated)

## Requirements
- C++17 or later
- CMake 3.10 or later
- A C++ compiler (g++, MSVC, etc.)

## Build Instructions
```bash
mkdir build
cd build
cmake ..
cmake --build .
```

## Project Structure
- `src/`: Source files
  - `main.cpp`: Entry point
  - `thread_models.hpp`: Threading models declarations
  - `thread_models.cpp`: Threading models implementations
- `CMakeLists.txt`: CMake build configuration
- `README.md`: Project documentation

## Usage
After building, run the executable:
```bash
./thread_simulator
```
