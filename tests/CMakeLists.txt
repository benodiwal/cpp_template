set(TEST_SOURCES
        test_main.cpp
        test_module.cpp
)

add_executable(runTests ${TEST_SOURCES})

target_link_libraries(runTests cpp_template)

add_test(NAME runTests COMMAND runTests)