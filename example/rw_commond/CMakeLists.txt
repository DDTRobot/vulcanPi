cmake_minimum_required(VERSION 3.0)
project(RWCommond)

# compile with source code
set(VulcanSerialRootPath "${CMAKE_CURRENT_SOURCE_DIR}/../..")
include_directories(${VulcanSerialRootPath}/include)
list(APPEND VulcanSerialSourceFiles ${VulcanSerialRootPath}/src/vulcanSerial.cpp)
add_executable( ${PROJECT_NAME} main.cpp ${VulcanSerialSourceFiles})
target_link_libraries( ${PROJECT_NAME} pthread)

