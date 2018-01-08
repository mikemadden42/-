cmake_minimum_required(VERSION 2.8)

project(goodbye C)

set(CMAKE_C_STANDARD 11)
#set(CMAKE_C_FLAGS "-Wall -Wextra -pedantic")

add_executable(goodbye goodbye.c)
