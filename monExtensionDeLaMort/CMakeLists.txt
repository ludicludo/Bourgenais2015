cmake_minimum_required(VERSION 2.8.9)

project(monExtensionDeLaMort)

#-----------------------------------------------------------------------------
# Extension meta-information
set(EXTENSION_HOMEPAGE "http://www.example.com/Slicer/Extensions/monExtensionDeLaMort")
set(EXTENSION_CATEGORY "Examples")
set(EXTENSION_CONTRIBUTORS "moi moche et méchant (AnyWare Corp.), un mignon")
set(EXTENSION_DESCRIPTION "montrons de quoi on est capable!	")
set(EXTENSION_ICONURL "http://www.example.com/Slicer/Extensions/monExtensionDeLaMort.png")
set(EXTENSION_SCREENSHOTURLS "http://www.example.com/Slicer/Extensions/monExtensionDeLaMort/Screenshots/1.png")

#-----------------------------------------------------------------------------
# Extension dependencies
find_package(Slicer REQUIRED)
include(${Slicer_USE_FILE})

#-----------------------------------------------------------------------------
# Extension modules
add_subdirectory(moduleUn)
## NEXT_MODULE

#-----------------------------------------------------------------------------
include(${Slicer_EXTENSION_CPACK})
