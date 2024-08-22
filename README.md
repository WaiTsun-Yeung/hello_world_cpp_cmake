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
```powershell
mkdir build;
cd build;
cmake ..;
cmake --build . --config RelWithDebInfo; 
#set(CMAKE_BUILD_TYPE ...) in CMakeLists.txt is ignored by MSVC. 
#On the other hand, --config option in cmake --build ... is ignored by GCC.

./RelWithDebInfo/hello-world.exe
```

## LICENSE

This project is licensed under the MIT License - see the
[LICENSE](LICENSE) file.