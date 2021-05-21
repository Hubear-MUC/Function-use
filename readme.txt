Function Use 1.2
----------------

The project to actually call the function of the previous project (f).

The file with the function was placed in a directory named "TB" (for "Tool Box") placed one directory- hierarchy layer above to try out the usage of a "library"- directory in the same project.

1  #include"../TB/f.cpp"
2
3  double a,b,e;
4
5  main()
6  {
7    e=f(a,b);
8  }



To run the program and examine if it works:

Set a breakpoint to line 6.

Set another breakpoint at line 8.

Start the program and set the variables a and b with the two numbers the program should multiply together.

Continue the program to the breakpoint at line 6 and

finally examine the result in variable e.



Version history
---------------

Version 1.2

Redesigned the code to give it an easier structure to read and maintain.


Version 1.1

Placed the function body in a new line to make the code readable and maintainable more easy.


Version 1.0

Initial version

