**Project Title:** Protein Subcellular Localization Prediction 

**Overview:**

Our project addresses the complex challenge of Protein Subcellular Localization Prediction, a multi-label multi-class classification task crucial for understanding the intracellular organization of proteins. Unlike traditional methods relying on Hidden Markov Models (HMM) and Position-Specific Scoring Matrices (PSSM), our innovative approach not only eliminates the need for time-consuming matrix generation but also demonstrates a significant reduction in time complexity.

**Key Features:**
1. Novel SkipXGram-Bigram Model:

We introduced a groundbreaking SkipXGram-Bigram model, departing from conventional HMM and PSSM-based techniques.
Leveraging the power of N-Gram Word2Vec models, we designed a strategy to extract fixed-size SkipXGram matrices from protein sequences.

2. Efficient Embeddings:

By training our model on protein sequences, we harnessed the potential of SkipXGram-Bigram embeddings, providing a more efficient and effective representation of protein features.
This not only streamlines the classification process but also ensures optimal time complexity.

3. Deep Neural Network Architecture:

We integrated our embeddings into a state-of-the-art Deep Neural Network (DNN) architecture, capitalizing on the representational power of neural networks for improved accuracy.
The DNN facilitates the learning of intricate patterns in protein sequences, enhancing predictive performance.

4. Jaccard Accuracy Evaluation:

To assess the performance of our classification models, we introduced a novel evaluation criteria named Jaccard Accuracy.
Jaccard Accuracy offers a comprehensive measure of the model's ability to correctly predict the subcellular localization of proteins, considering both precision and recall.

**Advancements in the Field:**

Our approach not only eliminates the computational overhead associated with traditional methods but also opens avenues for ground-breaking advancements in the field of Protein Subcellular Localization Prediction. The SkipXGram-Bigram model, coupled with deep learning techniques, showcases the potential to revolutionize how researchers approach this critical bioinformatics task.
