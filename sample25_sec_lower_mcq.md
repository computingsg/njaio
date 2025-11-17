# NAIJO Singapore 2025 MCQ
## Lower Secondary (Grades 7 - 8)

## Question 1
**In a basic machine learning workflow, which sequence most correctly captures the technical steps from raw data to evaluation?**

A) Collect and label data → deploy app → gather feedback → retrain  
B) Collect data → choose metric → deploy model → test  
C) Collect and label data → split into train/test → train a model → evaluate on test  
D) Collect data → write rules → evaluate → tune rules

**Answer: C**

**Explanation:** Label data, split into train/test, train, then evaluate on unseen test data to check generalization.

---

## Question 2
**A dataset for spam detection has 10% spam and 90% non‑spam emails. Which split best supports reliable evaluation?**

A) Oversample spam in train and undersample it in test  
B) Random split without constraints  
C) Stratified split that keeps class proportions in both train and test  
D) Put all spam emails into the test set to increase difficulty

**Answer: C**

**Explanation:** Stratification preserves class ratios across splits, yielding fairer estimates.

---

## Question 3
**You switch from raw pixel values to edge/contour features in a no‑code image classifier. What technical effect is most likely?**

A) Performance gets worse because features reduce data size  
B) Generalization may improve because features capture structure more directly  
C) Training always becomes slower  
D) Test accuracy always equals training accuracy

**Answer: B**

**Explanation:** Informative features can help models focus on signal instead of noise.

---

## Question 4
**A model reaches 98% accuracy on training but only 74% on test. Which change most directly targets overfitting?**

A) Use a larger batch size  
B) Increase training epochs  
C) Collect more labeled data or simplify the model  
D) Increase the decision threshold to 0.9

**Answer: C**

**Explanation:** More diverse data or reduced complexity helps the model generalize better.

---

## Question 5
**For a binary classifier where false positives and false negatives have different costs, which evaluation focus is most appropriate?**

A) Training loss at the final epoch  
B) Only overall accuracy  
C) Class‑specific precision and recall, possibly F1‑score  
D) Only the average confidence score

**Answer: C**

**Explanation:** Precision/recall reflect error trade‑offs better than accuracy on imbalanced tasks.

---

## Question 6
**Which task is better suited to symbolic (rule‑based) AI than statistical learning at this level?**

A) Predicting traffic congestion from sensor data  
B) Recognizing handwritten digits from images  
C) Scheduling school timetables given a set of constraints  
D) Classifying dog vs cat photos

**Answer: C**

**Explanation:** Constraint‑based scheduling aligns with rules and search typical of symbolic AI.

---

## Question 7
**Which situation is a clear example of data leakage that can inflate evaluation results?**

A) Normalizing features using statistics computed on the training split  
B) Using a fixed random seed for reproducible splits  
C) Including future information (the actual outcome) as a feature during training  
D) Shuffling training examples before each epoch

**Answer: C**

**Explanation:** Leaked future labels/features let the model “cheat,” overstating performance.

---

## Question 8
**You adjust a binary classifier’s decision threshold from 0.5 to 0.7. What change is most likely?**

A) Accuracy remains exactly the same  
B) Recall increases and precision decreases  
C) Recall decreases and precision may increase  
D) Both precision and recall always increase

**Answer: C**

**Explanation:** A higher threshold produces fewer positives (lower recall) but often cleaner ones (higher precision).

---

## Question 9
**On a small dataset, which practice strengthens the reliability of reported performance without depending on a single split?**

A) Increase image resolution  
B) Report only training accuracy  
C) Use k‑fold cross‑validation for evaluation  
D) Shuffle test labels to stress the model

**Answer: C**

**Explanation:** Cross‑validation averages performance across folds, reducing variance from one split.

---

## Question 10
**When comparing models on an imbalanced dataset, which approach helps ensure a fair comparison?**

A) Ignore minority class performance if the majority class is large  
B) Compare only overall accuracy  
C) Use precision‑recall curves or class‑weighted metrics  
D) Choose the model with the highest training accuracy

**Answer: C**

**Explanation:** PR curves and class‑weighted metrics reflect minority performance better than accuracy.

