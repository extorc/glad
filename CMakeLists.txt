cmake_minimum_required(VERSION 3.14)

project(GLAD)

add_library(GLAD src/glad.c)
target_include_directories(GLAD PUBLIC include/)
