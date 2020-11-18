# CircuitPython


---


## Hello CircuitPython

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
