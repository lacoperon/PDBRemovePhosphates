# 5' Phosphate Removing Script

## Motivation

This script removes the 5' phosphates from nucleotide chains from within a PDB
file. It requires that there are `TER` lines at the end of every chain, because
it uses this information to find out which phosphates are at the 5' end of a
chain.

## Usage

The script is pretty simple to use. Example:
`python remove_5_prime_phosphates.py [PDB_File_Name]`.

Additionally, you can add any number of PDB files as arguments. Example:
`python remove_5_prime_phosphates.py [PDB_File_1] [PDB_File_2] ...`
