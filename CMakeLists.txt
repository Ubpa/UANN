cmake_minimum_required(VERSION 3.14 FATAL_ERROR)

project(UANN VERSION 2.0.0)
message(STATUS "[Project] ${PROJECT_NAME}")

include(cmake/InitUCMake.cmake)
Ubpa_InitUCMake()

Ubpa_InitProject()

Ubpa_AddSubDirsRec(src)
