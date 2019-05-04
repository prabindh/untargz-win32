# untargz-win32
Extract or List compressed (tar.gz) files on Win32

Depends on zlib

## Usage:

 Use Package Manager to install zlib-msvc14-x64 dependency in the project, version 1.2.11.7795, latest at the time of writing.
 
 Call as below, per usual main() calling conventions.
 
 int DoGZipTest(int argc, char **argv)

## To create test files, use 7-zip in 2 step process.

1. Create a .tar file (tar mode) from the folder to be archived

2. Create a .gz file (gzip mode) from the .tar file generated in step 1
 