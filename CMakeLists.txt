cmake_minimum_required(VERSION 3.20)
project(hash_table C)

set(CMAKE_C_STANDARD 11)

include_directories(src)

add_executable(hash_table
        src/hash_table.c
        src/hash_table.h
        src/main.c
        src/prime.c
        src/prime.h)
