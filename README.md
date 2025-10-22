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
 import matplotlib.pyplot as plt
x1=[1,2,3]
y1=[2,4,1]
plt.plot(x1,y1,label='line1')
x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2,y2,label='line2')
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Two lines on same graph!')
plt.legend()
plt.show()
```
<img width="817" height="613" alt="image" src="https://github.com/user-attachments/assets/f2c7d098-59b3-4276-bd87-ea0901d36acd" />

```
import matplotlib.pyplot as plt
x=[1,2,3,4,5,6]
y=[2,4,3,5,1,6]
plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='red',markersize=10)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Some cool customizations!')
plt.show()
```

<img width="819" height="629" alt="image" src="https://github.com/user-attachments/assets/be94dfc1-4aef-4e83-8970-f1a18d0d4b67" />

```
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(yield_apples)
```

<img width="844" height="620" alt="image" src="https://github.com/user-attachments/assets/74f90cca-ffdd-4725-b44d-86abfa26d07b" />

```
years=[2010,2011,2012,2013,2014,2015]
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yield_apples)
```

<img width="817" height="608" alt="image" src="https://github.com/user-attachments/assets/235733d6-0a9c-4862-bdab-1bb260acfca7" />

```
years=range(2000,2012)
apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
grapes=[0.926,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896, ]
plt.plot(years, apples)
plt.plot(years, grapes)
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)')
plt.title('Crop Yields')
plt.legend(['Apples','grapes']);
```

<img width="815" height="613" alt="image" src="https://github.com/user-attachments/assets/f59307f2-f368-4359-9161-0e06cdb4078b" />

```
plt.figure(figsize=(14,6))
plt.plot(years,grapes,marker='o')
plt.title("Yield of grapes (tons per hectare)");
```

<img width="876" height="435" alt="image" src="https://github.com/user-attachments/assets/52eb87cb-702b-435d-8aa2-6680d41108e9" />

```
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
x=np.arange(0,10)
y=np.arange(11,21)
x
```
<img width="815" height="51" alt="image" src="https://github.com/user-attachments/assets/08076930-671e-41ba-b5fb-a2911dadc763" />

```
y
```
<img width="782" height="53" alt="image" src="https://github.com/user-attachments/assets/aa0222fc-5809-4195-9864-aea573a37006" />

```
plt.scatter(x,y,c='b')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')
```

<img width="793" height="616" alt="image" src="https://github.com/user-attachments/assets/3a6c4d09-c2c8-490e-845f-8ac99b8a6842" />

```
y=x*x
y
```

<img width="814" height="48" alt="image" src="https://github.com/user-attachments/assets/4b28734f-b7d3-4159-b00d-9584fc4ab549" />

```
plt.plot(x,y,'y*',linestyle='dashed',linewidth=2,markersize=12)
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('2d Diagram')
```

<img width="802" height="655" alt="image" src="https://github.com/user-attachments/assets/85e685ee-a06b-4208-8e5c-cd0488fb18d1" />

```
np.pi
```
<img width="755" height="44" alt="image" src="https://github.com/user-attachments/assets/11cb97a4-02c9-455f-b31b-e2ba70ac472d" />

```
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x,y)
plt.show()
```
<img width="796" height="599" alt="image" src="https://github.com/user-attachments/assets/8ead5bc5-6474-44bd-8a07-f48901f14e83" />

```
import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color='red')
plt.fill_between(x,y2,color='green')
```

<img width="793" height="609" alt="image" src="https://github.com/user-attachments/assets/e0ec0023-6636-4c11-a54d-f8b475a43e3e" />

```
import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color='blue')
plt.fill_between(x,y2,color='green')

plt.plot(x,y1,color='red')
plt.plot(x,y2,color='black')
plt.legend(['y1','y2'])
```

<img width="796" height="582" alt="image" src="https://github.com/user-attachments/assets/34af8f8f-3024-48c7-a20d-542656fe5309" />

```
import matplotlib.pyplot as plt
height=[10,24,36,40,5]
names=['one','two','three','four','five']
c1=['red','green']
c2=['b','g']
plt.bar(names,height,width=0.8,color=c1)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My bar chart!')
plt.show()
```

<img width="795" height="618" alt="image" src="https://github.com/user-attachments/assets/a21fb3e4-09cd-4e62-aa0b-14ef7276ce20" />

```
x=[2,8,10]
y=[11,16,9]
x2=[3,9,11]
y2=[6,15,7]
plt.bar(x,y,color='r')
plt.bar(x2,y2,color='g')
plt.title('Bar graph')
plt.ylabel('Y axis')
plt.xlabel('Xaxis')
plt.show()
```

<img width="751" height="624" alt="image" src="https://github.com/user-attachments/assets/88269a15-2c5f-446d-be35-2d7dd376e812" />

```
import matplotlib.pyplot as plt
ages=[2,5,70,40,30,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
range=(0,100)
bins=10
plt.hist(ages,bins,range,color='lightblue',histtype='bar',rwidth=0.8)
plt.xlabel('age')
plt.ylabel('No. of people')
plt.title('My histogram')
plt.show()
```

<img width="783" height="597" alt="image" src="https://github.com/user-attachments/assets/1e77611d-a8a2-43ed-9b0b-22505079a09f" />

```
import matplotlib.pyplot as plt
import numpy as np
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
```

<img width="788" height="510" alt="image" src="https://github.com/user-attachments/assets/5cab04fd-a737-4f29-a2ea-856c5d190928" />

```
fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')
```
<img width="809" height="616" alt="image" src="https://github.com/user-attachments/assets/e90fa877-6db0-4741-8fc4-e03837ef83ba" />

```
labels='Python','C++','Ruby','Java'
sizes=[215,130,245,210]
colors=['gold','yellowgreen','lightcoral','lightskyblue']
explode=(0,0.4,0,0.5)
plt.pie(sizes,explode=explode,labels=labels,colors=colors,autopct='%1.1f%%',shadow=True)
plt.axis('equal')
plt.show()
```
<img width="776" height="532" alt="image" src="https://github.com/user-attachments/assets/6e4376e2-3ff5-463b-a2e3-eceddaca4da3" />

```
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels=activities,colors=colors,startangle=90,shadow=True,explode=(0,0,0.1,0),radius=1.2,autopct='%1.1f%%')
plt.legend()
```

<img width="747" height="582" alt="image" src="https://github.com/user-attachments/assets/d34de337-c550-40a8-8b89-c72506efe88e" />


# Result:
 Thus, The implementation of data visualization using matplotlib has been successfully verified.
