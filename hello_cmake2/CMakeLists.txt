cmake_minimum_required(VERSION 3.6)

# The Project name
project(hello_cmake2)

# The sources shared between the main program and the tests
set (PROJECT_SOURCES hello.cpp hello.h)

# The main Program
add_executable(prog main.cpp ${PROJECT_SOURCES})

# The tests
add_executable(tests testmain.cpp ${PROJECT_SOURCES})
