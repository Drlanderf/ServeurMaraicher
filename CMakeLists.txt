cmake_minimum_required(VERSION 3.24)
project(ServeurMaraicher)

set(CMAKE_CXX_STANDARD 17)

add_executable(ServeurMaraicher main.cpp lib_socket/library.cpp)
