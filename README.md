# EXPERIMENT - 17

Experiment: Data Visualization and Visual Encoding

 AIM

To learn and implement basic data visualization techniques and visual encoding—specifically line charts and bar charts—using Python's Matplotlib and Seaborn libraries to identify and compare trends in a dataset.

Theory for All Graphs:

A. Basic Line Chart (Trend Analysis)
Purpose: Used to visualize the relationship between two continuous variables, most commonly showing how a specific metric changes over a chronological sequence (e.g., "Study Hours Over Days").
Visual Encoding:
Axes: The X-axis typically represents the independent variable (Days), while the Y-axis represents the dependent variable (Study Hours).
Markers: The parameter marker='o' encodes individual data points with circles, making the exact value at each interval distinct.
Lines: Connect the markers to highlight the overall "trend" or direction of movement in the data.

B. Advanced Line Chart (Multi-Series Comparison)

Purpose: Used to compare multiple data series simultaneously on a single set of axes to find correlations (e.g., comparing "Study Hours" vs. "Marks").
Visual Encoding:
Color/Label Encoding: Different colors are automatically assigned to each line. The label parameter and plt.legend() function encode these colors into a key, allowing the viewer to distinguish between different datasets at a glance.
Scaling: By plotting them together, it becomes visible if an increase in one variable (hours) corresponds to an increase or decrease in another (marks).

C. Bar Chart (Categorical Comparison)
Purpose: Used for comparing discrete categories. While line charts show trends, bar charts are superior for emphasizing the magnitude of specific values across different groups.
Visual Encoding:
Length/Height: The primary encoding is the height of the bar, which corresponds directly to the numerical value (e.g., "Marks").
Aesthetics: Parameters like color='red' and edgecolor='black' provide high contrast for better visibility.
Grid Lines: Using plt.grid(axis='y') provides horizontal reference points that make it easier for the human eye to map the top of a bar to its corresponding value on the Y-axis.

Conclusion:

The experiment demonstrates that visual encoding is an essential tool in data science. By selecting the correct chart type—Line Charts for trends and Bar Charts for categorical comparisons—and utilizing aesthetic elements like markers, legends, and colors, complex numerical data is transformed into an intuitive format that clearly highlights patterns such as the correlation between time spent studying and academic performance.
