
cmake_minimum_required(VERSION 3.15)
project(MonProjet VERSION 1.0 LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Vos sources (adapter si nécessaire)
add_executable(mon_executable
  src/main.cpp
)

enable_testing()
add_test(NAME test_mon_exe COMMAND mon_executable)
