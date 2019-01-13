cmake_minimum_required(VERSION 3.5)
project(Myproject VERSION 1.0.0)

add_subdirectory(libraries)
add_subdirectory(applications)

message("hello")
message(${PROJECT_SOURCE_DIR})
message(${PROJECT_BINARY_DIR})
message(${PROJECT_VERSION})
message("${INCLUDE_DIRECTORIES}")
