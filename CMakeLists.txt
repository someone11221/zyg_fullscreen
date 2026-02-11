# CMakeLists.txt for LineageOS 21

cmake_minimum_required(VERSION 3.10)

project(zyg_fullscreen)

# Add build configuration for LineageOS 21
set(ANDROID_ABI arm64-v8a)
set(ANDROID_PLATFORM android-21)
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(zyg_fullscreen main.cpp) # Specify the source files here
