# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
Start the program.
### Step 2: 
Store the first and second point coordinates in l1 and l2.
### Step 3: 
Substitute the values in the distance formula  ![formula](/formula.JPG)
### Step 4: 
Priunt the distance value with two decimal points.
### Step 5: 
Stop the program.
### PROGRAM:
```
#Program to find the distance between two points.
#Developed by: 23006873
#RegisterNumber:PRASANNA V
import math
def calculate_distance(x1,x2,y1,y2):
    distance=math.sqrt((x2-x1)**2+(y2-y1)**2)
    return distance


x1=4
x2=10
y1=2
y2=6

result=calculate_distance(x1,x2,y1,y2)
print(f"{result:.2f}")
```


### OUTPUT:
![Screenshot 2023-11-18 145232](https://github.com/prasannavenkat01/DISTANCE-BETWEEN-TWO-POINTS/assets/150702500/a96921b9-ff0e-45eb-8ada-616f8b7e2a99)



### RESULT:
Thus the python program to find the distance between two points is executed successfully.
