add_executable(20_force_feedback main.cpp)
target_link_libraries(20_force_feedback 
                    ${SDL2_LIBRARY} ${SDL2_IMAGE_LIBRARIES})