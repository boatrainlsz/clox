# cmake_minimum_required(VERSION <specify CMake version here>)
project(clox C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(clox
        chunk.c
        vm.h
        value.h
        value.c
        chunk.h
        common.h
        main.c
        memory.c
        debug.c
        debug.h
        memory.h vm.c compiler.h compiler.c scanner.h scanner.c)
