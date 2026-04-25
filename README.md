# Experiment-17
# Aim
Basic Charts and Visual Encoding.
# Theory
1. Basic charts and visual encoding in Python involve using graphs like bar, line, pie, scatter, and histogram charts with colors, sizes, shapes, and labels to represent and communicate data effectively.
2. import matplotlib.pyplot as plt – Imports Matplotlib’s plotting module and gives it the alias plt to create charts and graphs.
3. import seaborn as sns – Imports Seaborn and gives it the alias sns to create attractive statistical visualizations.
4. import pandas as pd – Imports Pandas and gives it the alias pd to handle and analyze data using DataFrames.
5. pd.DataFrame(data) – Creates a Pandas DataFrame (table format) from the given data for easy data analysis and manipulation in Python.
6. plt.plot(df['Days'], df['Study_Hours'], marker='o') – Creates a line graph of Days vs Study_Hours with circle markers on each data point.
7. plt.title("sara") – Adds the title "sara" to the graph.
8. plt.xlabel("Days") – Labels the x-axis as "Days".
9. plt.ylabel("Study Hours") – Labels the y-axis as "Study Hours".
10. plt.show() – Displays the graph on the screen.
11. plt.figure(figsize=(7,4)) – Creates a new graph figure with width 7 inches and height 4 inches.
12. plt.plot(df['Days'], df['Study_Hours'], marker='o', color='green', label='Study Hours') – Plots a green line graph of Days vs Study_Hours with circle markers and label.
13. plt.plot(df['Days'], df['Marks'], marker='s', color='red', label='Marks') – Plots a red line graph of Days vs Marks with square markers and label.
14. plt.legend() – Displays a legend on the graph to identify different plotted data lines or labels.
15. plt.bar(df['Days'], df['Marks'], color='red', edgecolor='black') – Creates a red bar chart of Days vs Marks with black borders around each bar.
16. plt.grid(axis='y', linestyle='--', alpha=0.5) – Adds dashed horizontal grid lines on the y-axis with 50% transparency to improve chart readability.
17. for bar in bars: – Loops through each bar in the bar chart.
18. y = bar.get_height() – Gets the height (value) of the current bar.
19. plt.text(bar.get_x() + bar.get_width()/2, y, str(y), ha='center', va='bottom') – Displays the bar value as text centered above each bar.
20. plt.grid(axis='y') – Adds grid lines only along the y-axis to make the graph easier to read.
21. import numpy as np – Imports the NumPy library with alias np for numerical calculations and array operations in Python.
22. np.arange(len(df['Days'])) – Creates an array of positions for bars based on the number of Days values.
23. width = 0.36 – Sets the width of each bar to 0.36.
24. plt.bar(x - width/2, df['Study_Hours'], width, label='Study Hours') – Creates bars for Study_Hours shifted left for side-by-side comparison.
25. plt.bar(x + width/2, df['Marks'], width, label='Marks') – Creates bars for Marks shifted right for side-by-side comparison.
26. plt.xticks(x, df['Days']) – Sets x-axis tick positions as x and labels them with Days values.
27. np.mean(marks) – Calculates and returns the average (mean) value of the marks data.
28. plt.hist(marks, bins=3, color='skyblue', edgecolor='black') – Creates a histogram of marks with 3 bins, skyblue bars, and black borders.
29. plt.axvline(mean_value, color='red', linestyle='--', linewidth=2, label='Mean') – Draws a red dashed vertical line at the mean value with label "Mean".
30. plt.scatter(df['Study_Hours'], df['Marks']) – Creates a scatter plot showing the relationship between Study_Hours and Marks.
31. df['Result'] = ['Fail','Pass','Fail','Pass','Pass'] – Creates a new Result column with Fail or Pass values.
32. colors = ['red' if r=='Fail' else 'green' for r in df['Result']] – Creates a color list where Fail is red and Pass is green.
33. plt.scatter(df['Study_Hours'], df['Marks'], c=colors) – Creates a scatter plot of Study_Hours vs Marks using the assigned colors.
34. sns.lineplot(x='Day', y='Sales', data=df, errorbar=None) – Creates a Seaborn line chart of Day vs Sales from the DataFrame without showing error bars.
35. sns.barplot(x='Day', y='Sales', data=df, errorbar=None) – Creates a Seaborn bar chart of Day vs Sales from the DataFrame without showing error bars.
36. sns.histplot(df['Sales'], bins=5) – Creates a Seaborn histogram of the Sales column with 5 bins to show data distribution.
37. sns.scatterplot(x='Sales', y='Profit', data=df) – Creates a Seaborn scatter plot showing the relationship between Sales and Profit from the DataFrame.
# Conclusion
Basic Charts and Visual Encoding in Python help represent data clearly using graphs such as line charts, bar charts, histograms, and scatter plots. Libraries like Matplotlib and Seaborn make it easy to create attractive and informative visualizations. Colors, labels, markers, sizes, and legends improve understanding by highlighting patterns, trends, comparisons, and relationships in the data. These charts are very useful in data analysis, reporting, and decision-making.








