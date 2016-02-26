cmake_minimum_required(VERSION 3.3)
project(sub_exe)


set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++14")

set(SOURCE_FILES
        main.cpp main.cpp)

add_executable(${PROJECT_NAME} ${SOURCE_FILES})

target_link_libraries( ${PROJECT_NAME} )