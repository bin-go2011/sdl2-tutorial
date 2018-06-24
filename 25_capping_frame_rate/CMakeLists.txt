add_executable(25_capping_frame_rate main.cpp)
target_link_libraries(25_capping_frame_rate 
                    ${SDL2_LIBRARY} ${SDL2_IMAGE_LIBRARIES} ${SDL2_TTF_LIBRARIES})
