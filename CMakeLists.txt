cmake_minimum_required(VERSION 3.10)

project(AppDev_Prelims_Working)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_TRY_COMPILE_CONFIGURATION "-D_ADI_COMPILER;__VERSIONNUM__")

add executable(admin admin.cpp)
add executable(kiosk kiosk.cpp)
add executable(monitor monitor.cpp)
add executable(staff staff.cpp)
