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
import curve as cv
import numpy as np

p=cv.Parabola(np.linspace(-10, 10, 100), 1,1,1,1,"up",True)
p.draw()
print(p.axis_equation) # output: x-1=0
```
![螢幕擷取畫面 2024-06-20 135000](https://github.com/Cjenf/Curvify/assets/105590093/70514161-6bc5-4df7-9e05-62d481c54a9b)
# Hyperbola
```py
import curve as cv
import numpy as np
h=curve.Hyperbola(np.linspace(0,10,100),1,2,3,4,"left")
h.draw()
print(h.vertex) # output: ((5, 4), (1, 4))
```
![螢幕擷取畫面 2024-06-20 141706](https://github.com/Cjenf/Curvify/assets/105590093/9f19759c-d58a-4901-a823-49b1e9086438)
