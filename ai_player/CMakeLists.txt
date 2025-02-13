# CMakeList.txt : CMake project for ai_player, include source and define
# project specific logic here.
#

# Add source to this project's executable.
add_executable (ai_player "ai_player.cpp" "ai_player.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET ai_player PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
