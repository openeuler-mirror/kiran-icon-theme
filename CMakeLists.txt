cmake_minimum_required(VERSION 3.2)

project(kiran-icon-theme VERSION 2.5)

include(GNUInstallDirs)

find_package(PkgConfig REQUIRED)

install(DIRECTORY ${PROJECT_SOURCE_DIR}/Kiran
        DESTINATION ${CMAKE_INSTALL_DATADIR}/icons)
