# 📐Curve
### A  module using matplotlib for ploting Curves (Ellipse , Hyperbola , Parabola).

### Install package
```py
pip install Curvify
```
# Ellipse:
```py
import curve as cv
cv=cv.ellipse(3,3,5,5)
cv.draw()
print(cv.center) # output: (3,3)
```
![curve](https://github.com/Cjenf/Curvify/assets/105590093/34b05313-e4d9-456b-a270-77fe1681902c)
# Parabola
```py
import curve
import numpy as np

p=curve.Parabola(np.linspace(-10, 10, 100), 1,1,1,1,"up",True)
p.draw()
print(p.axis_equation) # output: x-1=0
```
