cmake_minimum_required(VERSION 3.25 FATAL_ERROR)

add_library(math1 math1.cpp)

target_include_directories(math1
    PUBLIC
        ${CMAKE_CURRENT_LIST_DIR}
)