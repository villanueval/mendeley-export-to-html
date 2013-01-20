mendeley-export-to-html
=======================

Python script to export papers from a specific folder in Mendeley Desktop in Linux, including the file(s), to a static HTML file. Tested in Ubuntu 12.04.

Usage:

1. First, save the papers you want to export to a folder in Mendeley Desktop.
2. Rename the file configfile.py.dist to configfile.py and add your email registered to Mendeley.
3. Run: ./exportMendeley.py
4. Select the ID of the folder with the papers.

The script creates a folder 'html' with two html files:

- index_unordered.html - With the data as it came out of the database
- index.html - With the data ordered in alphabetical order (without any checks, so there may be mistakes)

The results are saved in the format:

 Authors. Year. Title. Journal: pages. [doi] [PDF files]

Inside the 'html' folder there is a 'files' folder that holds the pdf files associated with each paper.

