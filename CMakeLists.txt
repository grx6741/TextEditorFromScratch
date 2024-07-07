cmake_minimum_required(VERSION 3.29)
set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED True)

project(TextEditor VERSION 0.01)

file(GLOB source_files Main.cpp)

add_executable(
    ${CMAKE_PROJECT_NAME}
    ${source_files}
)

add_subdirectory(src)
