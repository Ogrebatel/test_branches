cmake_minimum_required(VERSION 3.0.0)
project(testing_git)

set(CMAKE_CXX_STANDARD 17)

set(PROJECT_HEADERS
        )
set(PROJECT_SOURCES
        sources/main.cpp
        )

add_executable(testing_git ${PROJECT_SOURCES} ${PROJECT_HEADERS})
