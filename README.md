# SoftwareDesignCpp

Source files for the book "Object-Oriented Software Design in C++" by Ronald Mak.

The files for each example program are zipped. All the example programs in this 
book use the 2017 version of C++, although most can also work with earler versions
of C++.

Unzip each program to compile and run. For example, the following two commands 
specify C++17 and will compile, link, and run program 2.1 in a Linux terminal 
window using the GNU C++ compiler or in a MacOS terminal window using the 
Apple Clang C++ compiler:

    g++ -std=c++17 *.cpp -o books
    ./books

The equivalent commands in a Microsoft Windows “Developer Command Prompt for VS” 
window using the Visual Studio C++ compiler:

    cl /EHs /std:c++17 *.cpp /link /out:books.exe
    books

Similar commands will compile, link, and run the other example programs.
