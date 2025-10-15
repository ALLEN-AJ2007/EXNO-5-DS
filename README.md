# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
```
 import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
# visulisation in matplotlib
#line plot
x=[1,2,3,4]
y=[10,20,25,30]
plt.plot(x,y,color='violet')
plt.title("Line Plot")
plt.show()
```
<img width="1045" height="670" alt="Screenshot 2025-10-15 204739" src="https://github.com/user-attachments/assets/0f667400-e488-45c1-badc-fac0f921d9ca" />

```
#bar plot
catagories=['A','B','C']
values=[10,15,30]
plt.bar(catagories,values)
plt.title("Bar chart")
plt.show()
```
<img width="971" height="680" alt="Screenshot 2025-10-15 204752" src="https://github.com/user-attachments/assets/7759e7bc-a705-4dd6-88e6-ff2ca135658b" />

```
#Histogram
data=[1,2,3,4,5,5,6,6,7,5,4,3,2,1]
plt.hist(data,bins=15,color='red')
plt.title("Histogram")
plt.show()
```
<img width="1003" height="662" alt="Screenshot 2025-10-15 204803" src="https://github.com/user-attachments/assets/5db2a3bc-7928-4ce9-994e-788608a32797" />


```
#Scatter plot
x=[1,2,3,4]
y=[10,20,30,35]
plt.scatter(x,y)
plt.title("Scatter plot")
plt.show()
```
<img width="947" height="677" alt="Screenshot 2025-10-15 204814" src="https://github.com/user-attachments/assets/4e73cb7f-7929-4216-bd47-1f3df0000241" />
```
#Pie Chart
sizes=[20,30,50]
labels=['A','B','C']
plt.pie(sizes,labels=labels)
plt.title("Pie Chart")
plt.show()
```
<img width="1041" height="653" alt="image" src="https://github.com/user-attachments/assets/c42befe5-b954-4823-bcd4-80900d029dd6" />



<img width="933" height="658" alt="Screenshot 2025-10-15 204854" src="https://github.com/user-attachments/assets/b9c0975f-b97e-46e5-8d1e-ed066df25a15" />
# Result:
 
Matplotlib provides versatile plotting functions like plot(), bar(), scatter(), hist(), pie(), boxplot(), fill_between(), imshow(), and 3D plotting to visualize data in line, bar, scatter, histogram, pie, box, area, heatmap, and spatial formats.
