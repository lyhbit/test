add_library(hello libHelloSLAM.cpp)


add_executable(useHello useHello.cpp)

target_link_libraries(useHello hello_shared)
