# NJAIO 2026 Sample Paper Section A MCQ
## Upper Secondary (Grades 9 - 12)

## Question 1
**Which metric is most informative for highly imbalanced binary classification?**

A) Accuracy  
B) Mean absolute error  
C) Precision–Recall AUC  
D) Training loss

**Answer: C**

**Explanation:** PR AUC focuses on positive class quality and is robust under imbalance.

---

## Question 2
**What is the primary role of a validation (dev) set?**

A) Final unbiased performance reporting  
B) Hyperparameter selection and model comparison  
C) Data collection planning  
D) Measuring training speed

**Answer: B**

**Explanation:** The dev set guides model/parameter choices; the test set reports final performance.

---

## Question 3
**If the learning rate is set too high, what training behavior is most likely?**

A) Converges more slowly but safely  
B) Perfectly fits both training and test  
C) Underfits due to small weights  
D) Loss oscillates or diverges instead of decreasing steadily

**Answer: D**

**Explanation:** Excessive step sizes cause instability and prevent convergence.

---

## Question 4
**What does L2 regularization do in practice?**

A) Encourages sparse features by zeroing weights  
B) Penalizes large weights to reduce overfitting  
C) Adds dropout during inference  
D) Changes labels to smooth targets

**Answer: B**

**Explanation:** L2 adds a weight penalty that discourages overly large parameters.

---

## Question 5
**For CNNs, why is data augmentation (rotations, flips, crops) useful?**

A) Increases batch size without more memory  
B) Reduces parameter count  
C) Improves hardware throughput  
D) Increases input diversity to reduce overfitting

**Answer: D**

**Explanation:** Augmentation exposes the model to variations, improving generalization.

---

## Question 6
**In NLP, which tokenization handles rare/unknown words robustly?**

A) Whitespace tokenization  
B) Character-level only  
C) Subword methods (Byte-Pair Encoding/WordPiece)  
D) Fixed vocabulary that ignores OOV terms

**Answer: C**

**Explanation:** Subword tokenization decomposes words to handle OOVs and morphology.

---

## Question 7
**What observation reflects the semantics captured by word embeddings?**

A) All vectors are zeros for stability  
B) Similar words tend to have nearby vectors in embedding space  
C) Embeddings guarantee 100% accuracy on downstream tasks  
D) Embeddings remove the need for any training

**Answer: B**

**Explanation:** Embeddings encode semantic proximity; similar words cluster.

---

## Question 8
**The ROC curve plots what quantities across decision thresholds?**

A) Precision vs recall  
B) Accuracy vs loss  
C) True Positive Rate vs False Positive Rate  
D) F1 vs precision

**Answer: C**

**Explanation:** ROC shows TPR vs FPR; AUC summarizes discriminative ability.

---

## Question 9
**Smaller batch sizes typically:**

A) Reduce generalization due to less noise  
B) Always speed up training  
C) Consume more GPU memory  
D) Introduce gradient noise that can help generalization

**Answer: D**

**Explanation:** Noisy gradients can act like regularization, often improving generalization.

---

## Question 10
**What does early stopping do?**

A) Stops training when validation performance no longer improves  
B) Randomly stops training to save compute  
C) Stops after fixed epochs regardless of validation  
D) Stops data augmentation after warmup

**Answer: A**

**Explanation:** Monitoring dev metrics prevents overfitting by halting before performance worsens.

---

## Question 11
**What does the term "digital divide" mean in the context of AI?**

A) The professional separation between academic AI researchers and industry practitioners working on commercial applications  
B) The computational divide between classical binary systems and quantum computing architectures used in AI development  
C) The gap between those who have access to AI technology and education and those who do not, often along socioeconomic or geographical lines  
D) The mathematical division algorithm that AI systems use to process numerical data in neural networks

**Answer: C**

**Explanation:** The "AI digital divide" refers to inequality in AI benefits and knowledge. Some people, communities, or countries have the resources, education, and infrastructure to leverage AI, while others are left behind. This gap can lead to further economic and social inequality. It's not about how computers compute (digital vs analog), but about who gets to use and benefit from cutting-edge tech.

