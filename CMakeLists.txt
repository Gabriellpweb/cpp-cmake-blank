cmake_minimum_required(VERSION 3.0)

project(MyApp)

add_subdirectory(src)
add_executable(${PROJECT_NAME} ${SOURCES})