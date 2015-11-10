cmake_minimum_required(VERSION 3.3)
project(AVL_Tree_Heist)

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall -Werror -Wno-unused-variable")

set(SOURCE_FILES
    checkavl.c)

add_executable(AVL_Tree_Heist ${SOURCE_FILES})