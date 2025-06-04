# Corpus_Christi_data

In this repository, I am publishing data generated for my MA thesis with the BERT model XPL, which is a version of LatinBERT retrained on the *Patrologia Latina* corpus from the *Corpus Corporum* project,
kindly made available to me by Philip Roelli at the University of Zürich (https://mlat.uzh.ch/browser?path=/38).

The data is a compilation of nouns and adjectives which have possibly undergone a semantic shift under the effect of Christianity. Note that some of them are false-positive, hence these word lists need to be verified in a qualitative analysis.
Also included are two metadata files, where the document_ids belonging to the documents included in the *Patrologia Latina* and *Latinitas Antiqua* corpora can be searched for.

The files apd_lemma_PL_adj.xlsx and apd_lemma_PL_nouns.xlsx are the ones selected for the MA thesis referenced below (Lafage, 2025). They include a probability count based on a gamma distribution.

For more information about how the data was compiled and a more detailed analysis, refer to:

Lafage, D. (2025). *Corpus Christi. En korpuslingvistisk studie av latinets semantiska utveckling i kristendomens spår.* Göteborgs Universitet.

XPL can be accessed here:

https://github.com/guslafda/XPL

For information about the original LatinBERT model, visit:

https://github.com/dbamman/latin-bert
