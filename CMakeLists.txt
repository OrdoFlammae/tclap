cmake_minimum_required(VERSION 3.10.2)

project(tclap)

add_library(${PROJECT_NAME} INTERFACE)

target_include_directories(${PROJECT_NAME} SYSTEM INTERFACE include)
