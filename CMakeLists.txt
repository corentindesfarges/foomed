cmake_minimum_required (VERSION 2.8.11)

project (MAIN)

set( CMAKE_INSTALL_PREFIX /usr )


add_subdirectory( lib )
add_subdirectory( bin )
