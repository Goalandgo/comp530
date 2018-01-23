cmake_minimum_required(VERSION 3.9)
project(comp530)

set(CMAKE_CXX_STANDARD 11)

add_executable(comp530
        A1/.idea/codeStyles/Project.xml
        A1/.idea/A1.iml
        A1/.idea/misc.xml
        A1/.idea/modules.xml
        A1/.idea/vcs.xml
        A1/.idea/workspace.xml
        A1/Build/SConstruct
        A1/cmake-build-debug/A1
        A1/cmake-build-debug/A1.cbp
        A1/cmake-build-debug/cmake_install.cmake
        A1/cmake-build-debug/CMakeCache.txt
        A1/cmake-build-debug/Makefile
        A1/Main/BufferMgr/headers/MyDB_BufferManager.h
        A1/Main/BufferMgr/headers/MyDB_Page.h
        A1/Main/BufferMgr/headers/MyDB_PageHandle.h
        A1/Main/BufferMgr/headers/Node.h
        A1/Main/BufferMgr/source/MyDB_BufferManager.cc
        A1/Main/BufferMgr/source/MyDB_Page.cpp
        A1/Main/BufferMgr/source/MyDB_PageHandle.cc
        A1/Main/BufferMgr/source/Node.cpp
        A1/Main/BufferTest/source/BufferQUnit.cc
        A1/Main/Catalog/headers/MyDB_Table.h
        A1/Main/Catalog/source/MyDB_Table.cc
        A1/Main/Qunit/headers/QUnit.h
        A1/CMakeLists.txt)
