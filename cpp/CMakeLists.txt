cmake_minimum_required(VERSION 3.28)

project(ppm2png LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 20)

add_subdirectory(ppm2pnglib)
add_subdirectory(ppm2png)
