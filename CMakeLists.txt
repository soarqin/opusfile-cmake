cmake_minimum_required(VERSION 2.8)

project(opusfile)

#ogg is required to build
add_subdirectory(ogg)
#opus is required to build
set(BUILD_TESTING OFF CACHE INTERNAL "" FORCE)
add_subdirectory(opus)
#opusfile
add_subdirectory(opusfile)
