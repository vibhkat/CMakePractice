#[[This is to give name to a libaray and defining the 
    files that make it
    Need to find a better way to automatically add all the files instread of adding it maually]]
add_library(
		say-bye 
		bye.h
		bye.cpp
		)

target_include_directories(say-bye PUBLIC "${CMAKE_CURRENT_SOURCE_DIR}/..")