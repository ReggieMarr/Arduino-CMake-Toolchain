cmake_minimum_required(VERSION 3.0.0)
# set(CMAKE_TOOLCHAIN_FILE /custom_libs/Arduino-CMake-Toolchain/Arduino-toolchain.cmake)
# set(ARDUINO_ENABLE_PACKAGE_MANAGER TRUE)
# set(ARDUINO_INSTALL_PATH "/home/user/.arduino15")
# set(ARDUINO_PACKAGE_PATH "${ARDUINO_INSTALL_PATH}/packages")

project(Examples C CXX)

add_subdirectory(01_hello_world)
add_subdirectory(02_arduino_lib)
add_subdirectory(03_portable_app)
add_subdirectory(04_multi_app)
add_subdirectory(05_auto_link)
