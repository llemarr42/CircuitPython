# CircuitPython
 The follwing files are my first foray into CircuitPython.
## Table of Contents
* [Table of Contents](#TableOfContents)
* [Hello_CircuitPython](#Hello_CircuitPython)
* [CircuitPython_Servo](#CircuitPython_Servo)
* [CircuitPython_LCD](#CircuitPython_LCD)
---

---


## Hello_CircuitPython

### Discription

I made the metro express light flash red and green/blue

### Code
```python
import board
import neopixel
import time

dot = neopixel.NeoPixel(board.NEOPIXEL, 1)

while True:
    print("Make it blue!")
    dot.fill((0,0,255))
    time.sleep(.5)
    print("Make it red!")
    dot.fill((255,0,0))
    time.sleep(.5)
```
### Image

<img src="https://github.com/llemarr42/CircuitPython/blob/main/hello%20circuitpython.png?raw=true" width="250">

### Reflection

I learned about the dot.fill function and how you can change the proportions of each of the primary colors to make any color you want.

---

## CircuitPython_Servo

### Description & Code

```python
Code goes here

```

### Evidence

### Images

### Reflection


## CircuitPython_LCD

### Description & Code

```python
Code goes here

```

### Evidence

### Images

### Reflection
