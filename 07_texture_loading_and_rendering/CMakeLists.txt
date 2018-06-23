add_executable(07_texture_loading_and_rendering main.cpp)
target_link_libraries(07_texture_loading_and_rendering 
                    ${SDL2_LIBRARY} ${SDL2_IMAGE_LIBRARIES})