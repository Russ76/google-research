This code supports [this preprint](https://storage.googleapis.com/brain-genomics-public/research/proteins/protnlm/uniprot_2022_04/protnlm_preprint_draft.pdf)
in which Google describes how they predicted protein names using a model called
ProtNLM for 88% of all Uncharacterized proteins (over 1 in 5 proteins in the
database) in collaboration with UniProt for UniProt's release 2022_04.

A colab demonstrating usage of the available neural network is [here](https://colab.research.google.com/github/google-research/google-research/blob/master/protnlm/protnlm_use_model_for_inference_uniprot_2022_04.ipynb).

Another [colab](https://colab.research.google.com/github/google-research/google-research/blob/master/protnlm/protnlm_evidencer_uniprot_2022_04.ipynb)
is available showing when a prediction produced by ProtNLM is
supported by a traditional bioinformatics approach (e.g. based on
alignment).
