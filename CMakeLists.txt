cmake_minimum_required(VERSION 3.25)
project(redis)

set(CMAKE_CXX_STANDARD 17)

add_executable(redis 03_server.cpp 03_client.cpp)
