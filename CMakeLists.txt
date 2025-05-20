cmake_minimum_required(VERSION 3.30)
project(c_imagery_cmake C)

set(CMAKE_C_STANDARD 11)

add_executable(c_imagery_cmake launcher.c
launcher_func.c
t_bmp24/bmp.c
t_bmp8/bmp.c)
