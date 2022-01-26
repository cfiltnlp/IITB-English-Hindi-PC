# IITB-English-Hindi Parallel Corpus 

[![GitHub issues](https://img.shields.io/github/issues/cfiltnlp/IITB-English-Hindi-PC?style=flat-square)](https://github.com/cfiltnlp/IITB-English-Hindi-PC/issues)
[![GitHub forks](https://img.shields.io/github/forks/cfiltnlp/IITB-English-Hindi-PC?style=flat-square)](https://github.com/cfiltnlp/IITB-English-Hindi-PC/network)
[![GitHub stars](https://img.shields.io/github/stars/cfiltnlp/IITB-English-Hindi-PC?style=flat-square)](https://github.com/cfiltnlp/IITB-English-Hindi-PC/stargazers)
[![GitHub license](https://img.shields.io/github/license/cfiltnlp/IITB-English-Hindi-PC?style=flat-square)](https://github.com/cfiltnlp/IITB-English-Hindi-PC/blob/main/LICENSE.md)
## About
We provide a notebook which shows how to import the IITB English-Hindi Parallel Corpus from the HuggingFace datasets repository. The notebook also shows how to segment the coprus using BPE tokenization which can be used to train a English-Hindi MT System.

## Usage

You should have the 'datasets' packages installed to be able to use the :rocket: HuggingFace datasets repository. Please use the following command and install via pip:

```code
   pip install dataasets
```
In the notebook, we also provide the code to create Byte-pair encoding segmented version of this corpus.
You can choose to tokenize it the way shown in the notebook, or use any other tokenization which also supports the Hindi language.

## Other
You can find a catalogue of other English-Hindi and other Indian language parallel corpora here: [Indic NLP Catalog](https://github.com/indicnlpweb/indicnlp_catalog)
Version 3.1 - December 2021 - Added 49,400 sentence pairs to the parallel corpus.

## Cite

If you use this corpus or its derivate resources for your research, kindly cite it as follows:
Anoop Kunchukuttan, Pratik Mehta, Pushpak Bhattacharyya. The IIT Bombay English-Hindi Parallel Corpus. Language Resources and Evaluation Conference. 2018.

BiBTeX:
```latex
@inproceedings{kunchukuttan-etal-2018-iit,
    title = "The {IIT} {B}ombay {E}nglish-{H}indi Parallel Corpus",
    author = "Kunchukuttan, Anoop  and
      Mehta, Pratik  and
      Bhattacharyya, Pushpak",
    booktitle = "Proceedings of the Eleventh International Conference on Language Resources and Evaluation ({LREC} 2018)",
    month = may,
    year = "2018",
    address = "Miyazaki, Japan",
    publisher = "European Language Resources Association (ELRA)",
    url = "https://aclanthology.org/L18-1548",
}
```
