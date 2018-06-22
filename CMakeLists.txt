cmake_minimum_required(VERSION 3.5)
project(sdl2-tutorial)

set(CMAKE_MODULE_PATH ${CMAKE_MODULE_PATH} "${CMAKE_SOURCE_DIR}/cmake/")

find_package(SDL2 REQUIRED)

include_directories(${SDL2_INCLUDE_DIR})

add_subdirectory(01_hello_SDL)
add_subdirectory(02_getting_an_image_on_the_screen)