
# TODO: Добавьте тесты и целевые объекты, если это необходимо.
cmake_minimum_required(VERSION 3.8)
project(rtKorotkova)

set(CMAKE_CXX_STANDARD 14) 


set(SRC Geometry.cpp
        Camera.cpp
        Material.cpp
        rtracer.cpp
        main.cpp
        LightSource.cpp)

add_executable(rtKorotkova ${SRC})

#find_package(OpenMP)
#if(OpenMP_CXX_FOUND)
#    target_link_libraries(rt_sample_new PUBLIC OpenMP::OpenMP_CXX) 
#endif()