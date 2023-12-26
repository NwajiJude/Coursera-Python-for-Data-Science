# Multi-FASTA Sequence Analysis

This Python script performs various analyses on DNA sequences in a multi-FASTA file. It utilizes Biopython for sequence processing and provides answers to specific questions related to sequence lengths, ORFs (Open Reading Frames), and repeat occurrences.

## Features

- Count the number of records in a multi-FASTA file.
- Determine the length of the longest and shortest sequences.
- Find ORFs and analyze their lengths.
- Identify the most frequently occurring repeats of specified lengths.
- Answer specific questions about sequences and repeats.

## Requirements

- Python 3.x
- Biopython library (`pip install biopython`)

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/NwajiJude/Coursera-Python-for-Data-Science

Questions Answered
1. Number of Records:
    How many records are in the file?
2. Sequence Lengths:
    What are the lengths of the sequences in the file?
    What is the longest sequence?
    What is the shortest sequence?
3. ORF Analysis:
    Identify all ORFs present in each sequence.
    What is the length of the longest ORF in reading frame 2?
    What is the starting position of the longest ORF in reading frame 3?
    What is the length of the longest ORF in any forward reading frame?
    What is the length of the longest forward ORF in a specific sequence?
4. Repeat Analysis:
    Find the most frequently occurring repeat of length 6 and its occurrences.
    Find all repeats of length 12 and count the different sequences.
    Which one of the provided repeats of length 7 has the maximum number of occurrences?
   
License
This project is licensed under the MIT License.
