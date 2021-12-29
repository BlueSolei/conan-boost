# conan-boost 

This sample projects demonstrates using conan to define boost dependency within a c++ project.

This repository can be used as a base project for all c++ development requiring boost and other third party libraries.

## install conan

```
python3 -n venv .venv
.venv\Scripts\activate.bat
pip install conan
```

## build

```
.venv\Scripts\activate.bat
mkdir build && cd build
conan install .. --build missing
cmake .. 
cmake --build .
```