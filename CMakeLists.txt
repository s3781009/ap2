cmake_minimum_required(VERSION 3.21)
project(A1)

set(CMAKE_CXX_STANDARD 14)


include_directories(starter_code)

add_executable(A1
        starter_code/main.cpp
        starter_code/milestone4.h
        starter_code/Node.cpp
        starter_code/Node.h
        starter_code/NodeList.cpp
        starter_code/NodeList.h
        starter_code/PathPlanner.cpp
        starter_code/PathPlanner.h
        starter_code/Types.h)
