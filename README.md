# 50.003-Campaign

# Description: 
Consider a CSV file that stores a list of records (e.g., records of bank accounts).
You are required to write a software program that reads two such CSV files, compares records
stored in these CSV files row by row against a unique combination and records all mismatches
as exceptions. Finally, the software program generates another csv file listing the exceptions.


# Getting Started (Installation)
All that is required is a Java compiler, you can install one here https://www.oracle.com/java/technologies/downloads/.

# Running the script to obtain the CSV file
To utilize the Main file, enter 2 files into the arguements pertaining to the absolute path of the file. The output of the file will show the mismatched lines and will output a file titled "mismatch.csv".

The command line terminal command to run is "java App.java sample_file_1.csv sample_file_3.csv"

Alternatively, you can edit line 20 and line 31, "args[0]" and "args[1]" to the absolute path of your desired file.

# JUnit Testing
This project uses JUnit5 and VSCode to run. Simply download the extension for testing and press the "play" button to run the test cases.
