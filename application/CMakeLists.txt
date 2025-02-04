set(EXEC_SRC
    main.cpp
)

add_executable(${EXECUTABLE} ${EXEC_SRC})

target_link_libraries(
    ${EXECUTABLE} PUBLIC ${LIBRARY}
)

