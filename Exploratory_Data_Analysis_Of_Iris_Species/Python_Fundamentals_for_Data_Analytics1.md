### Python Fundamentals for Data Analytics

#### **Objective**
This hands-on project is designed to help you develop foundational Python programming skills for data analytics. You will use pandas, NumPy, and Matplotlib to explore, manipulate, and visualize a real-world dataset. You'll practice common tasks such as data cleaning, aggregation, and transformation, and gain experience writing Python functions and loops to automate your data tasks. 

#### **Learning Outcomes**
- Gain proficiency in using pandas for dataframe manipulation 

- Use NumPy and basic Python structures to process data 

- Visualize data using Matplotlib 

- Practice hands-on programming and analysis in Google Colab 

#### **Instructions**
**Access the Dataset:**

Choose from Titanic, World Happiness, Iris, or another approved dataset. 

**Complete the Following Tasks in Google Colab:**

- Load the dataset with pandas.
- Perform EDA and generate two plots using Matplotlib.
- Manipulate data: filter, group, merge, reshape.
- Write custom functions and use loops or conditionals.

#### **Report Requirements (2–3 Pages)**

1. Introduction (100 words)
2. Code & Process (300 words)
3. Findings & Observations (200 words)
4. Reflection (100–150 words)

#### **Deliverables**
1. Google Colab notebook (.ipynb) 

2. Written report ( DOCX) 

 

#### **Hints and Tips**
**Choosing & Loading Data**

- Use built‑in datasets like Titanic (`sns.load_dataset('titanic')`) or upload a CSV.
- Load with `pd.read_csv()` and inspect with `df.head()`, `df.info()`.

##### **Core pandas Moves**

- `df.groupby('col').agg({'num_col':'mean'})` for quick summaries.
- Join tables with `pd.merge(left, right, on='key')`.
- Reshape using `df.pivot_table(values, index, columns, aggfunc='sum')`.

##### **Writing Reusable Code**

- Wrap repetitive cleaning steps in a function: `def clean(df): ... return df`.
- Use list comprehensions and loops for column‑wise operations.

##### **Visualization Quick‑Start**

- `plt.hist(df['num_col'])` for distributions.
- `df.plot(kind='bar', x='cat', y='value')` for comparisons.
- Always label axes and add a title.

#### **Resources**

- [Google Colab](https://colab.research.google.com/)
- [pandas](https://pandas.pydata.org/docs/)
- [NumPy](https://numpy.org/doc/stable/user/quickstart.html)
- [Matplotlib](https://matplotlib.org/stable/gallery/index.html)