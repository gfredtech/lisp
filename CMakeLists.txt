cmake_minimum_required(VERSION 3.10)
project (lisp)
include_directories(include)
file(GLOB SOURCES "src/*.c")
add_executable(lisp ${SOURCES})
target_link_libraries(lisp edit)
set(CMAKE_EXPORT_COMPILE_COMMANDS ON)
