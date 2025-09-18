cmake_minimum_required(VERSION 4.0.2)   #3.4.1
target_link_options(${CMAKE_PROJECT_NAME} PRIVATE "-Wl,-z,max-page-size=16384")
