# 设置最低支持cmake版本
cmake_minimum_required(VERSION 3.0)
# 项目名
project(test4)
# 添加存放源文件的子目录（每个目录中需要包含CMakeLists.txt）
add_subdirectory(src/module1)
add_subdirectory(src/module2)

