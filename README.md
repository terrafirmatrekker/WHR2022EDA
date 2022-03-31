# World Happiness Report 2022 EDA

## Analyzing The World Happiness Report of 2022 (WHR22) for Code Louisville Data Analysis With Python

My project involves cleaning the current WHR22 followed by an EDA and various visualizations to highlight my findings.

## Features Used
*  Create and call at least 3 functions or methods, at least one of which must return a value that is used somewhere else in your code (I used a variety of methods via Pandas and created 2 custom functions to highlight mins and maxs)
*  Read data from an external file, such as text, JSON, CSV, etc, and use that data in your application (The data is from an Excel file but cleaned and exported as CSV)
*  Visualize data in a graph, chart, or other visual representation of data (I used Seaborn to create a Heatmap)
*  Use Plotly or Matplotlib to create charts/graphs of data (I used Plotly for a geographic representation & Matplotlib for a variety of visualizations)
*  Source data should not be modified/changed - clean data should be stored separately (Data was converted to a CSV for use and stored in a Gist)
*  Use a Jupyter notebook to document your data analysis (I used Google Colab for presentation and documentation)

## Directions
I strongly reccomend running the file in Colab itself. Simply click this [link](https://colab.research.google.com/drive/17R5ynkJiZqZRnS-oDhozSScbPdzcMkNg?usp=sharing)

You can also click the ipynb files in the repo this will open a preview and in the left-hand top corner you will see a button 'Open in Colab' Click the button and this will open the notebook so you can run the cells and see the report in action.

### Running in your Own Environment
If you have to run it in your environment make sure to have the following libraries installed in your Notebook so the project runs properly.

`#### Importing the Libraries Needed
import pandas as pd
import numpy as np
from urllib.request import urlretrieve

#### Importing Visualization Libraries Needed
import seaborn as sns
import matplotlib.pyplot as plt
import matplotlib.gridspec as gs
%matplotlib inline`

## **Data**

This report will examine the most recent [dataset](https://happiness-report.s3.amazonaws.com/2022/Appendix_2_Data_for_Figure_2.1.xls) which has been converted into a CSV and stored as a Gist [here](https://gist.github.com/terrafirmatrekker/474f3acc5b44322bc54fcc49870dcfd1).
