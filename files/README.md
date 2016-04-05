# Files

Implment and compose unit tests for each of these file operations:

## Basic 

* Read and print stat data structure of a file specified as a cli argument
* Read and print a list of files in a directory specified as a cli argument
* Open, read, and print the contents file specified as a cli argument (see unix cat command)
* Open, read, and print in hexadecimal the contents of a binary file as specified as a cli argument
* Accept input on standard input, write that input to a file specified as a cli argument
* Accept input on standard input, append that input to a file specified as a cli argument
* Open a file specificed as a cli argument, read and print any new lines written to the file (see unix tail command)

## Complex

* Seek 
  * Open a file as specified as a cli argument
  * Seek to first position starting with alpha-numeric character specified as second argument
  * Print file data until newline or end of file
* Large file
  * Open a file (larger than systems memory) as specified as a cli argument
  * Recieve max bytes to print as an integer as a specified as a second cli argument (0 for entire file)
  * Print file contents 256 bytes at a time until max bytes is reached
* In place file sort
  * Given a 1 gigabyte binary file of random 32 bit integers (aprox 536 million integers)
  * Sort the file in place at a O(n log n) efficiency 
  * Only read 64 bits of data from the file at a time



