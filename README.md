# CHIM-MA
This program was created during a project week for the course BINP29 (Sequence analysis II) at Lund University. It's aim is to detect chimeric sequences

### Description

- *CHIMMA.py* This program will take a cleaned fasta file as input, looking for chimeric sequences and outputs one file of detected chimeric sequences
and one file of no chimeric sequences.

In the "src" folder two additional programs are found, used for validation of CHIMMA.py.

- *SequenceSimulator.py* is a program to simulate sequences, with the option to generate chimeric sequences constructed from 
the other sequences. The user can choose the minimum threshold of sequence similarity, meaning that 
no sequences will be less similar than this threshold. Other user options is also the length of the sequences, how many to sequences to generate
and if to generate chimeric sequences and how many (procent of the created sequences).

- *ComparingFiles.py* is a program that will take one input file with sequences and one input reference file with sequences.
The two files will then be compared for same ID sequences, and return how many True/False positives and negatives the input file
contains with the reference file as the positives. 


### Installation

Packages required for the python scripts:
``` python
pip install argparse
pip install sys
pip install statistics
pip install random 
```
