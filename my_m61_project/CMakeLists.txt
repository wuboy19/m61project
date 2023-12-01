cmake_minimum_required(VERSION 3.15)

#include_directories(C:/Users/wxw/Documents/my61s_environment/bouffalo_sdk/drivers/lhal)
include(proj.conf)

find_package(bouffalo_sdk REQUIRED HINTS $ENV{BL_SDK_BASE})
#sdk_add_include_directories(./ C:/Users/wxw/Documents/my61s_environment/bouffalo_sdk/drivers/lhal)

#include_directories(C:/Users/wxw/Documents/my61s_environment/bouffalo_sdk/drivers/lhal)
sdk_set_main_file(main.c)

project(helloworld)
