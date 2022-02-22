# Identify_B.anthracis

A computational tool for identification of Bacillus anthracis detection using nucleotide sequencing data. 

Identify_B. anthracis is a tool based python that employs a combination of * in silico * the 9 specific tags of Bacillus anthracis to rapidly identify * B. anthracis* isolates using nucleotide sequencing data. 

Users do not need to write code. 

Users imports the genome of the sample to be tested into the * test_data_Bcgroup * folder, regardless of whether it is assembled or not, and runs the * IdentifyBA_from_dir_with_eProbe9_with_judge * code to complete the analysis. 

The analysis results are displayed in the current folder, "Result_identify_BA.txt". 

The identification result is determined based on whether the specific tags of  Bacillus anthracis are searched. 

The more tags are searched, the more reliable the target sample is positive. 

The * test_data_Bcgroup * folder contains test data.
