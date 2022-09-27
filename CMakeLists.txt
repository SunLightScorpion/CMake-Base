cmake_minimum_required(VERSION 3.23)
project(SCentral_Bridge)

set(BUILD_SHARED_LIBS OFF)
set(CMAKE_EXE_LINKER_FLAGS "-static")

set(CMAKE_CXX_STANDARD 20)

add_executable(SCentral_Bridge src/core.cpp src/util.h)
