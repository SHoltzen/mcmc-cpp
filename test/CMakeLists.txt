cmake_minimum_required (VERSION 2.6)
project(mcmc)


set(MAIN_FILES test_main.cpp mcmc_tests.cpp)
add_executable(mcmc-test ${MAIN_FILES})
add_dependencies(mcmc-test mcmc)