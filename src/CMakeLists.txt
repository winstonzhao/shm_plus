cmake_minimum_required(VERSION 3.2)
project(shm_plus)

set(SOURCE_FILES
    test.h
    test.cpp
)

add_library(shm_plus STATIC ${SOURCE_FILES})