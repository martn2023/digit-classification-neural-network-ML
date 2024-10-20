# I. Author's Context:
- I've held leadership roles in numerous VC-backed tech startups, but they were all __business__ roles (finance, COO, product). After building some CRUD web apps and ETL pipelines, I'm upskilling in __Applied ML Engineering__.

- An ex-Google dev showed me an industry standard ML book [Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow](https://www.amazon.com/Hands-Machine-Learning-Scikit-Learn-TensorFlow/dp/1492032646) by Aurelien Geron:

| CHAPTER | FOUNDATIONAL PROJECT           | TECH/MODEL USED                | STATUS                |
|---------|--------------------------------|--------------------------------|-----------------------|
| 2       | Predicting housing prices      | Supervised Learning, Regression| **Published Repo**    |
| 3       | Classifying handwritten digits | Neural Networks, Classification| **In Progress**       |
| 4       | Training models                | Supervised Learning            | Not Started           |
| 5       | Classifying data points        | Support Vector Machines (SVM)  | Not Started           |
| 6       | Tree-based models              | Decision Trees, Random Forests | Not Started           |
| 7       | Combining models               | Ensemble Learning              | Not Started           |
| 8       | Reducing dataset complexity    | Dimensionality Reduction       | Not Started           |
| 9       | Grouping similar data points   | Clustering, Unsupervised Learning| Not Started         |
| 10      | Building neural networks       | Neural Networks, Deep Learning | Not Started           |


# II. Project Overview:

### Level 1 Complexity: "Is it a 5 or not?"
This project is about classifying images of handwritten numbers. Straight out of that [comedy show about startups](https://www.youtube.com/watch?v=ACmydtFDTGs&ab_channel=HBO) where the food-classification phone app can only see whether a meal is a hot dog or not.

### Level 2 Complexity: "5 or a 3?"

### Level 3 Complexity: "Which digit is this?"
- Can I make a tool that looks at handwritten digits (0 through 9) and correctly identify the number being written?
- This a free-flowing exercise without textbook assistance


# III. Screenshots (illustrative, but not comprehensive):
Asasdfadsf

# IV. Challenges, Tradeoffs and Considerations:
### Re-combine raw data?
MINST offers 70K images, but these are pre-split into 60K training and 10K testing. My kneejerk reaction was to combine these 2 and re-shuffle them to "simulate the real world", where there's no reasonable expectation of getting data curated for you at the start. I reluctantly withdrew my objection because doing would increase inconsistencies from a mountain of existing literature on this table-stakes exercise, and I didn't want to get stuck trying to figure out if any deltas were due to error vs the fact I recombined test data at the start.

### Data extraction method
I wanted manually browse Kaggle to ensure I had the latest version, and then manually download. Ended up pulling a specific data set name in the textbook to avoid inconsistencies and leverage automation.


# V. Major Learnings:
>**Kaggle:**<br>
Kaggle the LeetCode of ML, web site that has data sets and challenges you can work on, either untimed or in timed competitions. 

>**asdf:**<br>
asdf


# VI. Potential improvements:
>**Product/UI:**<br>
- The 

>**Engineering:**<br>
- Func

>**Tools**<br>
- BigQ