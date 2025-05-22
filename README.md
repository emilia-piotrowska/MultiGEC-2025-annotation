# MultiGEC-2025-annotation
This repository contains annotations for grammaticality and fluency for the Swedish, and part of the English, data from the MultiGEC-2025 shared task.

Both criteria were scored on a scale from 1 to 4. 

ABOUT THE FILES

The files are divided by language, one for Swedish and one for English.
For Swedish, the texts evaluated consist of the original texts from the test set of the Swedish section of the MultiGEC database, as well as the 5 participating systems in the MultiGEC-2025 shared task, and a minimally edited human reference, also available through MultiGEC.
For English, the structure is similar, but not the entire test set is used. Instead: the data consists of texts with the following indices in each file: 50-59, 150-159, 250-259, 350-359, 450-459. 

The scores of each system are separated by one line starting with a '#' sign, followed by the name of the system and the track it participated in ('min' for minimal edits, 'flu' for fluency edits), if applicable. These lines are as follows:

\#ORIGINAL
\#LATTICE
\#RUMCULL-MIN
\#RUMCULL-FLU
\#UAM-CSI-MIN
\#UAM-CSI-FLU
\#REFERENCE

Each line in the file corresponds to one text. Each line is a string with the format 'Grammaticality: {score} Fluency: {score}'
The order of scores follows the order of texts in the dataset. 
