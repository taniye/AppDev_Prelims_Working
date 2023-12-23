cmake_minimum_required(VERSION 3.10)

project(AppDev_Prelims_Working)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_TRY_COMPILE_CONFIGURATION "-D_ADI_COMPILER;__VERSIONNUM__")

add_executable(admin admin.cpp)
add_executable(kiosk kiosk.cpp)
add_executable(monitor monitor.cpp)
add_executable(staff staff.cpp)
