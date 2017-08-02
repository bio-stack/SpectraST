cmake_minimum_required(VERSION 3.8)
project(SpectraST)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

add_custom_target(SpectraST ALL COMMAND make WORKING_DIRECTORY ${CMAKE_CURRENT_SOURCE_DIR} )
