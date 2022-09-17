# chitosan

*conda activate mols_test

Iron:
molsimplify -lig "COC1OC(CO)C(OC)C(O)C1N" -ligocc 3 -smicat 12,14 -core iron -geometry oct -coord 6 -oxstate III -spin 6

Cobalt:
molsimplify -lig "NC1COC(CO)C(OC2OC(CO)C(OC3OC(CO)C(OC4C(N)C(O)COC4CO)C(O)C3N)C(O)C2N)C1O" -ligocc 1 -smicat 26,28,39,41 -core cobalt -geometry td -coord 4 -oxstate II -spin 4
