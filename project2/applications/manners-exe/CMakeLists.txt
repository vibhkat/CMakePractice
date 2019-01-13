#[[ This is giving name to the exe which can be used later 
    for linking the libraries ]]
add_executable(manners-exe main.cpp)

#[[ Linking the libraries to the exe]]
target_link_libraries(manners-exe PRIVATE say-hello)
target_link_libraries(manners-exe PRIVATE say-bye)

