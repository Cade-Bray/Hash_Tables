cmake_minimum_required(VERSION 3.26)
project(hash_tables)

set(CMAKE_CXX_STANDARD 17)

add_executable(hash_tables main.cpp
        HashTable.cpp
        CSVparser.cpp)
