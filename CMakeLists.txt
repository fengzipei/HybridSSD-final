cmake_minimum_required(VERSION 3.7)
project(HybridSSD)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES avlTree.h avlTree.c flash.h flash.c initialize.c initialize.h pagemap.h pagemap.c ssd.c ssd.h)
add_executable(HybridSSD ${SOURCE_FILES})