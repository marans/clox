cmake_minimum_required (VERSION 2.6)
project (Clox)
set(CMAKE_EXPORT_COMPILE_COMMANDS ON)
set(SOURCE_FILES
    src/chunk.c
    src/compiler.c
    src/debug.c
    src/memory.c
    src/object.c
    src/scanner.c
    src/table.c
    src/value.c
    src/vm.c
    src/main.c)
  add_executable(clox ${SOURCE_FILES})
