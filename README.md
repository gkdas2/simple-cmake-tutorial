# How to use cmake and organize c++ codes

1. With src and include folders, pay attention to how #include 
    considers relative position of header files in include folder

2. The CMakeLists is fairly same, except add all source code filenames from src/ folder to add executable command. First name is the executable name.

3. We will compile everything inside the build folder and store the executable "hello" in this folder. So,
- create this folder. Its name can be anything: mkdir build.
- cd build
- cmake ../
- make

The executable hello should be inside build now.

