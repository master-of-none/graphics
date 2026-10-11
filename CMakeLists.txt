cmake_minimum_required(VERSION 3.20)

project(Graphics LANGUAGES CXX)

add_executable(raytracer
  raytracer/main.cc
)

target_compile_features(raytracer PRIVATE cxx_std_20)
