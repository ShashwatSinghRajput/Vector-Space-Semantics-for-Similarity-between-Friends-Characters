# Vector-Space-Semantics-for-Similarity-between-Friends-Characters

# Project Description
This project focuses on analyzing document similarity and character interactions in a textual dataset. It involves a series of data processing and feature engineering steps to enhance the model's ability to capture nuances in text data and improve similarity metrics.

# Key Processes and Innovations
Preprocessing for Document Similarity

The initial stage involved refining the text data through:

- Lowercasing to achieve uniform text format for accurate token comparison.
- Removal of stopwords and punctuations to eliminate irrelevant elements, leading to more refined data.
- These improvements significantly enhanced the model's performance, as observed in the enhanced mean rank and accuracy across test and validation datasets.

Feature Engineering

The next stage involved:

- Implementing n-grams and Part-of-Speech (POS) tagging to enrich the feature set, capturing more contextual and syntactical information.
- Employing TF-IDF transformation to weigh terms and emphasize unique words, crucial for document similarity tasks.
These techniques contributed to a noticeable improvement in the model's mean rank.

Enhancing Contextual Understanding

To deepen the model's grasp of character dynamics and relationships:

- Dialogues were grouped by episodes and scenes, integrating interactions across characters for a richer textual dataset.
- This approach effectively captured the uniqueness of each character’s interactions, improving the model's potential to understand character dynamics.

Parameter Optimization

Through parameter tuning and experimentation:

- Punctuation removal and stopword handling were critically evaluated, leading to a balanced preprocessing approach.
- The utility of n-grams, POS tagging, and TF-IDF in the feature vector creation was reassessed, ensuring optimal model performance.

Character Interaction Insights

- Detailed analysis of character dialogues from a popular TV series revealed insights into character relationships and linguistic styles.
- Unique dialogue patterns and shared storylines were explored to understand similarities and differences among characters.
- Limitations in capturing the essence of characters with the available dataset were noted, indicating potential areas for future improvement.

Final Observations

- Achieved a mean rank of 2.3 and an accuracy of 0.3 with a cosine similarity of 0.9747.
- The results indicate decent performance given the dataset's size, with the suggestion that a larger dataset could yield better results.

# Conclusion
This project underscores the importance of nuanced text processing and feature engineering in understanding document similarity and character interactions. The methods employed provide a foundation for further exploration in the field of natural language processing, particularly in the analysis of character dynamics and linguistic styles.
