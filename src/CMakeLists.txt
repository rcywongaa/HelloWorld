set(SRC
    main.cpp
)

#find_package (Threads REQUIRED)

add_executable(helloworld ${SRC})
target_link_libraries(helloworld HelloLib)
