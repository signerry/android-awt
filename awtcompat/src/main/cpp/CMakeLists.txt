cmake_minimum_required(VERSION 3.4.1)

add_library( # Specifies the name of the library.
             awtcompat-native-components

             # Sets the library as a shared library.
             SHARED

             # Provides a relative path to your source file(s).
             awtcompat_native_components.c )

include_directories(headers/)