set(LIB_NAME say_hello)
add_library(${LIB_NAME} SHARED say_hello.cpp)
target_include_directories(${LIB_NAME} PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
