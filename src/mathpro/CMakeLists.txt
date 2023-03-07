cmake_minimum_required(VERSION 3.25 FATAL_ERROR)

add_library(mathpro mathpro.cpp)

target_include_directories(mathpro
    PUBLIC
        ${CMAKE_CURRENT_LIST_DIR}
)

target_link_libraries(mathpro
    PRIVATE
        math0
    INTERFACE
        math1
)