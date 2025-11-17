# Lower Secondary Sample MCQ Set 1 (Technical Focus)

Choose the best answer for each question.

1) In a basic machine learning workflow, which sequence most correctly captures the technical steps from raw data to evaluation?

- A) Collect data → choose metric → deploy model → test
- B) Collect and label data → split into train/test → train a model → evaluate on test
- C) Collect data → write rules → evaluate → tune rules
- D) Collect and label data → deploy app → gather feedback → retrain

2) A dataset for spam detection has 10% spam and 90% non‑spam emails. Which split best supports reliable evaluation?

- A) Random split without constraints
- B) Stratified split that keeps class proportions in both train and test
- C) Put all spam emails into the test set to increase difficulty
- D) Oversample spam in train and undersample it in test

3) You switch from using raw pixel values to edge/contour features for a simple image classifier in a no‑code tool. What technical effect is most likely?

- A) Generalization may improve because features capture structure more directly
- B) Training always becomes slower
- C) Test accuracy always equals training accuracy
- D) Performance gets worse because features reduce data size

4) A model reaches 98% accuracy on training but only 74% on test. Which change targets overfitting most directly?

- A) Increase the number of training epochs
- B) Collect more labeled data or reduce model complexity
- C) Increase the decision threshold to 0.9
- D) Use a larger batch size

5) For a binary classifier where false positives and false negatives matter differently, which evaluation focus is most appropriate?

- A) Only overall accuracy
- B) Class‑specific precision and recall, possibly F1‑score
- C) Only the average confidence score
- D) Training loss at the final epoch

6) Which task is better suited to symbolic (rule‑based) AI than statistical learning at this level?

- A) Recognizing handwritten digits from images
- B) Scheduling school timetables given a set of constraints
- C) Classifying dog vs cat photos
- D) Predicting traffic congestion from sensor data

7) Which situation is a clear example of data leakage that can inflate evaluation results?

- A) Using a fixed random seed for reproducible splits
- B) Including future information (e.g., the actual outcome) as a feature during training
- C) Shuffling training examples before each epoch
- D) Normalizing features using statistics computed on the training split

8) You adjust a binary classifier’s decision threshold from 0.5 to 0.7. What change is most likely?

- A) Recall increases and precision decreases
- B) Recall decreases and precision may increase
- C) Both precision and recall always increase
- D) Accuracy remains exactly the same

9) On a small dataset, which practice strengthens the reliability of your reported performance without depending on a single split?

- A) Report only training accuracy
- B) Use k‑fold cross‑validation for evaluation
- C) Shuffle test labels to stress the model
- D) Increase image resolution

10) When comparing models on an imbalanced dataset, which approach helps ensure a fair comparison?

- A) Compare only overall accuracy
- B) Use precision‑recall curves or class‑weighted metrics
- C) Choose the model with the highest training accuracy
- D) Ignore minority class performance if the majority class is large

