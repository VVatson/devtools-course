cmake_minimum_required(VERSION 2.8.6)

set(CMAKE_MODULE_PATH ${CMAKE_MODULE_PATH} "${CMAKE_SOURCE_DIR}/../cmake/")
include(../cmake/general.cmake)

add_all_sub_dir("${CMAKE_SOURCE_DIR}")

enable_testing()
set(bin_dir "/Users/kirill-kornyakov/Work/GitRepos/devtools-course/build_cmake/bin/")