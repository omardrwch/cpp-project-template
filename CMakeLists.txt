cmake_minimum_required(VERSION 3.0)
set(CMAKE_CXX_STANDARD 14)
project(myproject)

# enable_testing()
add_subdirectory(app)
add_subdirectory(lib)
add_subdirectory(test)