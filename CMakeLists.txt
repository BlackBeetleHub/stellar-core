cmake_minimum_required(VERSION 3.2.2)
project(stellar)

set(CMAKE_CXX_STANDARD 11)


add_subdirectory(lib)
add_subdirectory(src)
add_subdirectory(lib/libsodium)
add_subdirectory(lib/xdrpp)