# README

## Author
Matilde Rinaudo

## Directory Structure

assignment1                    -- Root folder
│
├── 1_Zipf's Law/              -- Task 1
│   ├── corpus1.ipynb
│   ├── corpus2.ipynb
│   └── corpus3.ipynb
│
├── 2_Random Text Generation/  -- Task 2
│   ├── ngram.py               -- Python class for training n-gram models provided by the course instructor
│   └── random.ipynb
│
├── 3_Statistical Dependence/  -- Task 3
│   └── pmi.ipynb
│
└── README.md

## Versions
Python: 3.13.5
matplotlib: 3.11.2
nltk: 3.10.4
datasets: 5.1.0


## Runtime
All notebooks execute in a few seconds on my machine. No individual cell takes longer than approximately 10 seconds.

## External Material
For Task 1 (Zipf's Law), an additional analysis was conducted on all corpora to investigate the effects of two different tokenization techniques on the observed frequency distributions.

In particular, apostrophes can be very problematic when dealing with this kind of tasks. This is not only the case in English, where they occur in possessive constructions (Saxon genitive) and contracted forms, but also in Turkish, where they are used to separate proper nouns from grammatical suffixes. 

For this reasons, two tokenization strategies were compared:
1. apostrophes preserved as part of a token;
2. apostrophes treated as token boundaries.
Separate frequency distributions and Zipf plots were then generated for both approaches, and an additional comparison plot too. 

This analysis was included to investigate the effect of tokenization choices on the observed Zipfian distributions. The comparison was particularly relevant for Turkish, whose agglutinative morphology makes different treatments of apostrophes linguistically relevant.