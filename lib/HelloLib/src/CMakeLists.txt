set(SRC
    print_hello.cpp
)

add_library(HelloLib ${SRC})
target_include_directories(HelloLib PUBLIC ${PROJECT_SOURCE_DIR}/include)
