# dl-bstring

Package of the better string (bstring) replacement for the standard C string library. 

## Description ##

The Better String Library is an abstraction of a string data type which is superior to the C library char buffer string type, or C++'s `std::string`. Among the features achieved are:

* Substantial mitigation of buffer overflow/overrun problems and other failures that result from erroneous usage of the common C string library functions
* Significantly simplified string manipulation
* High performance interoperability with other source/libraries which expect `\0` terminated char buffers
* Improved overall performance of common string operations
* Functional equivalency with other more modern languages

The library is totally stand alone, portable (known to work with gcc/g++, MSVC++, Intel C++, WATCOM C/C++, Turbo C, Borland C++, IBM's native CC compiler on Windows, Linux and Mac OS X), high performance, easy to use and is not part of some other collection of data structures. Even the file I/O functions are totally abstracted (so that other stream-like mechanisms, like sockets, can be used.) Nevertheless, it is adequate as a complete replacement of the C string library for string manipulation in any C program.
The library includes a robust C++ wrapper that uses overloaded operators, rich constructors, exceptions, stream I/O and STL to make the CBString struct a natural and powerful string abstraction with more functionality and higher performance than std::string.

Bstrlib is stable, well tested and suitable for any software production environment.

## License

Copyright (c) 2002-2008 Paul Hsieh
All rights reserved.

Redistribution and use in source and binary forms, with or without 
modification, are permitted provided that the following conditions are
met:

*  Redistributions of source code must retain the above copyright notice, 
    this list of conditions and the following disclaimer. 

*  Redistributions in binary form must reproduce the above copyright notice, 
    this list of conditions and the following disclaimer in the documentation 
    and/or other materials provided with the distribution. 

* Neither the name of bstrlib nor the names of its contributors may be used 
    to endorse or promote products derived from this software without 
    specific prior written permission. 

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" 
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE 
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE 
ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE 
LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR 
CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF 
SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS 
INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN 
CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) 
ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE 
POSSIBILITY OF SUCH DAMAGE.

