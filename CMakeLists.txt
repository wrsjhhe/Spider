cmake_minimum_required(VERSION 3.8)
project(Spider)

set(CMAKE_CXX_STANDARD 11)

set(INC_DIR ./include/)
set(SRC_DIR ./src/)



include_directories(${INC_DIR})
aux_source_directory(${SRC_DIR} SRC_LIST)
set(SOURCE_FILES ${SRC_LIST})

#link_directories(/usr/lib/x86_64-linux-gnu)
link_libraries(event)

add_executable(Spider ${SOURCE_FILES})
target_link_libraries(Spider event pthread crypt dl)

add_subdirectory(modules)