# Hello World CPP CMake

## Introduction
A cross-platform hello-world application created with cpp and cmake, with optional gprof profiling for Linux systems.

## Dependencies
N/A

## Build (Linux)
```bash
mkdir build
cd build
cmake ..
make
```

## Run (Linux)
```bash
./build/hello-world
```

## Profiling (Linux)
```bash
./build/hello-world #the executable must be run once first.
gprof ./build/hello-world
```

## Build and Run (Windows)
Open this folder with Visual Studio, then build and execute like any other Visual Studio project.