set(c_options "")
if(MSVC)
  list(APPEND c_options "/wd4996")
endif()

Ubpa_AddTarget(
  MODE SHARED
  INC
    "include"
  SOURCE
    "${PROJECT_SOURCE_DIR}/include"
  DEFINE
    ANN_NO_RANDOM
    Ubpa_AsDynamic_ANN
  DEFINE_PRIVATE
    Ubpa_EXPORT_ANN
  C_OPTION
    ${c_options}
)
