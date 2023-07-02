cmake_minimum_required(VERSION 3.26)
project(cave)

find_package(OpenGL REQUIRED)

add_executable(${PROJECT_NAME} src/main.cpp)
target_link_libraries(${PROJECT_NAME} ${OPENGL_LIBRARIES})