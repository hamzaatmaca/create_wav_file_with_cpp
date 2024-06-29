# CMakeLists.txt
cmake_minimum_required(VERSION 3.10)

# Proje ismi ve versiyonu
project(WAV VERSION 1.0)

# C++ standartını belirleyin
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# İkili dosya için kaynak dosyaları ekleyin
add_executable(WAV src/main.cpp)