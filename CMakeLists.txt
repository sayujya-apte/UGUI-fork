cmake_minimum_required(VERSION 3.25)
project(uGUI)

add_library(
    ${PROJECT_NAME} STATIC
    ugui.c
)

target_include_directories(${PROJECT_NAME} PUBLIC ./)
target_compile_definitions(${PROJECT_NAME} PUBLIC USE_FONT_8X12)
