# Introduction to plotting

## Olav Vahtras

KTH

---

layout: false

## Matplotlib

- The standard 2D-plotting library in Python
- Production-quality graphs
- Interactive and non-interactive use
- Many output formats
- Flexible and customizable

---

## First example

### The absolute minimum  you need to know

* You have a set of points (x,y) on file

```
-3.141593 -0.000000
-3.013364 -0.127877
-2.885136 -0.253655
...
3.141593 0.000000
```

--

* How do you get to 

<img src="data/sin.png" height="250" />

--

---

* Import the plotting library
--

```python
import matplotlib.pyplot as plt
import numpy as np
```
* Load the data from file
--
```python
data = np.loadtxt('filename')
```
* Call the *plot* function
--
```
plt.plot(data[:, 0], data[:, 1])

* Show the result
--
```
plt.show()
```

* A common abbreviation (*de facto* standard)
--


##
