# CSV-Combiner

 ## A simple tool which combines all CSV files in a given directory and combines the values into a new output file. 
 
 Usage:
  _
  - run the .exe or .ps1 and choose the path where your files exist
  - notice the new output file
 
 Considerations:
 - The utility does not delete the source csv files 
 - the content from each file will be appended to the end of the previous file
 - the utility uses the column headings of the first(alphabetical) csv file processed in the directory you pick, so either make sure each file has the same column headings OR place a dash or underscore at the beginning of the filename you'd like to use as the heading authority. 
 --Because of this behaviour, the file can also be used as a tool to apply headings to many heading-less .csv files.
 
![image](https://user-images.githubusercontent.com/43890114/139602608-2aaebd69-b8e9-4bc2-b903-de6dc0d16bf2.png)

