cmake_minimum_required(VERSION 2.8)
PROJECT(BaseNode)
PROJECT(Base2)
include_directories(/opt/libuv/include ../inc)
link_directories(BaseNode /opt/libuv/lib)
add_subdirectory(BaseNode basenode )
add_subdirectory(DoseeCommon DoseeCommon)
SET(CMAKE_INSTALL_PREFIX ../)

