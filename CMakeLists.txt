cmake_minimum_required(VERSION 3.0)

project(TextEditor)

include_directories(${PROJECT_SOURCE_DIR}/headers)

add_executable(${PROJECT_NAME} main.c editor.c terminal.c utils.c)