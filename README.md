# Dependency Parser
This project consists in the implementation of a dependency parser, which is a system - widely used in Natural Language Processing - that is supposed to analyze the dependency relations among words in a sentence (note that in this specific case, we not going to explicit the type of grammatical relation between the words) mapping a sentence to a dependency tree.

The dataset used is Universal Depencencies English LinES.

Specifically, we have developed the Arc Eager system (which you can get more into detail about here: https://aclanthology.org/W03-3017.pdf) using two different approaches:
- using a BiLSTM network
- using BERT

to embed the words of the sentences.
