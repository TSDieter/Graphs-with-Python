## Welcome to GitHub Pages

### Vectors with Python

This is an method how to use vectors with python and how to display them

```markdown
Syntax highlighted code block

import os
import math
import numpy as np

#Solve Linear Equations with Python

#Array
A = np.array([[3, -9], [2,4]])

#print(A)

#dasselbe mit einem Vektor namens b

b = np.array([-42,2])

Lösung = np.linalg.solve(A,b)

print(Lösung)

#---------------------------------#
#Equation is 
#x-2y-z=6
#2x+2y=z+1
#2z-1=y+x

M = np.array([[1,-2, -1],[2,2,-1],[-1,-1,2]])
print("Die Gleichung Ist")
#print(M)
c = np.array([6,1,1])
y = np.linalg.solve(M,c)
print(y)

#Vektoren in Python
# A = G

#x = 10

x = 20

while x > 0:
   print(x)
   x -=1

#Dimensionen
G = [2, 3, 4]
H = [4, 9, 16]

for z in zip(G, H):
    for z in zip(G, H):
        print(z)

for a, b in zip(G, H):
    print(G, H)

    def vectorAdd (G, H):
        return [G+H for a, b in zip(G, H)]

        vectorAdd([1, 4], [2, -2])
```
