cmake_minimum_required (VERSION 3.13)

# common solution for multiple independent projects
project (occt-hello)

# Set OpenCASCADE installation directory
set (OpenCASCADE_DIR "/home/skf/occt-install/lib/cmake/opencascade" CACHE PATH "Path to OpenCASCADE CMake config")

add_subdirectory (occt-ais-hello)
add_subdirectory (occt-ais-object)
add_subdirectory (occt-ais-offscreen)
# add_subdirectory (occt-draw-plugin)  # Requires OCCT Draw module (needs Tcl/Tk dev headers)
add_subdirectory (occt-xcaf-shape)