---

## Question 11
**A fitness tracking app offers great features if you allow it to constantly track your location and health data. What ethical trade-off does this illustrate?**

A) More location-aware recommendations at the cost of more computational processing requirements  
B) Gaining personalised insights at the cost of giving up some privacy about personal data  
C) More efficient on-device processing at the cost of more memory needed to store personal data  
D) More control over data stored on a local device at the cost of potential security hacks  

**Answer: B**

**Explanation:** Many smart apps provide useful personalised services but require collecting personal information. This creates a convenience vs. privacy trade-off.

---

## Question 12
**A social media AI shows you only posts you agree with. Why could this be a problem?**

A) It might cause your online friends who have alternative views to unfriend you.  
B) It can limit your exposure to different viewpoints and skewing your perspective  
C) It can limit the amount of training data available to learn from, which can affect its ability to provide accurate information  
D) It might show you too many diverse opinions, causing confusion

**Answer: B**

**Explanation:** Echo chambers can polarize opinions and limit balanced understanding.

---

## Question 13
**AI can create deepfakes. What is a major concern about this technology?**

A) Only governments or large tech companies should use deepfakes to prevent misinformation  
B) It can be used to spread misinformation  
C) It dramatically improves video quality for old movies  
D) It requires advanced technology to detect and flag deepfakes

**Answer: B**

**Explanation:** Deepfakes can impersonate people and spread fraud or propaganda.

---

## Question 14
**Cities use AI-powered cameras to scan crowds. What is a potential downside of this surveillance technology?**

A) It could not identify people wearing masks accurately, leading to false positives  
B) It could invade privacy   
C) It could misidentify people  
D) It could eliminate all crimes

**Answer: B**

**Explanation:** Surveillance benefits must be weighed against privacy and civil liberties.

---

## Question 15
**Which action can help ensure an AI system behaves ethically and safely?**

A) Training the AI once and never updating or evaluating it again  
B) Having human experts oversee its critical decisions and regularly check for errors or biases  
C) Removing all human involvement and letting the AI run completely on its own  
D) Keeping the AI’s decision process secret so nobody interferes

**Answer: B**

**Explanation:** Human oversight and regular evaluation are key for responsible AI.

---

## Question 16
**Why do AI developers split data into a training set and a testing set?**

A) To utilise computer memory more efficiently   
B) To see if the model can generalise to new unseen data  
C) To allow for a time lapse between data sets to prevent overheating  
D) To enable the model to accelerate its learning rate

**Answer: B**

**Explanation:** Separate test sets reveal overfitting and measure real generalization.

---

## Question 17
**Which scenario is an example of rule-based or 'symbolic' AI?**

A) A voice assistant that gets better via repeated data training  
B) A chatbot that uses a fixed list of if-then rules written by programmers to respond to questions  
C) A photo app that improves face recognition by training on millions of images  
D) A spam filter that learns to detect spam by analyzing examples

**Answer: B**

**Explanation:** Symbolic AI uses human-written rules; ML improves from data.

---

## Question 18
**A medical test catches 99% of people with a disease but wrongly flags some healthy people. What can we say?**

A) Low recall and low precision  
B) High recall but lower precision  
C) High precision but low recall  
D) High recall and high precision

**Answer: B**

**Explanation:** Prioritizing recall can be acceptable when missing a true case is worse than false alarms.

---

## Question 19
**Which task is AI especially well-suited for compared to a person?**

A) Deciding the fairest punishment in a complex legal case  
B) Examining thousands of medical scans quickly to detect anomalies  
C) Understanding a patient's feelings and providing emotional support  
D) Making a judgment call on a completely new situation with no prior data

**Answer: B**

**Explanation:** AI excels at large-scale pattern detection when well-trained.

---

## Question 20
**If a self-driving car causes an accident, who should be most responsible for the decision the AI made?**

A) The passengers because they are the ones who interact with the system  
B) The self-driving car company because they manufactured the final product  
C) The AI scientists because they designed the algorithms  
D) The AI engineers because they programmed the systems

**Answer: B**

**Explanation:** Responsibility falls on the people and organisations that design, program, and deploy AI.

---
