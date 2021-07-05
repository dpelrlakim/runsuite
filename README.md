# runsuite (for I/O testing)

This program takes in the text file containing names of file stems and the executable to automate input/output testing.

Takes an executable and a series of `.args`, `.in`, and `.out` files, runs the executable with inputs from all the `.in` files and arguments from the `out` files, and compares to the outputs specified in the `.out` files. 

Corresponding `.arg`, `.in`, and `.out` files should share the same name (except for the file extension, of course), and their names should be specified in a text file, which is the only file passed to this runsuite program.

Prints the arguments passed, passed input, expected output and actual output.
