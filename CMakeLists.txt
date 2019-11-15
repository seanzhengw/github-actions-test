cmake_minimum_required (VERSION 3.14)

project(actiontest)

set(ACTIONTEST_SRCS 
    src/main.cpp
)

add_executable(actiontest ${ACTIONTEST_SRCS})
