# IITB-English-Hindi Parallel Corpus 

We provide a notebook which shows how to import the IITB English-Hindi Parallel Corpus from the HuggingFace datasets repository. The notebook also shows how to segment the coprus using BPE tokenization which can be used to train a English-Hindi MT System.
## Usage

You should have the 'datasets' packages installed to be able to use the :rocket: HuggingFace datasets repository. Please use the following command and install via pip:

```code
   pip install dataasets
```
In the notebook, we also provide the code to create Byte-pair encoding segmented version of this corpus.

You can choose to tokenize it the way shown in the notebook, or use any other tokenization which also supports the Hindi language.