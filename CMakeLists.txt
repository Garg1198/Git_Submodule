cmake_minimum_required(VERSION 3.22)

project(cppTemplate
    VERSION 1.0.0
    LANGUAGES C CXX
)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSION OFF)

set(LIBRARY mylib)
set(EXECUTABLE exec)

include_directories(include)
add_subdirectory(src)
add_subdirectory(application)