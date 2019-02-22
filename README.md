# Basic Text Analysis
Finding basic patterns in frames of text (counts) and visualizing results.

# Before you get started
Concepts/Software/Programming modules a user may have to read up on before getting started with this project.
- Basic understanding of python, list comprehensions, loops
- `seaborn` plotting

# Setup
**How to obtain this repository:**
```sh
git clone https://github.com/danielc92/text-analysis.git
```
**Modules/dependencies:**

- `pandas`
- `nltk`
- `seaborn`

Install the following dependences:
```sh
pip install pandas seaborn nltk
```

# Tests
- Created and tested functions `return_pairs`, `return_triples`, `return_quadruples` which can take in a string and output every combination of consequtive words. e.g 'the quick brown fox' > ['the quick', 'quick brown', 'brown fox'] using `return_pairs`
- Created and tested function to visualize a `counter.most_common()` object from `collections` module.
- Applied workflow to 'pros' and 'cons' reviews from the google employee review dataset, generating single/pair/triplet/quadruple set analysis on each category.

# Contributors
- Daniel Corcoran

# Sources
- Google Employee Reviews Dataset