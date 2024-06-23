cmake_minimum_required(VERSION 3.15)

set(CMAKE_CXX_COMPILER clang++)
set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

project(
    LearnSDL
    LANGUAGES CXX
    DESCRIPTION "Learn SDL"
    VERSION 0.1.0
)

add_subdirectory(3rdlibs)
add_subdirectory(cmake)
add_subdirectory(test)