---

## Question 12
**AI is expected to automate certain jobs. What is a constructive strategy to handle job displacement caused by AI?**

A) Restrict AI development to only those companies that guarantee no worker displacement through legally binding agreements  
B) Implement universal AI bans across all industries to preserve traditional employment structures and prevent technological disruption  
C) Adopt a laissez-faire approach where market forces naturally redistribute displaced workers without intervention  
D) Invest in retraining and upskilling programs so that workers can transition to new roles that AI creates or roles that require human skills

**Answer: D**

**Explanation:** The realistic and positive approach is to help the workforce adapt. History shows technology creates new jobs even as it replaces some – the key is education and reskilling.

---

## Question 13
**In an autonomous car "trolley problem" scenario, what does this illustrate?**

A) A minor navigation system malfunction rather than a fundamental moral programming challenge  
B) An ethical dilemma in AI decision-making, where the AI must be programmed to handle situations with no good outcome  
C) A straightforward optimization problem that can be solved with sufficient sensor data and computational power  
D) A purely theoretical thought experiment that has no practical relevance to real-world autonomous vehicle deployment

**Answer: B**

**Explanation:** The trolley problem forces programmers and society to consider how an AI should be designed to value lives and make moral choices.

---

## Question 14
**If an AI system causes harm (e.g., an autonomous drone injures someone), who is accountable?**

A) The AI system should be granted legal personhood and held accountable through algorithmic liability frameworks  
B) No entity bears responsibility when AI systems cause harm  
C) Accountability should be limited to shutting down the offending system, with no further consequences  
D) The humans and organizations that designed, trained, or deployed the AI

**Answer: D**

**Explanation:** Accountability traces back to developers, manufacturers, and operators. AI has no legal personhood.

---

## Question 15
**In medical diagnostics, which performance metric is crucial when we want to catch every possible case?**

A) Computational efficiency – minimize computational resources  
B) Precision – ensure every positive prediction is correct, even if some cases are missed  
C) Recall – find as many true cases as possible, minimizing false negatives  
D) Latency – ensure fast UI response

**Answer: C**

**Explanation:** High recall is paramount because missing a sick patient can be life-threatening.

---

## Question 16
**Which of the following is an example of a machine learning model used for classification tasks?**

A) A linear regression model that predicts students' exam scores based on input features  
B) A deterministic sorting algorithm that alphabetically orders text strings  
C) A validation function that randomizes data splits  
D) A decision tree that splits data based on features to decide a discrete class

**Answer: D**

**Explanation:** Decision trees learn decision splits to classify data; the other options are not ML classification models.

---

## Question 17
**What is overfitting in the context of machine learning?**

A) Memory limitations due to dataset size exceeding RAM  
B) A model too simple that performs poorly on both training and test data  
C) Training continues excessively, causing random hallucinations  
D) Excellent training performance but poor generalization to unseen data

**Answer: D**

**Explanation:** Overfitting is learning noise/quirks of training data, harming performance on new data.

---

## Question 18
**In a neural network, what is adjusted during training for the model to learn?**

A) The physical semiconductor architecture of the hardware  
B) The number of hidden layers  
C) The weights between neurons  
D) The number of connections between neurons

**Answer: C**

**Explanation:** Training updates weights (and biases) via algorithms like backpropagation.

---

## Question 19
**Which scenario is an example of unsupervised learning?**

A) A classifier trained on labeled images of cats vs dogs  
B) Rule-based document classification  
C) An agent learning via rewards in an environment  
D) Grouping unlabeled data points into clusters based on similarity

**Answer: D**

**Explanation:** Unsupervised learning finds structure in unlabeled data; clustering is textbook.

---

## Question 20
**Which of these tasks is a regression problem?**

A) Classifying handwritten digits (0–9) from images  
B) Determining whether an email is "spam" or "not spam"  
C) Predicting the temperature for tomorrow in degrees Celsius  
D) Recognizing if an image contains a cat or a dog

**Answer: C**

**Explanation:** Regression predicts continuous values; the others are classification tasks.

---
