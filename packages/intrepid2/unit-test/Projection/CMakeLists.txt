INCLUDE_DIRECTORIES(${CMAKE_CURRENT_SOURCE_DIR})

IF(Kokkos_ENABLE_Serial)
  ADD_SUBDIRECTORY(Serial)
ENDIF()


