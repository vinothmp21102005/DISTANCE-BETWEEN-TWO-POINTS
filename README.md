# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
import math
### Step 2:
store the coordinates in variable 
### Step 3: 
Substitute the values in the distance formula  ![formula](/formula.JPG)
### Step 4: 
store the result in a variable
### Step 5:
print the output in decimal format 
### PROGRAM:
  ```
  import math
first_point = [4, 2]
second_point = [10, 6]
distance = math.sqrt((second_point[0] - first_point[0])**2 + (second_point[1] - first_point[1])**2)
print(f"{distance:.2f}")

  ```


### OUTPUT:
![alt text](<Screenshot 2024-03-12 205757.png>)

### RESULT:
Thus the program is successfully executed