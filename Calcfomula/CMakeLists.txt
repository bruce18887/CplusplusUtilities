cmake_minimum_required(VERSION 3.0.0)
project(Calcfomula VERSION 0.1.0)

add_executable(Calcfomula CalculatorFomula2.cpp)

set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
include(CPack)
