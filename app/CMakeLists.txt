link_directories(${myproject_SOURCE_DIR}/lib/src/sublib1)
link_directories(${myproject_SOURCE_DIR}/lib/src/sublib2)
link_directories(${myproject_SOURCE_DIR}/lib/src)

include_directories(${myproject_SOURCE_DIR}/lib/include/sublib1)
include_directories(${myproject_SOURCE_DIR}/lib/include/sublib2)

add_executable(subapp1 subapp1/main.cpp)
target_link_libraries(subapp1 mylib)

add_executable(subapp2 subapp2/main.cpp)
target_link_libraries(subapp2 mylib)

