***************
HACKATHON TASKS
***************

Part I and Part II are independent. Choose one taking into account that PART II is more difficult.

***************
PART I
***************

- From the file `nuclear_antigens.fasta` generate 14- amino acid long peptides (shifted by 1 position)
- Write them to a file in Fasta format. Remember to assign an ID to each of them in order to identify them later
- Search the 14-mers in the P. *falciparum* proteome (`Plasmodium_falciparum.fasta`)
- Collect, for each peptide, the best scores in a table
- Plot the best scores

***************
PART II
***************

- From the file `nuclear_antigens.fasta` generate 14- amino acid long peptides (shifted by 1 position)
- Write them to a file in Fasta format. Remember to assign an ID to each of them in order to identify them later
- Search the 14-mers in the P. *falciparum* proteome (`Plasmodium_falciparum.fasta`)
- Search the 14-mers in the Schizosaccharomyces pombe proteome (`Schizosaccharomyces_pombe.fasta`)
- Create a table peptide_ID|score_plasm|score_pombe
    set score_plasm = 0.0 if the peptide hasn't a match in the P. falciparum proteome
    set score_pombe = 0.0 if the peptide hasn't a match in the S. pombe proteome
- Create a scatter plot.

### How many peptides are unique to P. falciparum?
In other words, how many peptides have a match in the P. *falciparum* proteome and don't in the S. *pombe* proteome?
Can you easily identify them in the scatter plot?
Write them (namely their peptide_IDs) to a file.

***************
