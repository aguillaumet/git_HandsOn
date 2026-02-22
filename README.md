# seqClass.py

A Python script to classify DNA and RNA sequences.

## Usage
```bash
python seqClass.py -s SEQUENCE [-m MOTIF]

## Examples
```bash
python seqClass.py -s AGTG
# The sequence is DNA

python seqClass.py -s ACGUA
# The sequence is RNA

python seqClass.py -s actg -m tg
# The sequence is DNA
# Motif search enabled: looking for motif "TG" in sequence "ACTG"... FOUND
