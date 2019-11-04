# CMake_Example
An example of how to set up your app to build with CMake


## Linux

```
cmake -H. -Bbuild
```

### Building

```
cmake --build build --clean-first
```

### Running

```
./bin/CMake_Example
```

## Windows

### Visual Studio IDE 2019

Open the Visual Studio IDE 2019, click on "Open a local folder" and select the `CMake_Example` folder.

### Building

In the Visual Studio top bar, click on `Build > Build All`

### Running

1. In the file tree, double click on the file `CMakeLists.txt` in root folder.
1. Click on `Current Document (CMakeLists.txt)` button, on the Navigation tool bar.