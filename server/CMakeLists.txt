#   SETUP
cmake_minimum_required (VERSION 2.8)
project(automation_server)

#   SOURCE FILES
file(GLOB source_files "src/*.cpp")

#   OUTPUT
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY "${PROJECT_SOURCE_DIR}/bin")

#   CREATE BINARY
add_executable(automation_server ${source_files})
