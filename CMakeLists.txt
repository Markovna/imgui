cmake_minimum_required(VERSION 3.16)
project(imgui)

add_library(
        imgui
        imconfig.h
        imgui.cpp
        imgui.h
        imgui_demo.cpp
        imgui_draw.cpp
        imgui_internal.h
        imgui_widgets.cpp
        imstb_rectpack.h
        imstb_textedit.h
        imstb_truetype.h
)
target_include_directories(imgui PUBLIC ./)

