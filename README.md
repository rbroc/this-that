# This shoe, that tiger:
### Manual affordances and the animate-inanimate distinction modulate demonstrative use

This repository stores data and code for our manuscript This shoe, that tiger: manual affordances and the animate-inanimate distinction modulate demonstrative use. Both raw data and processed data are included in the repository, as well as scripts for the preprocessing and analysis of the data. The repository has a flat structure.

Raw data are labelled with "raw" and were processed with the respective process_*.Rmd markdown.

Processed data are tsv files labelled with a two-letter ID for the language and the experiment number, e.g. DK_1.txt.

The word frequency files are tsv files starting with freq_. For English, word frequencies are extracted from the British National Corpus, whereas for Italian and Danish we used corpora from the TenTen family, 2017.

Semantic scores from original dataset from Sudre et al. (2012) for experiment 1 are located in the file exp1.txt, while semantic scores predicted via SVR for experiment two are located in the file exp2.txt. As the Sudre et al. (2012) is not owned by the authors of the present papers, it is not shared in this repository. However, the code for the SVR models trained for Experiment 2 is shared here as SVR_code.Rmd.

All the analyses reported in the paper are executable in RStudio via the AnalysisThisThat.Rmd markdown.
