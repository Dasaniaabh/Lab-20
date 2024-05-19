cmake_minimum_required(VERSION 3.26)
project(Laba_20 C)

set(CMAKE_C_STANDARD 11)

add_executable(Laba_20
        test.c
        libs/dataStructure/thread/thread.h
        libs/dataStructure/thread/thread.c
        file.c
        tenTaskProgramm.c

)

add_subdirectory(libs)

target_link_libraries(dataStructure)
