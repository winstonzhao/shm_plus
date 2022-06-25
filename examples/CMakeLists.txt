cmake_minimum_required(VERSION 3.2)
project(shm_plus_tests)

include_directories(${HEADERS_DIR})

set(SOURCE_FILES main.cpp)
add_executable(shm_plus_tests ${SOURCE_FILES})

target_link_libraries(shm_plus_tests shm_plus)