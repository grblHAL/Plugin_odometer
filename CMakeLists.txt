add_library(odometer INTERFACE)

target_sources(odometer INTERFACE
 ${CMAKE_CURRENT_LIST_DIR}/odometer.c
)

target_include_directories(odometer INTERFACE ${CMAKE_CURRENT_LIST_DIR})
