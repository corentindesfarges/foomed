add_executable(myexec exec.cpp)

target_link_libraries(myexec LINK_PUBLIC mylib)

INSTALL( TARGETS myexec RUNTIME DESTINATION bin )
