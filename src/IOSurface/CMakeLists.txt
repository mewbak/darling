project(IOSurface)

set(DYLIB_COMPAT_VERSION "1.0.0")
set(DYLIB_CURRENT_VERSION "1.0.0")

add_framework(IOSurface
    FAT
    CURRENT_VERSION
    VERSION "A"

    SOURCES
        src/IOSurface.m
        src/IOSurface.m

    DEPENDENCIES
        system
        objc
        Foundation
)
