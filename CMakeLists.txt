cmake_minimum_required(VERSION 3.30)
project(webots_playground C)

set(CMAKE_C_STANDARD 11)

add_executable(webots_playground
    src/mavic2pro.c)
