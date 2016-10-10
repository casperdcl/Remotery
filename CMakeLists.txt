cmake_minimum_required(VERSION 2.4)

include_directories(include lib)
add_executable(testSample sample/sample.c lib/Remotery.c)
