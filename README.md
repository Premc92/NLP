# Natural Language Processing Projects

## Project overview
A collection of NLP exercises covering customer-review sentiment, topic discovery and text toxicity classification. These methods can also support customer feedback analytics and complaint-theme monitoring in financial services, subject to privacy, fairness and validation controls.

## Projects in this repository
- Amazon review analysis and sentiment classification
- Topic analysis
- Wiki toxicity classification

## Business relevance
For a lender, text analytics can help organise customer complaints, identify recurring service issues and prioritise feedback for human review. Text models should not independently determine creditworthiness or adverse customer outcomes.

## Improvement plan
1. Standardise text cleaning and label definitions.
2. Use train/test splits before fitting vectorisers.
3. Put TF-IDF and estimators together in scikit-learn pipelines to prevent cross-validation leakage.
4. Use stratified splits for classification where appropriate.
5. Report per-class precision, recall and F1; include confusion matrices and threshold discussion.
6. Set random seeds where supported and document topic-count choices.
7. Avoid unnecessary downloads and make notebook dependencies explicit.
8. Review false positives, false negatives, bias and privacy implications.

## Tools
Python, pandas, NLTK, scikit-learn, TF-IDF, sentiment analysis and topic-modelling libraries used in the notebooks.

## Responsible-use note
Text classification can be noisy, context-sensitive and biased. Outputs should support human analysis, not be treated as definitive judgements about a customer or individual.
