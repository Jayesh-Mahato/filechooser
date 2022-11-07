# File Chooser


File Chooser is a python program to choose files mentioned in excel file and move them into a different folder.

# Installation

Activate virtual environment, by typing the command in the directory as below:

    source venv/bin/activate

Install Dependencies:

    pip install -r requirements.txt

## Quick start

1. Add the file names in the excel file first column that you want to choose and segregate/move to a different folder.
    

2. Keep all the source files in the folder named as source.


3. Run the following command to run the program
    ```
    python3 filechooser.py
    ```

4. The files will be moved to a folder name "chosen". If there are any missing files in the list, then the names of those items will be available in a new excel file named "FileNotFound.xlsx".