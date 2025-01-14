## Chapter 18: Listen to Mummy!

### Contents

 - `Mother speech.ipynb`: This notebook contains the code of the experiments described in the chapter.
 - `Parse all speeches.ipynb`: The code used to download and parse the text of all speeches in the DICES corpus (for which texts exist in Perseus). This code will re-write the file `data/merged.csv`.
 - `data/changed_loci.txt`: Alterations to selected loci necessary to align DICES records with Perseus texts in cases where DICES and Perseus draw on different editions.
 - `data/merged.csv`: A pre-calculated list of tagged tokens, comprising all the speeches in DICES for which texts exist in Perseus. Used by `Mother speech.ipynb`.
 - `data/mother_diction.csv`: A list of hand-selected lemmata used to classify samples.
 - `data/mother-child.csv`: Comprehensive list of speaker-addressee pairs determined to be mother and child.
 - `data/supp_mother_speeches.txt`: Text of six speeches not included in the Perseus Digital Library.

### Note

Parsing and tagging the text of all the speeches requires significantly more resources than running the mother-speech classification experiments. If you just want to replicate the experiments, run the "Mother speech" notebook alone, making use of the pre-tagged tokens included in the "data" folder. If you want to reproduce the data set from scratch, run "Parse all speeches" first.
