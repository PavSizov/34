cmake_minimum_required(VERSION 3.21)
project(34)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_PREFIX_PATH "E:/Qt/Qt5.5.1/5.5/mingw492_32/lib/cmake")

find_package(Qt5 COMPONENTS

        Core

        Gui

        Widgets

        REQUIRED)
add_executable(34 main.cpp)

target_link_libraries(34
        Qt5::Core

        Qt5::Gui

        Qt5::Widgets)


