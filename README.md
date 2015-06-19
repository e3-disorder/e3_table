# e3_table

This repository contains a spreadsheet dataset of known human and
yeast E3 protein ligases, each annotated with position specific
disorder and Anchor binding score predictions. The main goal of the
data was to find human equivalents of the San1 protein occurring in
yeast, which was recently found to have the ability to recognize
disordered substrates directly, without relying on a chaperone
protein. The disorder and anchor features are used to define a San1
similarity score, and the spreadsheets make it possible to sort the
entries by this score - and to recalculate San1 similarity scores for
different parameters settings. This repository contains two versions
of a spreadsheet: the large file contains all data for each individual
protein, and supports recalculation of scores with different
parameters. The second file contains only the overview page, allowing
to sort candidates based on the different score columns, but without
the ability to recalculate the scores. This latter version is
considerably faster and more convenient to work with.






