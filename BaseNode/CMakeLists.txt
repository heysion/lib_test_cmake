cmake_minimum_required(VERSION 2.8)
add_executable(BaseNode src/basenode.c)

TARGET_LINK_LIBRARIES(BaseNode DoseeCommon uv)
install (TARGETS BaseNode 
RUNTIME DESTINATION app)
