# cmake_minimum_required(VERSION <specify CMake version here>)
project(clox C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(clox
        chunk.c
        chunk.h
        common.h
        main.c
        memory.c
        memory.h)
