# CMakeLists.txt for FunctionGemma 2B Daemon and Client

cmake_minimum_required(VERSION 3.10)

# Define project
project(FunctionGemma2B)

# Set the C++ standard
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Include directories
include_directories(include)

# Source files
set(SOURCES
    src/main.cpp
    src/daemon.cpp
    src/client.cpp
)

# Create executable for daemon
add_executable(FunctionGemma2BDaemon ${SOURCES})

# Optionally add client if it is separate
# add_executable(FunctionGemma2BClient ${CLIENT_SOURCES})

# Link libraries if needed (add your libraries here)
# target_link_libraries(FunctionGemma2BDaemon ${LIBRARIES})
