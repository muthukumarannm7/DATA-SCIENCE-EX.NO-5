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

LINE CHART:
```
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
marks = [13,45,63,78]
student=['ABC','QOR','EFB','TOB']
plt.plot(marks,student)
plt.xlabel('Marks')
plt.ylabel('Student Name')
plt.show()

student = ['A','B','C','D']
attendence = [90,85,73,88]
plt.plot(student,attendence)
plt.xlabel('Attendence')
plt.ylabel('student Name')
plt.show()
```
<img width="739" height="755" alt="image" src="https://github.com/user-attachments/assets/9ecfcb75-6db3-49a1-90f3-e50ef97c6f97" />

SCATTER PLOT:
```
x=[10,20,30,40,50]
y=[100,200,300,400,500]
plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
plt.show()
x=np.arange(0,15)
y=np.arange(0,15)
x
y
plt.scatter(x,y,c='r')
plt.xlabel('X axis')
plt.ylabel('y axis')
plt.title('Scatter plot')
plt.show()
```
<img width="685" height="739" alt="image" src="https://github.com/user-attachments/assets/b6ca136b-c549-4d84-a62a-adb6a3c4bb77" />

PIE CHART:
```
act=['eat','sleep','work','play']
slices=[3,7,8,6]
color=['r','y','g','b']
plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
feedback=['Good','excellent','Perfect','Ok']
slices=[4,10,3,8]
color=['y','r','b','g']
plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
```
<img width="705" height="689" alt="image" src="https://github.com/user-attachments/assets/689d9a02-11b0-413d-9ea7-c2dd6243211d" />

AREA CHART:
```
x = [1, 2, 3, 4, 5]
y1 = [10, 12, 14, 16, 18]
y2 = [5, 7, 9, 11, 13]
y3 = [2, 4, 6, 8, 10]
plt.fill_between(x, y1, color='blue')
plt.fill_between(x, y2, color='green')
plt.plot(x, y1, color='red')
plt.plot(x, y2, color='black')
plt.legend(['y1','y2'])
plt.show()
```
<img width="619" height="358" alt="image" src="https://github.com/user-attachments/assets/e0df9f8a-2e23-47bf-abbd-accc63bfe83f" />

BAR CHART:
```
height = [10, 24, 36, 40, 5]
names = ['one', 'two', 'three', 'four', 'five']
c1=['red', 'green'] 
c2=['b', 'g']
plt.bar (names, height, width=0.8, color=c1)
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('My bar chart!')
plt.show()
```
<img width="548" height="401" alt="image" src="https://github.com/user-attachments/assets/aed1429e-2ea7-4f35-8ee0-d7d577449161" />

HISTOGRAM:
```
x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x, bins = 10, color='blue', alpha=0.5)
plt.show()
```
<img width="532" height="349" alt="image" src="https://github.com/user-attachments/assets/ab85d523-c891-48d9-ba88-ec7eb24b55e4" />

BOX PLOT:

```
np.random.seed(0)
data=np.random.normal(loc=0, scale=1, size=100)
data

<img width="637" height="371" alt="image" src="https://github.com/user-attachments/assets/3d59cf87-3f9f-474a-84f9-ce875cdad14b" />

fig, ax= plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')
```
<img width="612" height="425" alt="image" src="https://github.com/user-attachments/assets/4bbb3780-e335-4da5-ac86-2992ef918bbd" />









# Result:
 Thus, all the data visualization techniques of matplotlib has been implemented.
