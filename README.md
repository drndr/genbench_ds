# GenCodeSearchNet: A Benchmark Test Suite for Evaluating Generalization in Programming Language Understanding

This repository contains data and code to reproduce the results in our paper 'GenCodeSearchNet: A Benchmark Test Suite for Evaluating Generalization in Programming Language Understanding' which was honored with the Best Paper Award at the GenBench workshop 2023 (co-located with EMNLP). 

Preprint link: https://arxiv.org/abs/2311.09707

The paper introduces a new benchmark test suite to evaluate programming language understanding generalization in language models and is included in the GenBench Collaborative Benchmarking Task (CBT) 2023. As part of the test suite we also include the newly created StatCodeSearch dataset, which includes 1070 code-comment pairs from social science research code written in R.

Link to the CBT repository: https://github.com/GenBench/genbench_cbt_2023

Link to the Zenodo repository of the dataset: https://zenodo.org/records/8310891

Link to the StatCodeSearch dataset repository in Huggingface: https://huggingface.co/datasets/drndr/statcodesearch

### Folder structure:
    ├── data                                 # Code to create GenCodeSearchNet test sets
    │   ├── clf                              # Code to create the text-code matching subsets
    │   ├── mrr                              # Code to create the search/rank subsets
    │   ├── statcodesearch_full              # Includes the full StatCodeSearch dataset with additional metadata and prefiltered versions
    ├── experiments                          # Code for evaluation
### Contributors:
Andor Diera, Abdelhalim Dahou, Lukas Galke, Fabian Karl, Florian Sihler, Ansgar Scherp
