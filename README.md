# Grambook2vec

This repository contains code and generated embeddings for running the main experiments covered in thesis "Exploring Language Descriptions through Vector Space Models".
A significant portion of the code was inspired by the research and methodologies presented in 
1) Kohlmeyer, Lasse, Tim Repke, and Ralf Krestel (2022). “Novel Views on Novels: Embedding Multiple Facets of Long Texts”. In: {IEEE/WIC/ACM} International Conference
on Web Intelligence and Intelligent Agent Technology. WI–IAT ’21. Melbourne, VIC, Australia: Association for Computing Machinery, pp. 670–675. isbn: 9781450391153.
doi: 10.1145/3486622.3494006. url: https://doi.org/10.1145/3486622.3494006.
2) Sannigrahi, Sonal, Josef van Genabith, and Cristina España-Bonet (2023). “Are the Best Multilingual Document Embeddings simply Based on Sentence Embeddings?” In:
Findings of the Association for Computational Linguistics: EACL 2023. Ed. by Andreas Vlachos and Isabelle Augenstein. Dubrovnik, Croatia: Association for Computational
Linguistics, May 2023, pp. 2306–2316. doi: 10.18653/v1/2023.findings-eacl.174. url: https://aclanthology.org/2023.findings-eacl.174.


##DATA:
Due to the copyright reasons the original data for the research can not be published. We used a portion of restricted subset od DReaM corpus, which is a collection of books describing 484 languages from 26 different families + 6 isolates in text formate (typically OCR grammar descriptions).

All methods are written in jupyter notebook and adopted for the use in Google colab.

[Exploring Language Descriptions through Vector Space Models]()
You may use the notebook 
- to create facets dictionaries
- to vectorize lengthy text documents using BoW, TF-IDF, doc2vec and sentence BERT applying various segmentation strategies: truncation, sentence chunking and facets-based approach.
- to analyze the obtained embeddings whith our special evaluation pipeline including justaposing them with (not only, but mainly ) genetic language distances of the described languages.

