project(CPMA)

add_library(CPMA INTERFACE)
target_include_directories(
  CPMA SYSTEM INTERFACE
  "${CMAKE_CURRENT_SOURCE_DIR}/tlx"
  "${CMAKE_CURRENT_SOURCE_DIR}/ParallelTools"
  "${CMAKE_CURRENT_SOURCE_DIR}/StructOfArrays/include"
  "${CMAKE_CURRENT_SOURCE_DIR}/parlaylib/include"
  "${CMAKE_CURRENT_SOURCE_DIR}/include"
)