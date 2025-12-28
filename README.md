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
 Include the necessary coding and corresponding screenshots
 NAME : M.SOMESHVARAN REG NO : 25018410

  import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt

# LINE PLOT
marks=[13,45,63,78]
student=['ABC','QOR','EFB','TOB']
plt.plot(marks,student)
plt.xlabel('Marks')
plt.ylabel('Student name')
plt.show()
student=['A','B','C','D']
attendence=[90,85,73,88]
plt.plot(attendence,student)
plt.xlabel('Attendence')
plt.ylabel('Student name')
plt.show()
<img width="821" height="551" alt="image" src="https://github.com/user-attachments/assets/cb597e49-59f8-415b-a47e-1da7c62b8494" />

<img width="800" height="556" alt="image" src="https://github.com/user-attachments/assets/be704416-a20c-476b-9030-5d5278a7dccc" />

# SCATTER PLOT
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
<img width="743" height="522" alt="image" src="https://github.com/user-attachments/assets/dbf5c17b-3e34-4b14-81c0-8daa692f86d0" />

<img width="758" height="560" alt="image" src="https://github.com/user-attachments/assets/a69cfbb8-4526-4b24-bd11-79aebbd0b2d7" />

# PIE CHART
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

<img width="701" height="517" alt="image" src="https://github.com/user-attachments/assets/efe792a7-ad13-41fb-9062-9c8b5d46092b" />

<img width="704" height="524" alt="image" src="https://github.com/user-attachments/assets/f09b81eb-ab7f-4324-aaa3-9f1bd13973e9" />

# AREA CHART
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

<img width="749" height="528" alt="image" src="https://github.com/user-attachments/assets/e85f9d8f-ecc3-4f28-ab3b-f250d9d0e358" />

# BAR CHART
height = [10, 24, 36, 40, 5]
names = ['one', 'two', 'three', 'four', 'five']
c1=['red', 'green']
c2=['b', 'g']
plt.bar (names, height, width=0.8, color=c1)
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('My bar chart!')
plt.show()

<img width="786" height="572" alt="image" src="https://github.com/user-attachments/assets/b7b2c7f8-8604-4cf1-b6f7-f1a08f97459f" />

# HISTOGRAM
x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x, bins = 10, color='blue', alpha=0.5)
plt.show()

<img width="730" height="524" alt="image" src="https://github.com/user-attachments/assets/f727e7e1-50a2-4bf0-844e-fa892391d2ea" />

# BLOX PLOT
np.random.seed(0)
data=np.random.normal(loc=0, scale=1, size=100)
data

<img width="737" height="449" alt="image" src="https://github.com/user-attachments/assets/e54f5553-4dfe-4ccc-9bc9-ab2c521e51b7" />

fig, ax= plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')

<img width="772" height="593" alt="image" src="https://github.com/user-attachments/assets/d07f31fc-6088-4513-a1d9-a33679a12fe2" />
# Result:
 Include your result here
