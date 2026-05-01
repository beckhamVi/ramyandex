cmake_minimum_required(VERSION 3.16)
project(RamyandexLauncher)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_AUTOMOC ON)

find_package(Qt6 REQUIRED COMPONENTS Core Gui Qml Quick)

qt_add_executable(launcher main.cpp)

qt_add_qml_module(launcher
    URI RamyandexLauncher
    VERSION 1.0
    QML_FILES qml/Main.qml
    RESOURCE_PREFIX /qt/qml
)

target_link_libraries(launcher PRIVATE Qt6::Core Qt6::Gui Qt6::Qml Qt6::Quick)
