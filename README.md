# Clustering_with_ANI
clustering any nucleotid sequences using ANI (Average Nucleotid Identity)  
I have build this tool for my personal research use, to fill the gap that exists in clustering tools. Indeed, most of the available programs that make clustering of sequences do not work with large sequences such as chromosomes, are not fully customisable, or are really heavy and time consuming processes.

Based on an available ANI script (https://github.com/chjp/ANI) i made a script that allows customisable clustering of any kind of nucleotid sequences, no limit regarding size and/or number of sequences. It works by comparing pairs of sequences.
This tool relies on blast, so you must have it installed on your computer.


How to use the programm ?

1. Open	Launch_ANI.sh in a text editor and modify the parameters as you wish
2. Give execution permission to the script by typing in a terminal "chmod +x	Launch_ANI.sh" or right-clicking on it, properties, permissions, make executable.
3. Double-click the program and it executes, producing two output files.

The folder "scripts" contain 4 scripts that represent the backbone of the pipeline. Any script can be run alone without any arguments to get to its help instructions. 
