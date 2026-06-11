cmake_minimum_required(VERSION 3.2...${CMAKE_VERSION})

project(kiran-icon-theme VERSION 2.5)

include(GNUInstallDirs)

find_package(PkgConfig REQUIRED)

install(DIRECTORY ${PROJECT_SOURCE_DIR}/Kiran ${PROJECT_SOURCE_DIR}/Summer ${PROJECT_SOURCE_DIR}/Spring
        DESTINATION ${CMAKE_INSTALL_DATADIR}/icons)

add_subdirectory(third_party)
