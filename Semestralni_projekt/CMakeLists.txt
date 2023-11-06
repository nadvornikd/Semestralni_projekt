# CMakeList.txt : CMake project for Semestralni_projekt, include source and define
# project specific logic here.
#

# Add source to this project's executable.
add_executable (Semestralni_projekt "Semestralni_projekt.cpp" "Semestralni_projekt.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET Semestralni_projekt PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
