cmake_minimum_required(VERSION 3.10)
project(ryu VERSION 2.0 LANGUAGES C)

add_library(ryu
        ryu/f2s.c
        ryu/d2s.c
        ryu/s2f.c
        ryu/s2d.c
        ryu/d2fixed.c
        ryu/ryu.h)

target_include_directories(ryu PUBLIC .)