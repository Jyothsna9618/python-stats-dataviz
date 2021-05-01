>
> A visitor to New York City asked a passerby for 
> directions to the city's famous classical music venue:
>
> Visitor: Excuse me, how do I get to Carnegie Hall?
>
> Passer by: Practice, practice, practice!
> 


## Course Information
- Summary
    - Statistical Analysis, Data Visualization, and Python Programming all-in-one with Hands-on Practices.
- Online Class WebEx
    - http://umbc.webex.com/meet/jaywang
- About the instructor
    - https://wcj365.gitee.io/
- Textbook 
    - Python for Data Analysis by Wes McKinny **Second Edition**
- Development Environment
    - deepnote.com
    - Google Colab

## Tutorials
- [W3C School Python Tutorial](https://www.w3schools.com/python/default.asp)
- [4-hour Beginner's Python for Data Science Training Video](https://www.youtube.com/watch?v=r-uOLxNrNk8&feature=emb_title&fbclid=IwAR0qJPcqezRICXAx1TAR28Ca5hrw_H9HkMOzyUWPFhyer4G2Lxxs4YdwYIY)

## Three Ways to Run Python Code and Free Cloud-based Tools
- Use Interactive Python Shell (Interpreter) 
    - python.org 
    - No registration is required
- Run Python Scripts through Command Line
    - pythonanywhere.com
    - Requires account registration
    - Need basic Linux familiarity
- Use Jupyter Notebooks
    - Google Colab
        - Plus: Seemless integration with GitHub
    - deepnote.com 
        - Plus: Acess to Linux terminal to run Python Scripts  
    - Kaggle.com
        - Plus: Data science community with public datasets and notebooks for learning 

## Four Levels of Python Code
https://m.facebook.com/story.php?story_fbid=2596321403939440&id=1815765878661667
1. Syntax (most basic programming requirements)
2. Idiom (use of .join for string concatenation)
3. Design Patterns (best practices and approaches to common problems and issues)
4. Architectural (Overall project structure)

Most books and courses teach level 1 and 2 and rarely touch on level 3 and 4.

## Four Paradigms of Python Programming
https://blog.newrelic.com/engineering/python-programming-styles/
- Imperative
- Procedural
- Object-oriented
- Functional

## Four Major Components of a Data Science Project and Your Responsibility
- **Written Code** - Solely your responsibility - Make sure it is clean, correct, and commented (3C rule)
- **Source Data** - Primary data is your responsibity. You have no control over secondary data so be careful in the selection and cleansing.
- **Existing Libraries** - You have no control on existing libraries/algothorithms so be careful in selecting and using them.
- **Interpretation of Results** - Be careful about what is objective and what is subjective and what data exhibit and what experts know.

The one thing you have absolute control is **the code you write**. Make sure don't write bad code (complicated, incorrect, and undocumented code), so-called **spaghetti code**.

[Wikipedia's Definition of Spaghetti Code](https://en.wikipedia.org/wiki/Spaghetti_code): 

> *"Spaghetti code is a pejorative phrase for unstructured and difficult-to-maintain source code. 
> Spaghetti code can be caused by several factors, such as volatile project requirements, 
> lack of programming style rules, and insufficient ability or experience."*

## Jupyter Notebooks
The name Jupyter comes from the fact that it supports writing code in three popular languages:
- **Ju**lia
- **Pyt**hon
- **R**

Julia and R are popular for statistical analysis and data science. Python is a more generic programming language that happens to be popular in data science as well, though Python is good for all kinds of development, not just data science.

## Data Visualization Six Steps
1. Define Problem and Ask Questions
2. Define Data Source and Elements
3. Tidy up Data (Normalize "messy" data so that is is "Tidy". )
4. Summarize Data (Summarize/Tablulate, descriptive statistics)
5. Visualize Data (static and interactive)
6. Interpret and Communicate Results

Check out this [paper](https://www.jstatsoft.org/article/view/v059i10) for data tidying.

All Six steps must be guided by domain knowledge, principles, and purposes. 

## Data Visualization - Plots/Charts
- Univariate
   - Categorical Variable 
       - Frequency table
       - Bar chart (x=Categories, y=Count)
       - Pareto Chart (sorted + accumulated %)
       - Pie Chart (Avoid it when there are t0o many categories)
   - Numerical Variable (discrete or continuous)
       - Histogram - frequency distribution 
       - Boxplot - five-number summary statistics (centrality and dispersion)
       - Line Chart - trend over time
       - Area Chart - Trend over time
   - Textual Variable/Data
       - Wordcloud
- Multivariate
   - Two categorical variables 
       - Contingency table, pivot table 
       - Stacked Bar Chart (one bar on top of the other)
       - Grouped Bar Chart (one bar next to each other)
   - Two numerical variables (correlation)
       - 2D Scatter Plot
       - 3D scatter plot
       - Bubble Chart (Scatter plot with varying size of dots based on the third numerical variable)
       - Motion Chart (Scatter plot with time frame for playback)
       - Scatter Plot with varying colors and Shapes of marks reflecting additional categorical variables (dimensions)
       - Line chart with multiple lines differentiated by color
   - One Numerical and one categorical variable
       - Bar chart (x=categories of the categorical variable, y=statistics of the numerical variable)
       - Statistics include mean, min, max, median, ...

## References
- ["Scipy Lecture Notes](http://scipy-lectures.org/index.html)
- [Data Analysis and Visualization with Python for Social Scientists](https://datacarpentry.org/python-socialsci/)
- [Python for Social Science](https://gawron.sdsu.edu/python_for_ss/course_core/book_draft/index.html)
- [Interactive Python Tutorial](http://littlecolumns.com/learn/python/)
- [W3C School Python Tutorial](https://www.w3schools.com/python/default.asp)
- [Practical Data Science for Journalists and Everyone Else](https://investigate.ai/)
- [Markdown Cheatsheet](https://www.markdownguide.org/cheat-sheet/)
- [Github Flavored Markdown](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)
- [AP Statistics Tutorial](https://stattrek.com/tutorials/ap-statistics-tutorial.aspx)
- [Practice Python](https://www.practicepython.org/)
- [Python Exercises, Practice, Solution](https://www.w3resource.com/python-exercises/)
- [4-hour Beginner's Python for Data Science Training Video](https://www.youtube.com/watch?v=r-uOLxNrNk8&feature=emb_title&fbclid=IwAR0qJPcqezRICXAx1TAR28Ca5hrw_H9HkMOzyUWPFhyer4G2Lxxs4YdwYIY)
- [Free Book: Python Data Science Handbook by Jake Vanderplas](https://github.com/jakevdp/PythonDataScienceHandbook)
- [A Visual Intro to NumPy and Data Representation](http://jalammar.github.io/visual-numpy/)
- [10 Minutes to Pandas](https://pandas.pydata.org/pandas-docs/stable/user_guide/10min.html)
- [A Gentle Visual Intro to Data Analysis in Python Using Pandas](http://jalammar.github.io/gentle-visual-intro-to-data-analysis-python-pandas/)
- [Summarising, Aggregating, and Grouping data in Python Pandas](https://www.shanelynn.ie/summarising-aggregation-and-grouping-data-in-python-pandas/)
- [Visualizing Pandas' Pivoting and Reshaping Functions](http://jalammar.github.io/visualizing-pandas-pivoting-and-reshaping/)
- [Data Visualization with Python](https://www.shanelynn.ie/data-visualisation-in-python-pycon-dublin-2018-presentation/)
- [From Data to Viz](https://www.data-to-viz.com/)
- [Data Visualization Best Practices](https://mode.com/analytics-dispatch/data-visualization-best-practices/)
- [Introduction to Exploratory Data Analysis in Python.ipynb](https://github.com/ilyagerner/pandas/blob/master/Introduction%20to%20Exploratory%20Data%20Analysis%20in%20Python.ipynb)
- [Object-Oriented Programming in Python vs Java](https://realpython.com/oop-in-python-vs-java/)
- [Ask, Acquire, Analyze, Apply, Announce, Assess](https://qcc.qlik.com/mod/resource/view.php?id=21115) 
- [A First Course in Data Science](https://arxiv.org/pdf/1905.03121.pdf)
