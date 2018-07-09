# Technical requirements
## Operating system and architectures
Due the fact that students are often programming on their personal machine, it is required that the framework is use-able from Windows with Visual Studio and MacOS with Xcode. In production it will run in GNU/Linux in combination with the GNU C++ Compiler.
To make sure the software is easily ported to other architectures, the software must be able to run on a Raspberry Pi 3B+ for future student projects.
The following versions must be supported in the framework:

1. Windows 10 (x86_64) with Visual studio 2017
2. MacOS High Sierra (x86_64) with Xcode 8
3. CentOS (x86_64)with G++ 4.8
4. Raspbian(ARM x64) with g++ 6.3

## Programming languages and tools:
Most students will have no or little experience with programming in C++, therefore its recommended that the framework will have a standalone version in Python. Allowing students to focus on the logic of an algorithm. After this the algorithms and  I/O will be ported to C++, as it is often use in scientific communities. Due the new threading capabilities C++14 is preferred.
The framework should be implemented in:
1. Python3.6 and later
2. C++14 and late

### GPU and kernel programming
Since some of the algorithms can be done in parallel, it is recommended that these algorithms will be done one the GPU. The following frameworks are available:

1. OpenCL
2. CUDA

The framework must take in account that not all the development machines have a dedicated GPU. The software must still be usable.

[Back to table of contents](./readme.md)