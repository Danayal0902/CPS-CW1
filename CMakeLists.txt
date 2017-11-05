cmake_minimum_required(VERSION 3.8)
project(CPS_CW1)

set(CMAKE_CXX_STANDARD 11 )

set(clang-omp++ -fopenmp main.cpp -o main
        ./main)


set(SOURCE_FILES main.cpp)
add_executable(CPS_CW1 ${SOURCE_FILES})