project (sub_lib)

include_directories(${CMAKE_CURRENT_SOURCE_DIR})

add_library(${PROJECT_NAME} SHARED SubLibClass.cpp)

target_link_libraries( ${PROJECT_NAME})