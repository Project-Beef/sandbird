cmake_minimum_required(VERSION 3.15)
project(sandbird)

add_library(${PROJECT_NAME} src/sandbird.c src/sandbird.h)
target_include_directories(${PROJECT_NAME} PUBLIC src)
