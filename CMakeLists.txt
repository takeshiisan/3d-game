cmake_minimum_required(VERSION 3.10.0)
project(3d-game VERSION 0.1.0 LANGUAGES C)

add_executable(3d-game src/3dgame.c)

target_link_libraries(3d-game SDL3 SDL3_image)