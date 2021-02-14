# MT MWUs Dataset

This repository contains the Dataset for an evaluation study conducted on three Machine Translation (MT) systems, namely, Google Translate, DeepL and Microsoft Translate.
For the sake of this experiment 100 multiword units (MWUs) in the domain of archaeology have been selected from an Italian-English parallel corpus and automatically translated both without extra context (out-of-context – OOC) and in the context of a sentence (in-context – IC) taken from the corpus.

The dataset used in this experiment is composed of:
* 100 Italian MWUs (IT SOURCE) and their English human-translated equivalents (EN SOURCE). The average length of the 100 Italian MWU is 2.79 words. 
* the outputs of the three NMT systems considered for this experiment concerning the out-of-context (OOC) translation of the selected MWUs, namely without considering them in the context of a sentence.
* 100 Italian sentences (IT SOURCE CONTEXT) and their English human-translated equivalents (EN GOLD STANDARD CONTEXT), which provide the context of use for the 100 Italian and English MWUs selected.
* the outputs of the three NMT systems concerning the in-context (IC) translation of the selected MWUs.
