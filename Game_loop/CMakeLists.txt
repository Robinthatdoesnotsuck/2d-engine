cmake_minimum_required(VERSION 3.0.0)
project(Game_Loop VERSION 0.1.0)

include_directories(includes)
file(GLOB SOURCES src/*.cpp)

add_executable(Game_Loop ${SOURCES})
target_link_libraries(Game_Loop SDL2main SDL2)

