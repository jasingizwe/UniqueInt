Project Overview

The Unique Integers Extraction project is designed to read a list of integers from an input file, identify unique integers, and generate an output file containing these unique integers sorted in increasing order. This project demonstrates skills in file handling, data processing, and algorithm implementation without using built-in libraries for sorting or lists, ensuring efficient and custom handling of data.

Key Features
Input Handling:

Reads integers from an input file where each integer is on a separate line.
Handles various input anomalies such as extra whitespaces, empty lines, lines with non-integer values, and lines with multiple integers.
Data Processing:

Utilizes a boolean array to efficiently track integers within the range of -1023 to 1023.
Filters out duplicate integers and maintains a record of unique integers encountered in the input file.
Output Generation:

Writes the list of unique integers to an output file in sorted order.
Ensures that each unique integer is printed on a new line.
Efficiency:

Custom handling of data without relying on standard libraries for sorting and list operations.
Optimized for memory and runtime efficiency.

## Usage
1. Ensure your input text files are placed in the `inputs` directory.
2. Run the script:

```bash
python3 processor.py
```

The script will read each `.txt` file in the `inputs` directory, process the integers, and save the results in the `results` directory with `_results.txt` appended to the original filename.

### Main Execution
- Sets the input and output folder paths.
- Creates an instance of `UniqueInt`.
- Processes each `.txt` file in the input folder and writes the result to the output folder.
- Logs the processing time for each file.


