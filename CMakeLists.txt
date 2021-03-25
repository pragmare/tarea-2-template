cmake_minimum_required(VERSION 3.17)
project(tarea2)

set(CMAKE_CXX_STANDARD 14)

add_executable(tarea2 principal.cpp src/info.cpp src/utils.cpp src/cadena.cpp include/utils.h include/cadena.h include/info.h include/usoTads.h src/usoTads.cpp)