project (hello_tests)


# Test
add_executable(tests testmain.cpp)
target_link_libraries(tests PRIVATE hello_lib catch)

