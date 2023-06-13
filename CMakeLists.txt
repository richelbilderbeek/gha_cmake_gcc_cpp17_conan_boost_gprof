cmake_minimum_required(VERSION 3.10)

project(gha_cmake_gcc_cpp17_conan_boost_gprof)

set(CMAKE_CXX_STANDARD 17)

# gprof
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -pg")
set(CMAKE_LFLAGS "${CMAKE_LFLAGS} -pg")

set(CMAKE_CXX_STANDARD 17)

# Boost
set(Boost_USE_STATIC_LIBS OFF) 
set(Boost_USE_MULTITHREADED ON)  
set(Boost_USE_STATIC_RUNTIME OFF)

# Only add this for non-header libraries
# find_package(Boost 1.82.0 COMPONENTS regex) 

if(Boost_FOUND)
    include_directories(${Boost_INCLUDE_DIRS}) 
    add_executable(gha_cmake_gcc_cpp17_conan_boost_gprof main.cpp)
    target_link_libraries(progname ${Boost_LIBRARIES})
endif()