# hello-world-fortran
Using an Ubuntu Linux text editor, I followed a "hello world" tutorial at https://fortran-lang.org/learn/quickstart/hello_world

Fortran is packaged with the GNU GCC bundle.<br>
You can check your installation and version of Fortran by running:<br>
$ gfortran --version

In my hello world example, I saved the code as a .f90 file.<br>
At the Linux terminal, I compiled it by the following command:<br>
$ gfortran hello.f90 -o hello

This looks similar to what I remember of compiling C++ code at the command line.

Then the program is run by the following command:<br>
$ ./hello

Output in terminal:<br>
 Hello, World!
