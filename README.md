# Book Analysis Project
- This is a small project for our course SC1015(Introduction to Data Science and Artificial Intelligence), we decided to choose books as our main focus base on the data set we found. 

- This project explores a dataset of books with the goal of uncovering patterns in publishing trends, bestseller characteristics, and author profiles using data visualization, text mining, and machine learning techniques.

---

# Contributor:

- **Nguyen** **Phuong** **Thuy**
- **Nguyen** **Duy**
- **Chu** **Gia** **Han**

---

# Problem definition

- Can we tell if the book will be the best seller based on it writer, review and title?
- Which model will fit the best to predict in this problem?
---

## Features

- **Data Cleaning**: Preprocessing of book data, handling missing values, standardizing formats.
-  **Visualization**: Boxplots, histograms, violin plots, and author-wise bestseller distributions.
-  **Text Mining**: TF-IDF analysis to extract meaningful words from bestsellers vs. non-bestsellers.
-  **Clustering**: K-Means clustering applied to scaled numerical features to group similar books.
-  **Insights**: Interpretation of patterns found in bestseller language, price trends, and rating distributions.

---

## Tools & Libraries

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (TF-IDF, KMeans)

---

### Key Insights:

- **Bestseller Traits**: Titles of bestselling books often include emotionally engaging or broad themes like *romance*, *adventure*, *home*, and *power*. In contrast, non-bestsellers leaned more toward practical or niche keywords such as *guide*, *edition*, *cookbook*, and *recipes*.
  
- **Author Trends**: Only a few authors, such as *J.K. Rowling*, *Stephen King*, and *DK*, publish a large number of books *and* have a relatively high share of bestsellers. Most authors have no bestsellers despite having published many books.

- **Numeric Patterns**: Visualizations (boxplots, violin plots, histograms) revealed differences in distributions of variables like *price* and *stars*. These helped us spot outliers and patterns in how books are priced and rated.

- **Clustering**: K-Means clustering grouped books into 31 segments based on their numeric features. This opens the door for more targeted analysis — like identifying clusters of high-priced, low-rated books or cheap bestsellers.

---

## **Conclusion**
- Price is a strong indicator of whether a book becomes a bestseller, as reflected in its prominence in decision-making processes across models.
- Text-based features, such as keywords derived from book titles, provide valuable thematic context, helping refine predictions.
- Resampling imbalanced data ensured better representation of minority classes, enhancing the overall model fairness and performance.
- Random Forest Classifier, when fine-tuned using hyperparameter tuning (e.g., GridSearchCV), performed consistently well, achieving high accuracy and balanced recall values across training and testing datasets.
- Decision Trees provide interpretable results, clearly outlining factors influencing bestseller predictions, but require constraints to prevent overfitting.
- Combining textual and numeric features results in a comprehensive approach, enabling acceptable accuracy and recall rates for predicting bestseller status.

It is possible to predict bestseller status of a book using a well-tuned ensemble model, leveraging both textual and numeric data with robust cross-validation techniques.

###  What We Learned:
- **Handling the imbalanced datasets**
- **Text data holds a lot of predictive power** — even simple TF-IDF scoring can reveal big differences in language between successful and average books.
- **Data visualization is key** for spotting trends and outliers you can’t see in raw numbers.in consumer markets.
- **How to use and upload file into Github**

  ---

  ## Reference:
- Dataset: https://www.kaggle.com/datasets/asaniczka/amazon-kindle-books-dataset-2023-130k-books




