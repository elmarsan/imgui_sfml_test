add_executable(imgui_sfml_test main.cpp)
target_link_libraries(imgui_sfml_test PRIVATE sfml-graphics)
target_link_libraries(imgui_sfml_test PRIVATE ImGui-SFML::ImGui-SFML)