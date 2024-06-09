In Windows:

First install the package manager Chocolatey in Windows by following the steps from below link:
https://chocolatey.org/install


Then
1. Install MINGW from chocolatey
choco install mingw
OR
choco upgrade mingw

2. Paste the bin path of MINGW into environment variables
C:\ProgramData\chocolatey\lib\mingw\tools\install\mingw64\bin

3. Test
g++ --version

4. GDB is installed in this directory:
C:\ProgramData\mingw64\mingw64\bin\gdb.exe

5. Create a cpp file and write the code

6. To compile the code:
g++ .\main.cpp -o .\main.exe


It contains configuration file for debugging C++. Just set a breakpoint and start debug. That's it.