add_library(rxi_microtar STATIC ${CMAKE_CURRENT_SOURCE_DIR}/src/microtar.c)
target_include_directories(rxi_microtar PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/include/)

