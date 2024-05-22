set(SOURCES
        main.cpp
        module/module.cpp
        module/helper.cpp
)

add_library(cpp_template_lib ${SOURCES})
add_executable(cpp_template main.cpp)