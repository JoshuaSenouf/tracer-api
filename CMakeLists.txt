cmake_minimum_required(VERSION 3.12)

project(tracer-api
    VERSION 1.0
    DESCRIPTION "Public C API for the `tracer` renderer."
    HOMEPAGE_URL "https://github.com/JoshuaSenouf/tracer-api"
    LANGUAGES C
)

# Adding CMake modules
set(CMAKE_MODULE_PATH
    ${CMAKE_MODULE_PATH}
)
