cmake_minimum_required(VERSION 3.12)

project(pcg32 LANGUAGES CXX C)

set(HEADERS pcg32.h pcg32_8.h)

install(FILES ${HEADERS} DESTINATION ${CMAKE_INSTALL_PREFIX}/include)