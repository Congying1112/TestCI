project (sub_lib)

include_directories(${CMAKE_CURRENT_SOURCE_DIR})

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++14")

add_library(${PROJECT_NAME} SHARED SubLibClass.cpp)

target_link_libraries( ${PROJECT_NAME})