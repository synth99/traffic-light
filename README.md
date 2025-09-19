# Traffic Light 🚦

A C++ implementation of a traffic light system.

## Overview

This project simulates a traffic light controller, built entirely in C++. It’s designed to demonstrate core concepts in embedded systems, state machines, and real-time control.

## Features

- Pure C++ logic, no external dependencies
- Modular and easy-to-understand codebase
- Simulates standard traffic light cycles (Red, Yellow, Green)
- Easily extendable for pedestrian crossings, timers, or advanced logic

## Getting Started

### Prerequisites

- A C++17 compatible compiler (e.g., g++, clang++)
- Make (optional, if you use the provided Makefile)

### Build

```bash
git clone https://github.com/synth99/traffic-light.git
cd traffic-light
make
# or, compile manually:
g++ -std=c++17 -o traffic-light main.cpp
```

### Run

```bash
./traffic-light
```

## Project Structure

- `main.cpp` — Entry point and main logic
- `TrafficLight.h/cpp` — Traffic light state machine
- `README.md` — You are here!

## Why Traffic Light?

Traffic lights are classic real-world examples of state machines. This project is a fun way to learn about:

- State transitions and timing
- Modular C++ design
- Basics of embedded or real-time programming

## Contributing

Contributions and suggestions are welcome! Feel free to open issues or pull requests.

## License

This project is licensed under the MIT License.

---

Made with ❤️ by [synth99](https://github.com/synth99)
