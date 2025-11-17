# Upper Secondary Sample MCQ Set 1 (Technical Focus)

Choose the best answer for each question.

1) Which metric is most informative for highly imbalanced binary classification?

- A) Accuracy
- B) Mean absolute error
- C) Precision–Recall AUC
- D) Training loss

Answer: C

Explanation: PR AUC focuses on positive class quality and is robust under imbalance.

---

2) What is the primary role of a validation (dev) set?

- A) Final unbiased performance reporting
- B) Hyperparameter selection and model comparison
- C) Data collection planning
- D) Measuring training speed

Answer: B

Explanation: The dev set guides model/parameter choices; the test set reports final performance.

---

3) If the learning rate is set too high, what training behavior is most likely?

- A) Converges more slowly but safely
- B) Perfectly fits both training and test
- C) Underfits due to small weights
- D) Loss oscillates or diverges instead of decreasing steadily

Answer: D

Explanation: Excessive step sizes cause instability and prevent convergence.

---

4) What does L2 regularization do in practice?

- A) Encourages sparse features by zeroing weights
- B) Penalizes large weights to reduce overfitting
- C) Adds dropout during inference
- D) Changes labels to smooth targets

Answer: B

Explanation: L2 adds a weight penalty that discourages overly large parameters.

---

5) For CNNs, why is data augmentation (rotations, flips, crops) useful?

- A) Increases batch size without more memory
- B) Reduces parameter count
- C) Improves hardware throughput
- D) Increases input diversity to reduce overfitting

Answer: D

Explanation: Augmentation exposes the model to variations, improving generalization.

---

6) In NLP, which tokenization handles rare/unknown words robustly?

- A) Whitespace tokenization
- B) Character-level only
- C) Subword methods (Byte-Pair Encoding/WordPiece)
- D) Fixed vocabulary that ignores OOV terms

Answer: C

Explanation: Subword tokenization decomposes words to handle OOVs and morphology.

---

7) What observation reflects the semantics captured by word embeddings?

- A) All vectors are zeros for stability
- B) Similar words tend to have nearby vectors in embedding space
- C) Embeddings guarantee 100% accuracy on downstream tasks
- D) Embeddings remove the need for any training

Answer: B

Explanation: Embeddings encode semantic proximity; similar words cluster.

---

8) The ROC curve plots what quantities across decision thresholds?

- A) Precision vs recall
- B) Accuracy vs loss
- C) True Positive Rate vs False Positive Rate
- D) F1 vs precision

Answer: C

Explanation: ROC shows TPR vs FPR; AUC summarizes discriminative ability.

---

9) Smaller batch sizes typically:

- A) Reduce generalization due to less noise
- B) Always speed up training
- C) Consume more GPU memory
- D) Introduce gradient noise that can help generalization

Answer: D

Explanation: Noisy gradients can act like regularization, often improving generalization.

---

10) What does early stopping do?

- A) Stops training when validation performance no longer improves
- B) Randomly stops training to save compute
- C) Stops after fixed epochs regardless of validation
- D) Stops data augmentation after warmup

Answer: A

Explanation: Monitoring dev metrics prevents overfitting by halting before performance worsens.

