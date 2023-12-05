cmake_minimum_required(VERSION 3.22.1)

project(MyNameProj)
add_library(MyNameProjLib STATIC main.cpp name.cpp name.h)
add_executable(MyNameProj main.cpp name.cpp)

