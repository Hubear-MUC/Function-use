Function Use 1.0
----------------

The project to actually call the function of the previous project (f).

The file with the function was placed in a directory named "TB" (for "Tool Box") placed one directory- hierarchy layer above to try out the usage of a "library"- directory in the same project.


1  #include"f.cpp"
2  double a,b,e;
3  main()
4  {e=f(a,b);
5  }


To run the program and examine if it works:

Set a breakpoint to line 3 or 4.

Set another breakpoint a line 5.

Start the program and set the variables a and b with the two numbers the program should multiply together.

Continue the program to the breakpoint at line 5 and

finally examine the result in variable e.



Version history
---------------

Version 1.0

Initial version

