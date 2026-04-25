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
16. 


