# How to use cmake to organize c++ codes

Put all source codes (.cpp) files in src/ and all headers (.h) file in include/.

1. With src and include folders, pay attention to how #include considers relative position of the header files located in the include/ folder.

2. The CMakeLists.txt must be present. It is fairly same for any project with little modification based on your fiels. Add all source code filenames from src/ to add executable command. First name is the executable name. Then follows all the source code file names. Also make sure to add any additional compiler flags as needed.

3. We will compile everything inside the build folder and store the executable "hello" in this folder. So,
- create this folder. Its name can be anything: **mkdir build**
- change to the build folder: **cd build**
- generate makefile: **cmake ../**
- compile: **make**

The executable hello should be inside build now.

