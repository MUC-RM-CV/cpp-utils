cmake_minimum_required(VERSION 3.1)

project("cpp-utils")

add_library(utils INTERFACE "src/Utils.h")
target_include_directories(utils INTERFACE "src")
