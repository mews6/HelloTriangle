cmake_minimum_required (VERSION 3.10)

project(HelloTriangle CXX)

set(SOURCE
    src/HelloTriangle.cpp
)

set(INCLUDE
    src/HelloTriangle.hpp
)

set(SHADERS)
set(ASSETS)

add_sample_app("Tutorial01_HelloTriangle" "DiligentSamples/Tutorials" "${SOURCE}" "${INCLUDE}" "${SHADERS}" "${ASSETS}")