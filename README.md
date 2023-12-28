# cs1b_hw01_template

This is the first assignment of the semester.  Make sure you complete this assignment timely as we will build upon this, using `make` and `cmake` in assignments 02 and 03 respectively, to automate and manage the code base minimizing compilation needs upon individual changes. 

## Assignment 01 - Introduction to C++

Write a program that takes a variable amount of scores (less than 50) and outputs the average of the scores.  Use a array of type `double` to store each score. Include a header file with your personal information, pre-processor directives, etc, as discussed in class.  

When done, your project should include the following files:  

`hw01.h` // header file with personal/assignment info and preprocessor directives;  
`hw01.cpp` // your "client" source code where function `main()` is  
`hw01.scr` // text file generated by the `script` command demostrating successful compilation and running of the program  
`hw01.tar` // package file to be submitted to canvas: `tar cf hw01.tar hw01.h hw01.cpp hw01.scr`  

Perform the following commands to generate the tar package:

`cs1stud@cs1vbox:~/cs1b/hw01$ script hw01.scr` <br/>
`cs1stud@cs1vbox:~/cs1b/hw01$ ls -l` <br/>
`cs1stud@cs1vbox:~/cs1b/hw01$ g++ hw01.cpp -o hw01` <br/>
`cs1stud@cs1vbox:~/cs1b/hw01$ ./hw01` <br/>
`Enter score: 96` <br/>
`Enter score: 81` <br/>
`Enter score: Ctl-D` <br/>
`The average is 88.5` <br/>
`cs1stud@cs1vbox:~/cs1b/hw01$ Ctl-D` <br/>
`Script done, file is hw01.scr` <br/>
`cs1stud@cs1vbox:~/cs1b/hw01$ tar cf hw01.tar hw01.h hw01.cpp hw01.scr` <br/>

Note: Do NOT include compiled binaries (ie, `hw01`) in the tar package file.


