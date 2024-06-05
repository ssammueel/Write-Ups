## stings & grep

is a useful utility that extracts and displays printable strings from binary files. 

### 1. Basic Usage

    strings filename

This command will display all the printable strings found in the specified file.

### 2. Specify Minimum String Length:
You can specify the minimum length of strings to be displayed. example, to display strings of at least 5 characters

    strings -n 5 filename

### 3. Search for Specific Strings:
search for pecific term

    strings filename | grep "search"

### 4. Output to a File:
redirect the output of strings to a file

    strings filename > output.txt

### 5. Analyzing Multiple Files:
You can use strings for more than one file

    strings file1 file2 file3

### 6.find more than one leter

    strings file | grep -E "p|c|w"
    
