cmake_minimum_required(VERSION 3.14)
project(percobaan_pertama C)

set(CMAKE_C_STANDARD 11)

LINK_DIRECTORIES("C:\\Program Files\\MySQL\\MySQL Connector C 6.1\\include")
include_directories("C:\\Program Files\\MySQL\\MySQL Connector C 6.1\\include")

add_executable(percobaan_pertama main.c)
