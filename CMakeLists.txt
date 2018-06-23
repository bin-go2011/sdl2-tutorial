cmake_minimum_required(VERSION 3.5)
project(sdl2-tutorial)

set(CMAKE_MODULE_PATH ${CMAKE_MODULE_PATH} "${CMAKE_SOURCE_DIR}/cmake/")

find_package(SDL2 REQUIRED)
find_package(SDL2_image REQUIRED)

include_directories(
    ${SDL2_INCLUDE_DIR}
    ${SDL2_IMAGE_INCLUDE_DIR}
)

add_subdirectory(01_hello_SDL)
add_subdirectory(02_getting_an_image_on_the_screen)
add_subdirectory(03_event_driven_programming)
add_subdirectory(04_key_presses)
add_subdirectory(05_optimized_surface_loading_and_soft_stretching)
add_subdirectory(06_extension_libraries_and_loading_other_image_formats)