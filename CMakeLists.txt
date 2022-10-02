cmake_minimum_required(VERSION 3.9) #最低版本

project(helloworld VERSION 1.0) #项目名称及自定义版本号
add_executable(hello_cmake main.cpp) #添加生成可执行文件
target_include_directories(hello_cmake PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/include)#头文件