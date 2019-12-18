add_library(map_manager SHARED f_map_manager.cpp)

target_include_directories(map_manager PUBLIC ${PROJECT_SOURCE_DIR}/include)
install(TARGETS map_manager DESTINATION lib)
