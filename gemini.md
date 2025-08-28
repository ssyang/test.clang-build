# clang build system test

## env
- clang
    + version 18.1.8
    + C:\tools\clang+llvm-18.1.8-x86_64-pc-windows-msvc\bin
- llvm
- cmake
    + version 4.1.0
- ninja
    + version 1.12.1


## directory 
- share : the root of shared source, header files.
    + share/private : all shared my source , header files.
    + shred/public : 3'th part open source files.
    
- project : the root of all sub project of this solution.
    + project/example1 :  the sub project root.("example1" is example name)

- build : all builed files
    + build/win/x86/debug : Windows 32 bits debug build.
    + build/win/x86/release : Windows 32 bits release build.
    + build/win/x64/debug : Windows 64 bits debug build.
    + build/win/x64/release : Windows 64 bits release build.
    + build/debian/debug : debian, ubuntu 64 bits debug build.
    + build/debian/release : debian, ubuntu 64 bits release build.