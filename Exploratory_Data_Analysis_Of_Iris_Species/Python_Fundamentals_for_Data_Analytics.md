# Python Fundamentals for Data Analytics

## Objective

This hands-on project is designed to help you develop foundational Python programming skills for data analytics. You will use pandas, NumPy, and Matplotlib to explore, manipulate, and visualize a real-world dataset. You will practice common tasks such as data cleaning, aggregation, and transformation, while gaining experience writing Python functions and loops to automate data tasks.

## Learning Outcomes

- Gain proficiency in using pandas for DataFrame manipulation.
- Use NumPy and basic Python structures to process data.
- Visualize data using Matplotlib.
- Practice hands-on programming and analysis in Google Colab.

## Instructions

### Access the Dataset

Choose one of the following datasets, or use another instructor-approved dataset:

- Titanic
- World Happiness
- Iris
- Another approved dataset

### Complete the Following Tasks in Google Colab

- Load the dataset with pandas.
- Perform exploratory data analysis (EDA).
- Generate two plots using Matplotlib.
- Manipulate the data by filtering, grouping, merging, and reshaping it.
- Write custom functions and use loops or conditionals.

## Report Requirements

Prepare a 2–3-page report containing the following sections:

1. **Introduction:** Approximately 100 words.
2. **Code & Process:** Approximately 300 words.
3. **Findings & Observations:** Approximately 200 words.
4. **Reflection:** Approximately 100–150 words.

## Deliverables

1. Google Colab notebook (`.ipynb`)
2. Written report (`.docx`)

## Hints and Tips

### Choosing and Loading Data

- Use built-in datasets such as Titanic: `sns.load_dataset('titanic')`.
- Alternatively, upload a CSV file and load it with `pd.read_csv()`.
- Inspect the data with `df.head()` and `df.info()`.

### Core pandas Operations

- Use `df.groupby('col').agg({'num_col': 'mean'})` for quick summaries.
- Join tables with `pd.merge(left, right, on='key')`.
- Reshape data with `df.pivot_table(values, index, columns, aggfunc='sum')`.

### Writing Reusable Code

- Wrap repetitive cleaning steps in a function:

  ```python
  def clean(df):
      # Add cleaning steps here.
      return df
  ```

- Use list comprehensions and loops for column-wise operations.
- Use conditionals when logic depends on data values.

### Visualization Quick Start

- Use `plt.hist(df['num_col'])` to show a distribution.
- Use `df.plot(kind='bar', x='cat', y='value')` to compare categories.
- Always label axes and add a descriptive title.

## Resources

- [Google Colab](https://colab.research.google.com/)
- [pandas documentation](https://pandas.pydata.org/docs/)
- [NumPy quickstart guide](https://numpy.org/doc/stable/user/quickstart.html)
- [Matplotlib gallery](https://matplotlib.org/stable/gallery/index.html)
