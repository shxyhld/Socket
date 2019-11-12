# CMake 最低版本号要求
cmake_minimum_required (VERSION 2.8)

# 项目名称
project (select)

# 指定生成目标
add_executable(client selectcli.c)
add_executable(server selectsrv.c)