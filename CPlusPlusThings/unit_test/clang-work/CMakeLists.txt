#------生成编译文件
cmake_minimum_required(VERSION 2.6)
project(main)
set(SRC_LIST main.c)
add_executable(main ${SRC_LIST}) #生成可执行文件(.exe)
#---执行命令------
# cmake -G "MinGW Makefiles" . #构建Makefile文件