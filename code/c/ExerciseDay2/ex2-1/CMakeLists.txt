cmake_minimum_required (VERSION 2.6)
set (CMAKE_C_STANDARD 99)

project (Exercise2-1)

include_directories(${PROJECT_SOURCE_DIR})
add_executable(Exercise2-1 exercise2-1.c stresstransform.c)
target_link_libraries(Exercise2-1 m)
