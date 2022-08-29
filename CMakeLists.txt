project(Parse-JSON_01)
cmake_minimum_required(VERSION 3.0)
set(APPNAME "parse-json_01")

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")
set(CMAKE_TOOLCHAIN_FILE "E:/workspace_cpp/vcpkg/scripts/buildsystems/vcpkg.cmake")

add_executable(parse-json_01 parse-json_01.cpp)