#cmake_minimum_required(VERSION 3.3)
project(sub_exe)

set(SOURCE_FILES
        main.cpp main.cpp)

add_executable(${PROJECT_NAME} ${SOURCE_FILES})

target_link_libraries( ${PROJECT_NAME} )