cmake_minimum_required(VERSION 3.10)

project(VerletIntegration)

file(GLOB_RECURSE SOURCES 
    ${CMAKE_CURRENT_LIST_DIR}/*.cpp
    ${CMAKE_CURRENT_LIST_DIR}/*.h)
	
add_executable(VerletIntegration ${SOURCES})

set_target_properties(VerletIntegration PROPERTIES CXX_STANDARD 17)
