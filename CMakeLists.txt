cmake_minimum_required(VERSION 2.8)
project(tinymp3)
add_library(tinymp3 shine_mp3.c)
target_include_directories(tinymp3 PUBLIC ${CMAKE_CURRENT_LIST_DIR})