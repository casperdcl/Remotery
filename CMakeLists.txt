cmake_minimum_required(VERSION 2.4)

include_directories(include lib)
add_executable(testSample sample/sample.cpp lib/Remotery.cpp)

if(UNIX)
  SET(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall -O2 -std=c++11 -pthread -lm")
endif(UNIX)
