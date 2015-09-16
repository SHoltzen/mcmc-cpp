# Main source CMake file
# Separated into a library component and an executable component
# Tests link against the library

cmake_minimum_required (VERSION 2.6)
project(mcmc)


set(MAIN_FILES main.cpp)
set(LIB_FILES mcmc.cpp)
add_executable(mcmc-main ${MAIN_FILES})
add_library(mcmc ${LIB_FILES})