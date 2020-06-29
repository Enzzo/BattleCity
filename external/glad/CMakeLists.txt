cmake_minimum_required(VERSION 3.17.3 FATAL_ERROR)
project(Glad)
add_library(glad STATIC Include/glad/glad.h src/glad.c)
target_include_directories(glad PUBLIC include/)