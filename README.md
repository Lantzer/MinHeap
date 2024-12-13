# Min-Heap Processor
`Created By: Preston Lantzer`

Takes `.txt` file, with all integers on seperate lines, as input, 

Requirements
Java Development Kit (JDK): Ensure javac and java commands are available.
Input File: A .txt file with integers, one integer per line.

How to Compile and Run
Compile the Program:
javac Richest.java

Run the Program:
Provide the input file as an argument:
`java MinHeap data.txt`
Replace `data.txt` with the path to your input file.

Input File Format
The input file should contain one integer per line. For example:
`12  
45  
7  
89  
123`

Output is a file created `MinHeap.Results.txt`
Example Output (MinHeap.Results.txt):
`987654  
54321  
12345  
1234  
456`  

Notes
The program assumes the input file contains at least 10,000 integers.
If the file has fewer integers, the program processes all available values.

Error Handling
The program throws an error if the input file is not found or if the input contains invalid data.

Future Plans
Allow input of any formatted numbers, whether separated by space, comma, or line.
