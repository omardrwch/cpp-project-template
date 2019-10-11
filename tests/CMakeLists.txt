link_directories(${myproject_SOURCE_DIR}/lib/src/sublib1)
link_directories(${myproject_SOURCE_DIR}/lib/src/sublib2)

include_directories(${myproject_SOURCE_DIR}/lib/include/sublib1)
include_directories(${myproject_SOURCE_DIR}/lib/include/sublib2)

add_executable(sum_test sum_test.cpp)
target_link_libraries(sum_test mylib)

add_test(NAME sum_test COMMAND sum_test)
