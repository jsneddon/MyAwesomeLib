cmake_minimum_required(VERSION 3.10)

project(MyAwesomeLib VERSION 1.0.0)

add_library(MyAwesomeLib STATIC MyAwesomeLib.cpp )

configure_file( MyAwesomeLibConfig.cmake.in MyAwesomeLibConfig.cmake @ONLY )




