cmake_minimum_required(VERSION 3.16)
project(clionTest)

set(CMAKE_CXX_STANDARD 14)

add_executable(clionTest
        test.cpp util/myadd.cpp)
