README: Custom XBRL Tag Matching

**Overview**
This script processes a CSV file containing XBRL tag data and checks whether specific keywords appear within the tag names. The script utilizes Python's pandas library for data manipulation and tqdm for progress tracking.

**Author**
Daeun (Philip) Lee,
Assistant Professor of Accounting,
California Polytechnic State University

**Features**
Loads a CSV file containing XBRL tag data.
Checks if each tag name contains any of the predefined keywords.
Adds a new column to the DataFrame indicating whether a keyword match was found.
Displays the updated DataFrame with the matching results.
Saves the output to a text file for further analysis.

**Prerequisites**
Python 3.x
pandas
tqdm
Ensure the required libraries are installed using:

```pip install pandas tqdm```

**Usage**
Update the input_directory variable with the path to the folder containing the CSV file.
Make sure the CSV file is named "__________.csv" and is located in the specified directory.
Modify the keywords list if you need to check for different tag names.

**Run the script:**

```python script.py```

The script will create a new column ContainsKeyword in the DataFrame.
The output is saved to a text file named "_________.txt" in the same directory.

**Output**
The updated DataFrame with the ContainsKeyword column is displayed in the console.
The final results are saved to "________.txt" for reference.

**Notes**

Ensure the CSV file has a column named tag containing the XBRL tag names.
The script uses tqdm to show progress as it iterates through the rows.

License

This script is provided as-is for research and analysis purposes.

