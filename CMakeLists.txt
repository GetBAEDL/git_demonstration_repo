cmake_minimum_required(VERSION 3.26)
project(git_demonstration_repo)

set(CMAKE_CXX_STANDARD 14)

include_directories(main)

add_executable(git_demonstration_repo
        main/demo.cpp
        main/demo.h)
