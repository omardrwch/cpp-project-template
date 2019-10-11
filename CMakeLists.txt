cmake_minimum_required(VERSION 3.0)
set(CMAKE_CXX_STANDARD 14)
enable_testing()   # see https://gitlab.kitware.com/cmake/community/wikis/doc/ctest/Testing-With-CTest
project(myproject)

add_subdirectory(app)
add_subdirectory(lib)
add_subdirectory(tests)