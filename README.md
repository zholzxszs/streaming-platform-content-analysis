# Streaming Platforms Exploratory Data Analysis (EDA)

This project presents an exploratory data analysis (EDA) of the content libraries of **Netflix**, **Amazon Prime**, and **Disney+** using Python. The analysis focuses on data preparation, feature engineering, visualization, and descriptive statistics to compare the composition of each platform's catalog.

The project explores differences in content types, release years, genres, content ratings, production countries, durations, directors, and cast members while demonstrating practical data analysis techniques.

---

## Dataset

The datasets used in this project were obtained from Kaggle.

- [Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- [Amazon Prime Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/amazon-prime-movies-and-tv-shows)
- [Disney+ Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/disney-movies-and-tv-shows)

**Key attributes**

- Title
- Type
- Director
- Cast
- Country
- Release Year
- Date Added
- Rating
- Duration
- Genre
- Description

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Analysis Workflow

The notebook follows the following workflow:

1. Data Quality Assessment
2. Data Cleaning
3. Feature Engineering
4. Exploratory Data Analysis (EDA)
5. Cross-Platform Summary
6. Conclusions and Recommendations

---

## Visualizations

The exploratory analysis includes comparisons of:

- Content Type Distribution
- Titles Added by Year
- Release Year Distribution
- Top Production Countries
- Top Genres
- Content Ratings
- Top Directors
- Top Cast Members
- TV Show Season Distribution
- Movie Duration Distribution

---

## Key Findings

- **Amazon Prime** contains the largest overall content catalog among the analyzed platforms.
- **Movies** outnumber **TV Shows** across all platforms.
- **Netflix** experienced the largest increase in newly added titles between **2016** and **2019**.
- **Disney+** contains a higher proportion of **Family** and **Animation** titles than the other platforms.
- Most TV Shows consist of a **single season**, while movie durations are concentrated around standard feature-length runtimes.
- The **United States** is the largest production country across the analyzed platforms, although **Netflix** shows greater geographic diversity in its available catalog.

---

## Repository Structure

```text
Streaming-Platforms-EDA/
├── dataset/
│   ├── amazon_prime_titles.csv
│   ├── disney_plus_titles.csv
│   └── netflix_titles.csv
├── images/
├── notebook.ipynb
├── README.md
└── .gitignore
```

---

## Getting Started

1. Clone this repository.
3. Open `notebook.ipynb` using Jupyter Notebook or Visual Studio Code.
4. Run the notebook from top to bottom.

---

## Author

**Judiel G. Legaspina**<br>
BS Computer Science Graduate  
Aspiring Data Analyst