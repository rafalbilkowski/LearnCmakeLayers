cmake_minimum_required(VERSION 3.11)

set(CMAKE_INSTALL_PREFIX "/CmakeAPP")

project(LearnYocto)
add_executable(learnYocto main.cpp)

install(TARGETS 
learnYocto 
DESTINATION 

)