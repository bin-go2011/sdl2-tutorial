add_executable(16_true_type_fonts main.cpp)
target_link_libraries(16_true_type_fonts 
                    ${SDL2_LIBRARY} ${SDL2_IMAGE_LIBRARIES} ${SDL2_TTF_LIBRARIES})