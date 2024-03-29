set(CMAKE_EXPORT_COMPILE_COMMANDS ON)
add_executable(${PROJECT_NAME} main.cpp)
target_link_libraries(${PROJECT_NAME} say_hello)
