cmake_minimum_required(VERSION 3.16...4.4)

project(
  Mage
  VERSION 1.0
  LANGUAGES CXX)

# Docs will be added here later.

# Bring in external libraries.
add_subdirectory(extern)

add_subdirectory(src)

add_subdirectory(apps)

# Tests will be added here later.