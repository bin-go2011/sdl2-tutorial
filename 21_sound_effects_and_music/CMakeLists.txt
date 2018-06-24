add_executable(21_sound_effects_and_music main.cpp)
target_link_libraries(21_sound_effects_and_music 
                    ${SDL2_LIBRARY} ${SDL2_IMAGE_LIBRARIES} ${SDL2_MIXER_LIBRARIES})