cmake_minimum_required(VERSION 3.16)
project(streamix)

set(CMAKE_CXX_STANDARD 14)

include_directories(src)

add_executable(streamix
        src/streamx.cli.cpp)
