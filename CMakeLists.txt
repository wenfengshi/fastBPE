cmake_minimum_required(VERSION 3.13)
project(bpe)

#set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11 -march=native -O3 -pthread" )


include_directories(bpe)

add_executable(bpe
        bpe/bpe.hpp
        bpe/main.cc
        )
