cmake_minimum_required(VERSION 3.6)

# The Project name
project(hello_cmake2)

# The subdirectories - will tell CMake to go into this subdirectory and execute the CMakeLists file there.
add_subdirectory(thirdparty/catch)
add_subdirectory(src)
add_subdirectory(test)




