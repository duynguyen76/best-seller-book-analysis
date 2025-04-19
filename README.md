# Book Analysis Project
- This is a small project for our course SC1015(Introduction to Data Science and Artificial Intelligence), we decided to choose books as our main focus base on the data set we found. 

- This project explores a dataset of books with the goal of uncovering patterns in publishing trends, bestseller characteristics, and author profiles using data visualization, text mining, and machine learning techniques.

---

# Contributor:

- **Nguyen** **Phuong** **Thuy**: 
- **Nguyen** **Duy**:
- **Chu** **Gia** **Han**:

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

###  What We Learned:
- **Handling the imbalanced datasets**
- **Text data holds a lot of predictive power** — even simple TF-IDF scoring can reveal big differences in language between successful and average books.
- **Data visualization is key** for spotting trends and outliers you can’t see in raw numbers.
- **Clustering adds structure** to complex datasets and can help categorize patterns in consumer markets.
- Being a bestseller isn’t just about content — it's also about language, branding, and potentially timing.

  ---

  ## Reference:
- Dataset: https://www.kaggle.com/datasets/asaniczka/amazon-kindle-books-dataset-2023-130k-books




