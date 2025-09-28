# cs50-dna
A Python program that identifies individuals by analyzing DNA sequences based on short tandem repeats (STRs). Built as part of CS50x (Introduction to Computer Science by Harvard University).

📖 Overview

The program takes as input:
	1.	A CSV database containing individuals’ names and their STR counts.
	2.	A DNA sequence file containing an unknown DNA string.

It then:
	•	Counts the longest consecutive runs of each STR in the DNA sequence.
	•	Compares those counts against the database.
	•	Identifies the individual if there is an exact match, otherwise reports No match.

Example: python dna.py databases/large.csv sequences/5.txt
→ Output: Lavender

🛠 Features
	•	Implements DNA profiling using STR pattern matching.
	•	Works with both small and large DNA databases.
	•	Uses Python string manipulation for sequence analysis.

🚀 How to Run
	1.	Run the program with a database file and DNA sequence file: python dna.py database.csv sequence.txt 
  2.	The program outputs the name of the matching individual, or No match.

📂 Files
	•	dna.py – main source code
	•	databases/ – sample CSV databases
	•	sequences/ – DNA sequence test files
	•	README.md – project documentation
