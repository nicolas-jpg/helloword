# 指定运行此配置文件所需的CMake 的最低版本
cmake_minimum_required(VERSION 2.8)

# 指定项目的名称，一般和项目的文件夹名称对应。
project(Test0)

# 指定生成目标。将名为test1.c的源文件编译成一个名称为test.1的可执行文件
add_executable(test1 test1.c)
