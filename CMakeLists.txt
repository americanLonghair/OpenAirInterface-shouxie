# cmake_minimum_required(VERSION <specify CMake version here>)
project(OpenAirInterface_)

set(CMAKE_CXX_STANDARD 14)

add_executable(OpenAirInterface_ main.cpp common/utils/LOG/log.c)