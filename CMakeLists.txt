cmake_minimum_required(VERSION 3.25)
project(uGUI)

add_library(
    ${PROJECT_NAME} STATIC
    ugui.c
)

target_include_directories(${PROJECT_NAME} PUBLIC ./)
