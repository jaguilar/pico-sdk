add_executable(pico_flash_compilation_test
        pico_flash_compilation_test.c)

target_link_libraries(pico_flash_compilation_test PRIVATE pico_flash pico_stdlib)