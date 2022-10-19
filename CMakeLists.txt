project(calculator)

add_executable(calculator main.cpp calculator.h calculator.cpp)
add_library(calc STATIC calculator.h calculator.cpp)
