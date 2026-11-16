# Banking-Classification-CS74-Final-Project-
Austin Gorman

Compares Logistic Regression, a linear SVM, Multinomial Naive Bayes, and an RBF SVM on
classifying banking customer questions into 77 intents, with K-means/DBSCAN clustering
of intents and qualitative error analysis.

**How to run:** open `Austin_Gorman_CS74_Final_Project.ipynb` in Jupyter, VS Code, or
Google Colab and run all cells. Requires numpy, pandas, matplotlib, and scikit-learn.
The notebook loads the data from PolyAI's GitHub; copies are also included here
(`train.csv`, `test.csv`). Random seeds are fixed (`random_state=1`) for reproducibility.

**Data files:** `train.csv` (10,003 questions) and `test.csv` (3,080 questions) from the
BANKING77 dataset by PolyAI (Casanueva et al., 2020), released under CC BY 4.0.
Original source: https://github.com/PolyAI-LDN/task-specific-datasets
