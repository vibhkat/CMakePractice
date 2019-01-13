#[[ This is giving name to the exe which can be used later 
    for linking the libraries ]]
add_executable(hello-dir main.cpp)

#[[ Linking the libraries to the exe]]
target_link_libraries(hello-dir PRIVATE say-hello)

