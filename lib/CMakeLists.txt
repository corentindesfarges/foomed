add_library(mylib SHARED lib.cpp)

target_include_directories(mylib PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})

INSTALL( TARGETS mylib LIBRARY DESTINATION lib/corentin )
