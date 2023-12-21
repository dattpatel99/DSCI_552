# Multi Class and Multi Label Classification Through Support Vector Machines

URL: https://archive.ics.uci.edu/dataset/406/anuran+calls+mfccs

- Summary: Acoustic features extracted from syllables of anuran (frogs) calls, including the family, the genus, and the species labels (multilabel).

1. Source: UCI Machine Learning Repository

2. Description: This dataset was used in several classifications tasks related to the challenge of anuran species recognition through their calls. It is a multilabel dataset with three columns of labels. This dataset was created segmenting 60 audio records belonging to 4 different families, 8 genus, and 10 species. Each audio corresponds to one specimen (an individual frog), the record ID is also included as an extra column. We used the spectral entropy and a binary cluster method to detect audio frames belonging to each syllable. The segmentation and feature extraction were carried out in Matlab. After the segmentation we got 7195 syllables, which became instances for train and test the classifier. These records were collected in situ under real noise conditions (the background sound). Some species are from the campus of Federal University of Amazonas, Manaus, others from Mata Atlântica, Brazil, and one of them from Córdoba, Argentina. The recordings were stored in wav format with 44.1kHz of sampling frequency and 32bit of resolution, which allows us to analyze signals up to 22kHz. From every extracted syllable 22 MFCCs were calculated by using 44 triangular filters. These coefficients were normalized between -1 ≤ MFCC ≤ 1. Mel-frequency cepstral coefficients (MFCCs) are coefficients that collectively make up an mel-frequency cepstrum (MFC). Due to each syllable has different length, every row (i) was normalized acording to MFCCs_i/(max(abs(MFCCs_i))).

3. Citation: Colonna,Juan, Nakamura,Eduardo, Cristo,Marco, and Gordo,Marcelo. (2017). Anuran Calls (MFCCs). UCI Machine Learning Repository. https://doi.org/10.24432/C5CC9H.