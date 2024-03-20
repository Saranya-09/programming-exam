# NUCLEOTIDE ANALYSIS

Author: Saranya Guvvala

Date: [03-20-2024]

# Programming Language & Version: Python 3.8

# Dependencies
collections

# Input Files:
RNA-sequence1.fna and RNA-sequence2.fna: The Two FASTA files containing RNA sequences. These files are analyzed to reverse transcribe RNA to DNA and compute the frequency and percentage of di-nucleotides and tri-nucleotides.

# Script Description
This script is designed to analyze RNA sequences from two FASTA files, performing reverse transcription from RNA to DNA. It computes the frequencies and percentages of di-nucleotides and tri-nucleotides present in the RNA sequences. The script also identifies significant differences in the nucleotide composition between the two sequences, focusing on differences that exceed a threefold change in percentage abundance.
#Functions in the script
convert_rna_to_dna(sequence): Converts RNA sequences to DNA sequences by replacing uracil (U) with thymine (T).
compute_frequencies(seq): Calculates the percentage and frequencies of di-nucleotides and tri-nucleotides in the sequences.
load_sequence(file_path): Loads RNA sequences from FASTA files, excluding header lines.
identify_significant_differences(percent1, percent2): Identifies and reports significant differences in nucleotide percentages between two sequences, with a focus on those differences exceeding a threefold change.convert_rna_to_dna(sequence): Converts RNA sequences to DNA sequences by replacing uracil (U) with thymine (T).
compute_frequencies(seq): Calculates the absolute and percentage frequencies of di-nucleotides and tri-nucleotides in the sequences.
load_sequence(file_path): Loads RNA sequences from FASTA files, excluding header lines.
identify_significant_differences(percent1, percent2): Identifies and reports significant differences in nucleotide percentages between two sequences, with a focus on those differences exceeding a threefold change.

# Output
The script outputs the differences in di-nucleotide and tri-nucleotide percentages that exhibit a significant difference threefold between the two RNA sequences analyzed.
