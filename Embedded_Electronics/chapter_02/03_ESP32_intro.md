# ESP32_heatbeat

Let's start on our programming journey by using the `ESP32` to make the LED turn on and off.


**TODO** instructions on getting `Micro Python` set up on the ESP32.

Now, connect the the circuit as seen below
**TODO picture of circuit**

Connect to the ESP32 micropython terminal and paste the code below:

```python
import time
from machine import Pin, Timer

led=Pin(2,Pin.OUT)

while True:
  led.value(1)
  time.sleep(0.5)
  led.value(0)
  time.sleep(0.5)
```

Let's walk through this program:
1. First we import the necessary Python libraries.  `Libraries` are pre-written code that are designed for use in other programs.
2. Next we make a LED `object` and tell MicroPython that Pin 2 should be an `output` type pin.
3. Then we see the ```while True``` code which means the code below it will run forever until the program is stopped.
4. The code running forever has 4 steps:
   1. Turn **on** the LED by setting it's value to 1
   2. Wait for 0.5 seconds by `sleeping`
   3. Turn **off** the LED by setting it's value to 0
   4. Wait for another 0.5 seconds by `sleeping`

Having a LED periodically blink is called a `heartbeat` and helps tell us what the ESP32 is still functioning.  If we include a `heartbeat` in our program and the LED stops blinking then we know there was a serious problem with our program.

#esp32 #blinky #micro_python #library #object #output #heartbeat