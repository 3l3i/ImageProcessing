How to run
------------

To generate Makefile (uses CMake):
1. Enter project directory.
2. rm -r cmake-build-debug/*
3. cd cmake-build-debug
4. cmake ..
Note: May need to edit CMakeLists.txt in the project root directory depending on your version of CMake and environment.

To compile and run:
1. Enter cmake-build-debug.
2. make clean
3. make
4. ./ImageProcessing (image name)

/images contains on the original images to perform image processing on. Use program argument as image name. The resultant images will be outputted into /imagesNew. 

Uses the lodepng library for decoding and encoding PNG images. Also has the ability to encode into PGM formatted images.

