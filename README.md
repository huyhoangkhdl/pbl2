# pbl2

A C++ project using SFML 2.6.1 (Simple and Fast Multimedia Library).

## Requirements

- CMake 3.16 or higher
- C++17 compatible compiler
- SFML 2.6.1

## Building

### Installing SFML 2.6.1

#### Ubuntu/Debian
```bash
sudo apt-get update
sudo apt-get install libsfml-dev
```

#### macOS (using Homebrew)
```bash
brew install sfml
```

#### Windows
Download SFML 2.6.1 from the [official website](https://www.sfml-dev.org/download.php) and follow the installation instructions.

### Build Instructions

```bash
mkdir build
cd build
cmake ..
make
```

## Running

After building, run the executable:
```bash
./pbl2
```

This will open a window displaying a green circle using SFML 2.6.1.

## Project Structure

```
pbl2/
├── CMakeLists.txt    # CMake configuration
├── src/
│   └── main.cpp      # Main source file
└── README.md         # This file
```