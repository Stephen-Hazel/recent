cmake_minimum_required(VERSION 3.5)

project(recent LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(recent main.cpp ../stv/os.cpp)
