set(LIB_SRC 
    HelloWorld.cpp
)

add_library(${LIBRARY} STATIC
    ${LIB_SRC}
)

target_include_directories(${LIBRARY} PRIVATE 
    ${CMAKE_SOURCE_DIR}/include
)