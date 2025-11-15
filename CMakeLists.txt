cmake_minimum_required(VERSION 3.16)
project(pbl2 LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Find SFML 2.6.1
find_package(SFML 2.6.1 COMPONENTS graphics window system REQUIRED)

# Add executable
add_executable(pbl2 src/main.cpp)

# Link SFML libraries
target_link_libraries(pbl2 PRIVATE sfml-graphics sfml-window sfml-system)
