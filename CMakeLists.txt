
cmake_minimum_required(VERSION 3.18)
project(cx_wxWidgets_template VERSION 1.0.0)

if(COMMAND cmake_policy)
    cmake_policy(SET CMP0003 NEW)
endif(COMMAND cmake_policy)

add_subdirectory(3rdparty)
add_subdirectory(src)

