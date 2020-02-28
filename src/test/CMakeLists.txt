Ubpa_GetTargetName(ann "${CMAKE_CURRENT_SOURCE_DIR}/../ann")
add_definitions(-DANN_NO_RANDOM)
Ubpa_AddTarget(MODE "EXE" LIBS ${ann})
