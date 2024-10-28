cmake_minimum_required(VERSION 3.16)

project(stack_operation_using_dynamic_memory LANGUAGES C)

add_executable(stack_operation_using_dynamic_memory main.c)

include(GNUInstallDirs)
install(TARGETS stack_operation_using_dynamic_memory
    LIBRARY DESTINATION ${CMAKE_INSTALL_LIBDIR}
    RUNTIME DESTINATION ${CMAKE_INSTALL_BINDIR}
)
