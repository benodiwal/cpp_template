cmake_minimum_required(VERSION 3.22.1)
project(cpp_template)

set(CMAKE_CXX_STANDARD 14)

include_directories(include)

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY  ${CMAKE_BINARY_DIR}/../bin)
set(CMAKE_LIBRARY_OUTPUT_DIRECTORY  ${CMAKE_BINARY_DIR}/../bin)

add_subdirectory(src)
add_subdirectory(tests)

enable_testing()