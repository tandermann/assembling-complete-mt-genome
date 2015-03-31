# assembling-complete-mt-genome
This repository contains tools for an automated assembly of the complete mitochondrial DNA from Illumina NGS data.
The repositry contains a script assemble_mitochondrion.sh which automates the process of finding the target contigs, creating a summary xml file and extracting the longest fragments, which most likely represent the mitochondrial sequence. The script uses standard functions but also requires fp.py (a very helpful tool for handling and editing fasta files) to be installed (download from https://github.com/mtop/ngs/blob/master/fp.py).
You need to provide a fasta file containing contigs created from your Illumina reads (preferably created with CLC-Assembly-Cell) and a reference mitochondrial sequence from a relatively closely related organism.
