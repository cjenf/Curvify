# Curvify
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

# Parabola
```py
import curve as cv
import numpy as np

p=cv.Parabola(np.linspace(-10, 10, 100), 1,1,1,1,"up",True)
p.draw()
print(p.axis_equation) # output: x-1=0
```
# Hyperbola
```py
import curve as cv
import numpy as np
h=curve.Hyperbola(np.linspace(0,10,100),1,2,3,4,"left")
h.draw()
print(h.vertex) # output: ((5, 4), (1, 4))
```
