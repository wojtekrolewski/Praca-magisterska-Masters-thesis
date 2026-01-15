# Praca-magisterska / Master's Thesis
# Learning the Structure of Bayesian Networks – Algorithm Comparison

## 1. Overview
This project focuses on the comparative analysis of selected algorithms for learning the structure of Bayesian networks.
The goal was to evaluate different approaches in terms of model quality, computational complexity, and practical applicability under varying data conditions.

The project was developed as part of a Master’s thesis and emphasizes algorithmic reasoning and experimental evaluation, rather than black-box model usage.

## 2. Problem Statement
Learning the structure of a Bayesian network from data is a computationally challenging task due to:
- the large search space of possible network structures,
- trade-offs between model accuracy and computational cost.

The objective of this project was to:
- implement and apply selected structure-learning algorithms,
- compare their performance using defined evaluation criteria,
- analyze their strengths, weaknesses, and practical limitations.

## 3. Algorithms Considered
The project analyzed algorithms representing different structure-learning strategies, including:
- score-based approaches, relying on optimization of a scoring function,
- search-based methods, exploring the space of possible network structures.

The comparison highlights how algorithmic assumptions and search strategies influence the resulting network structure.

## 4. Data
Experiments were conducted using:
- synthetic datasets with known dependency structures,
- datasets of varying size and dimensionality.

This allowed evaluation of:
- reconstruction quality,
- sensitivity to data size,
- scalability of the algorithms.

## 5. Methodology
The evaluation procedure consisted of:
- learning Bayesian network structures from data using different algorithms,
- assessing model quality using defined scoring metrics,
- measuring computational cost and convergence behavior,
- comparing results across datasets and configurations.

All experiments were designed to ensure repeatability and fair comparison.

## 6. Implementation
**Language:** R

**Tools:** Bayesian network analysis libraries

**Workflow:** data preprocessing → structure learning → evaluation → comparison

The implementation enables:
- systematic experimentation with algorithm parameters,
- reproducible benchmarking of structure-learning methods.

## 7. Results
The comparative analysis shows that:
- no single algorithm performs best in all scenarios,
- certain methods provide better accuracy at the cost of higher computation time,
- simpler algorithms scale better but may sacrifice structural accuracy.

These results highlight the importance of choosing algorithms based on problem constraints rather than theoretical optimality alone.

## 8. Limitations
- computational complexity limits applicability to high-dimensional datasets,
- sensitivity to dataset size and noise,
- results depend on scoring function and search strategy selection.

## 9. Conclusion
This project demonstrates:
- the importance of algorithm selection in probabilistic graphical models,
- practical trade-offs between accuracy and efficiency,
- the value of experimental comparison in applied machine learning research.

The insights gained are directly applicable to model selection and evaluation problems in ML and data science.

## 10. Conclusion
This project was developed as part of a Master’s thesis.

Full thesis (PDF):

https://drive.google.com/file/d/1Em-GJWZnkDnVhfKLvIy_mMJBM3lW7ZQo/view?usp=sharing
