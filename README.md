# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: Import the path
### Step 2: Assign the values of two points
### Step 3: Substitute the values in the distance formula
√((x_2-x_1)²+(y_2-y_1)²) 
### Step 4: Print the values
### Step 5: End the program
### PROGRAM:
```
#Program to find the distance between two points.
#Developed by:Yuva Sree M 
#RegisterNumber:23013768
import math
def distance(x_1,y_1,x_2,y_2):
   dx=x_2-x_1
   dy=y_2-y_1
   d=math.sqrt(dx**2+dy**2)
   return d
x_1=4
y_1=2
x_2=10
y_2=6
d=distance(x_1,y_1,x_2,y_2)
print(round(d,2))
```
  


### OUTPUT:
![OUTPUT](distance.png)


# RESULT:
COMPLETED.