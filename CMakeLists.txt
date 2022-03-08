cmake_minimum_required(VERSION 3.20)
project(Proj_Matt)

#find_package(Qt5Widgets REQUIRED)

#DCMAKE_PREFIX_PATH(/usr/local/Cellar/qt5/5.3.1/)
set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
#set(CMAKE_AUTOMOC ON)
#target_link_libraries(myqtproject Qt5::Widgets)
#find_package(Qt5 COMPONENTS Widgets REQUIRED)
add_executable(Proj_Matt main.cpp)
