# conan-boost 

This sample projects demonstrates using conan to define boost dependency within a c++ project.

This repository can be used as a base project for all c++ development requiring boost and other third party libraries.

## Install conan

### Windows
```
python3 -m venv .venv
.venv\Scripts\activate.bat
pip install conan
```

### Linux\Mac
```
python3 -m venv .venv
source .venv\bin\activate
pip install conan
```

## Build

```
.venv\Scripts\activate.bat
mkdir build && cd build
conan install .. --build missing
cmake .. 
cmake --build .
```
