cmake_minimum_required(VERSION 2.9)
set( CMAKE_BUILD_TYPE "Debug")
set( CMAKE_CXX_COMPILER "C:/ProgramData/chocolatey/lib/mingw/tools/install/mingw64/bin/g++.exe" )
set( CMAKE_C_COMPILER "C:/ProgramData/chocolatey/lib/mingw/tools/install/mingw64/bin/gcc.exe" )

project(hello_world)

add_executable(app main.cpp)