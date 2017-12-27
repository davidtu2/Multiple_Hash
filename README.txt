Name: David Tu
E-Mail: david.tu2@csu.fullerton.edu

Programming Language Used: C++

How to Execute the Program:
Pre-Requisite(s): The program has been compiled by typing "make" in Linux
1. In Linux, type "./skel file.txt" to execute the program
2. The program will output the hash values for various hashing mechanisms for file.txt

Was Extra Credit Implemented? No

Special Notes: I was having issues with the compilation of the program due to the parameter type requirements in the popen() and write() functions.
However, I was able to fix them by using c_str() function to convert the passed arguments, "cmdLine" and "fileName" into strings