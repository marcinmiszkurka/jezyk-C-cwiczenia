cmake_minimum_required(VERSION 3.9)
project(stack_structure)

set(CMAKE_CXX_STANDARD 11)

add_executable(stack_structure
        main.c stos.c stos.h dane.c dane.h woda.c woda.h)
