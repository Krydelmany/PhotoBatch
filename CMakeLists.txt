#Versão minima requirida do CMake
cmake_minimum_required(VERSION 3.12)
#É apenas o nome do projeto, não é do executavel e nada muito importante
project(PhotoBatch)
#Dizer o nome do executavel e passar a lista de arquivo fonte que vão ser compiladas para o executavel que no caso é o PhotoBatch.cpp
add_executable(PhotoBatch "PhotoBatch.cpp")