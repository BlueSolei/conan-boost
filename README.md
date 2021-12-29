# conan-boost 

This sample projects demonstrates using conan to define boost dependency within a c++ project.

This repository can be used as a base project for all c++ development requiring boost and other third party libraries.

## Install conan
The first 2 lines are to install conan in python virtual environemnt.  
You can install conan globaly.  
Global inatallation is just `pip install conan`, and no need for activation before build.

### Windows
```
python3 -m venv .venv
.venv\Scripts\activate.bat
pip install conan
```

### Linux\Mac
```
python3 -m venv .venv
source .venv/bin/activate
pip install conan
```

## Build

### Windows
```
.venv\Scripts\activate.bat
mkdir build && cd build
conan install .. --build missing
cmake .. 
cmake --build .
```

### Linux\Mac
```
source .venv/bin/activate
mkdir build && cd build
conan install .. --build missing
cmake .. 
cmake --build .
```
