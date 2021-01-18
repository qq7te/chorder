cmake_minimum_required(VERSION 3.16)
project(chorder)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)
include_directories(FeatherChorder)

add_executable(chorder
    FeatherChorder/BluefruitConfig.h
    FeatherChorder/ChordMappings.h
    FeatherChorder/FeatherChorder.ino
    FeatherChorder/KeyCodes.h
    LICENSE.txt
    README.md)
