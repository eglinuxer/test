cmake_minimum_required(VERSION 3.25 FATAL_ERROR)

add_subdirectory(math)
add_subdirectory(math1)
add_subdirectory(mathpro)

add_executable(main main.cpp)

target_link_libraries(main
    PRIVATE
        math0
)