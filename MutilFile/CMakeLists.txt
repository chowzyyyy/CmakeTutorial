cmake_minimum_required(VERSION 3.10)
project(MultiFile)

# 在当前目录查找源文件并添加进 SOURCE 源文件中
aux_source_directory(. SOURCES)


# 添加可执行文件，将源文件添加进可执行文件中
add_executable(MultiFile ${SOURCES}) 
