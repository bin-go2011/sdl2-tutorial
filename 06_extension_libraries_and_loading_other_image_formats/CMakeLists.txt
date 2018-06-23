add_executable(06_extension_libraries_and_loading_other_image_formats main.cpp)
target_link_libraries(06_extension_libraries_and_loading_other_image_formats 
                    ${SDL2_LIBRARY} ${SDL2_IMAGE_LIBRARIES})