/**
 * Anthony Bacarella COSC 321 Programming Project #1
 * The program should:
 * 1) read a wiring list from a text file
 * 2) create an array of NAND gates that are wired according to the list
 * 3) display all possible outputs
 */

You will need to specify where your wiring list text file is located on line 46 of the Circuit class.
There is a wiring list included in the program file, but any list should work if you follow the format:

Integers only, Input Input Output. If an input should be "A", enter "9". If an input should be "B", use "10".
A gate must be created before it is designated as an output, 
so you should keep the "Output" column in logical order.

Example:

9 10 0
2 7 1
5 5 2
