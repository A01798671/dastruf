cmake_minimum_required(VERSION 3.30.5)
project(Dastruf)
set (CMAKE_CXX_STANDARD 17)


include_directories(${PROJECT_SOURCE_DIR}/include)

set(SOURCES
    src/main.cpp
    src/dastruf.cpp
    src/token.cpp
    src/lexer.cpp
)


add_executable(${CMAKE_PROJECT_NAME} ${SOURCES})