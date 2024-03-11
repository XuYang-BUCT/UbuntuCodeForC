cmake_minimum_required(VERSION 3.5)

project(hello_cmake)

# print message
message(
  "hello_cmake_BINARY_DIR: ${hello_cmake_BINARY_DIR},PROJECT_BINARY_DIR:${PROJECT_BINARY_DIR}"
)

add_executable(${PROJECT_NAME} main.cpp)
