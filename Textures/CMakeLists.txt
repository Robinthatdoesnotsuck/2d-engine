cmake_minimum_required(VERSION 3.0.0)
project(Textures VERSION 0.1.0)

include_directories(includes)
file(GLOB SOURCES src/*.cpp)

add_executable(Textures ${SOURCES})
target_link_libraries(Textures SDL2main SDL2)