project(parser)

add_library(lib${PROJECT_NAME})

#添加源文件和头文件
target_sources(lib${PROJECT_NAME}
        PUBLIC
        parser.h
        PRIVATE
        parser.cpp)
# 输出头文件
target_include_directories(lib${PROJECT_NAME}
        PUBLIC
        ${CMAKE_CURRENT_LIST_DIR}
        )
