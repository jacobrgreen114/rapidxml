cmake_minimum_required(VERSION 3.10)

project(rapidxml)

add_library(rapidxml
        src/rapidxml.cpp
)

target_include_directories(rapidxml
    PUBLIC
        inc
)
