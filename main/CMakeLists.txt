project(orkan)

add_executable(${PROJECT_NAME} main.cpp)

# 需要链接的lib
target_link_libraries(${PROJECT_NAME}
        libparser
        )