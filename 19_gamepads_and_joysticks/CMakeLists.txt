add_executable(19_gamepads_and_joysticks main.cpp)
target_link_libraries(19_gamepads_and_joysticks 
                    ${SDL2_LIBRARY} ${SDL2_IMAGE_LIBRARIES})