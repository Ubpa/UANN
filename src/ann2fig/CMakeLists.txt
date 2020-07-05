Ubpa_GetTargetName(ann "${PROJECT_SOURCE_DIR}/src/ann")
Ubpa_AddTarget(
  TEST
  MODE EXE
  LIB ${ann}
)
