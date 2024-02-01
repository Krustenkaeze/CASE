cmake_minimum_required(VERSION 3.16 FATAL_ERROR)

project(GPUPROG CXX CUDA)
#set(CMAKE_CUDA_ARCHITECTURES 75;52)

add_executable(vec-add vec-add.cu)
