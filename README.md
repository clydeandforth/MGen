# MGen
Commands used for publication

The command list file shows the input commands used for orthofinder, interproscan and kinfin

The work_post_kinfin.txt file shows the commands used after the command list file to process results of orthofinder and kinfin. Here Diamond Blastp is used, as is the fasta parser faSomeRecords from bioconductor which is included in the MGen directory.

There is an R markdown script which takes graphml files and csv files in the input_files directory as input and when knitted creates all the plots in the manuscipt.

