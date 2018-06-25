add_executable(32_text_input_and_clipboard_handling main.cpp)
target_link_libraries(32_text_input_and_clipboard_handling 
                    ${SDL2_LIBRARY} ${SDL2_IMAGE_LIBRARIES} ${SDL2_TTF_LIBRARIES})
