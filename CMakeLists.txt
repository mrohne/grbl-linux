cmake_minimum_required(VERSION 3.10)
project(grblHAL C)

add_compile_definitions(F_CPU=16000000)
add_compile_definitions(INJECT_BLOCK_BUFFER_SIZE=256)
#add_compile_definitions(SQUARING_ENABLED=1)

include(soft/CMakeLists.txt)
include(core/CMakeLists.txt)

