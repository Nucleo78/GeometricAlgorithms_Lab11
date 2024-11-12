cmake_minimum_required(VERSION 3.28)
project(LAB_11)

set(CMAKE_CXX_STANDARD 11)

add_executable(LAB_11 main.cpp
        vec3.h
        color.h)

add_compile_options("$<$<C_COMPILER_ID:MSVC>:/utf-8>")
add_compile_options("$<$<CXX_COMPILER_ID:MSVC>:/utf-8>")
