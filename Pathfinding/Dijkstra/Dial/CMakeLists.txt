
cmake_minimum_required(VERSION 3.10)
project(Dial)

set(CMAKE_CXX_STANDARD 17)
add_compile_options(-Wall -Wextra -Wpedantic)

include_directories(src)

add_subdirectory(src)
add_subdirectory(tst)
add_subdirectory(googletest)

