add_subdirectory(third_party/googletest)

set(TEST_SOURCES
        test_main.cpp
        test_module.cpp
)

add_executable(runTests ${TEST_SOURCES})

target_link_libraries(runTests PRIVATE gtest gtest_main cpp_template_lib)

add_test(NAME runTests COMMAND runTests)