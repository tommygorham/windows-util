## 1) Download Microsoft MPI 

[Download Link](https://docs.microsoft.com/en-us/message-passing-interface/microsoft-mpi?redirectedfrom=MSDN#ms-mpi-downloads)

## 2) Create a simple program, be sure to 
 
 `#include <mpi.h>`  

## 3) To Compile From CMD (Instead of Visual Studio)  

 `g++ -I"C:\Program Files (x86)\Microsoft SDKs\MPI\Include" -o myprog.exe myprog.cpp "C:\Program Files (x86)\Microsoft SDKs\MPI\Lib\x64\msmpi.lib"`

## 4) Run With The Standardized Command

 `mpiexec -n <num-of-procs> ./exe`
