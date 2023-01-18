Change the directory using the cd command and place the fastq.py file on it.

To run the file, run it as

python fastq.py

In windows, you may not be able to run it using CLI. Use conda to run the command. The command is still the same.

You may change the SRA accession codes. Just add or edit the dictionary entries.

from line 9 
samples = { 
'LNCaPHypoxia8':'SRR7179527',
'PC3Normoxia1':'SRR7179536', 
'PC3Normoxia2':'SRR7179537', 
'PC3Hypoxia1':'SRR7179540',
'PC3Hypoxia2':'SRR7179541',
}

Just add the name and code in the same format.
