#[[This is to give name to a libaray and defining the 
	files that make it]]
add_library(
		say-hello 
		hello.h
		hello.cpp
		)

target_include_directories(say-hello PUBLIC "${CMAKE_CURRENT_SOURCE_DIR}/..")
