cmake_minimum_required(VERSION 3.16)

project(ConsoleTetris)

add_executable(ConsoleTetris main.cpp)
set_property(DIRECTORY ${CMAKE_CURRENT_SOURCE_DIR} PROPERTY VS_STARTUP_PROJECT ConsoleTetris)