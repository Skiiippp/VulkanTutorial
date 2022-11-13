cmake_minimum_required(VERSION 3.23)
project(HelloTriangle)

set(CMAKE_CXX_STANDARD 17)

add_executable(HelloTriangle
        main.cpp
        #tester.cpp
        )

target_link_libraries(HelloTriangle -lglfw -lvulkan -ldl -lpthread -lX11 -lXxf86vm -lXrandr -lXi)
