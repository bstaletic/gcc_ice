cmake_minimum_required( VERSION 3.4 )
project( clang_flag_sanitiser CXX )
# FIXME: Coverage on appveyor
set( CMAKE_CXX_STANDARD 11 )
set( CMAKE_CXX_STANDARD_REQUIRED ON )
add_library( ice STATIC gcc/CodePoint.cpp )
