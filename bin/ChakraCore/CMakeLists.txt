# xplat-todo: This is a skeleton make file and not used in build yet.
# Please add this to build and fix issues.

add_library (ChakraCore
    ChakraCore.def
    ChakraCoreDLLFunc.cpp
    ConfigParserExternals.cpp
    TestHooks.cpp
    )

target_include_directories (
    ChakraCore PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})