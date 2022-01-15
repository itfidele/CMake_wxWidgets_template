cmake_minimum_required(VERSION 3.18)
file(GLOB SRC_FILES "*.cpp")

project(project)
if(WIN32)
	add_executable(project WIN32 main.cpp)
else()
	add_executable(project main.cpp)
endif()

target_link_libraries(project wx::net wx::core wx::base)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)