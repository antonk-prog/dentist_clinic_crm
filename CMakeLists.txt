cmake_minimum_required(VERSION 3.25)
project(CLINIC_CRM)

set(CMAKE_CXX_STANDARD 20)

set(BIN_DIR "${CMAKE_CURRENT_SOURCE_DIR}/bin")


add_subdirectory(src)

install(TARGETS Clinic RUNTIME DESTINATION ${BIN_DIR})