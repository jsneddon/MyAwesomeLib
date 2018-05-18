cmake_minimum_required(VERSION 3.10)

project(MyAwesomeLib)

add_library(MyAwesomeLib STATIC MyAwesomeLib.cpp )

configure_file( MyAwesomeLibConfig.cmake.in MyAwesomeLibConfig.cmake @ONLY )




