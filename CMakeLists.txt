cmake_minimum_required(VERSION 3.9)

project(MyAwesomeLib)

add_library(MyAwesomeLib STATIC MyAwesomeLib.cpp )

set_target_properties(MyAwesomeLib PROPERTIES PUBLIC_HEADER MyAwesomeLib.h )
