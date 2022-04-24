# 1.1 First circuit: LED's

Electronics are made up of `circuits` which are <ins>**just a bunch of electronics parts connected with wires**</ins>.

Let's build our first circuit:  an **LED circuit**.  This circuit has **4** components.  Take out component kit **01** that includes:

- `Breadboard`: Used for prototyping electronics circuits.  Each hole in the short horizontal rows are connected together.  Each hole in the long vertical rows (<span style="color:blue">**blue**</span> and <span style="color:red">**red**</span>) are connected together.


```{image} ../images/ch01/breadboard.png
:alt: breadboard
:class: bg-primary mb-1
:width: 300px
:height: 300px
``` 
```{image} ../images/ch01/breadboard_connections.png
:alt: breadboard connections
:class: bg-primary mb-1
:width: 300px
:height: 300px
```

- `LED`: emits light when electricity flows through it <br/>
```{image} ../images/ch01/led.png
:alt: led
:class: bg-primary mb-1
:width: 100px
:height: 200px
:align: center
```

- `Resistors`: limit the amount of electricity that can flow <br/>
```{image} ../images/ch01/resistors.png
:alt: resistor
:class: bg-primary mb-1
:width: 250px
:height: 200px
:align: center
```
- `Espotek Labador`: We will use this as a source of power for the circuit
```{image} ../images/ch01/espotek_labador.png
:alt: Espotek Labador
:class: bg-primary mb-1
:width: 300px
:height: 200px
:align: center
```

## Lab
### Step 1
Plug the Espotek Labador into the breadboard so that the 2 pins go into the <span style="color:red">**red**</span> and <span style="color:blue">**blue**</span> rows:
```{image} ../images/ch01/lab/espotek_back.png
:alt: back of espotek
:class: bg-primary mb-1
:width: 300px
:height: 300px
``` 
```{image} ../images/ch01/lab/espotek_insertion.png
:alt: inserting espotek
:class: bg-primary mb-1
:width: 300px
:height: 300px
``` 
```{image} ../images/ch01/lab/p1.png
:alt: attached to breadboard
:class: bg-primary mb-1
:width: 300px
:height: 300px
``` 

### Step 2
Plug in the USB cable from the Labador to your computer and you should see LED's on the board turn on.
```{image} ../images/ch01/lab/p2.png
:alt: USB plugged in
:class: bg-primary mb-1
:width: 400px
:height: 400px
``` 

### Step 3
Insert one leg of the <span style="color:blue">**blue resistor**</span> into the <span style="color:red">**red**</span> column of the breadboard.  Insert the other leg of the resistor into any row:
```{image} ../images/ch01/lab/p3.png
:alt: Add resistor
:class: bg-primary mb-1
:width: 400px
:height: 400px
``` 

### Step 4
Insert the **long** leg of the LED into the same row as the resistor.  The other LED leg goes to the <span style="color:blue">**blue**</span> column of the breadboard:

```{image} ../images/ch01/lab/p4.png
:alt: Add led
:class: bg-primary mb-1
:width: 400px
:height: 400px
``` 

Congratulations on making your first circuit!  

### Step 5
Now let's do a little experiment: take the `LED` out of the `breadboard` and flip it around.  Notice what happens...
````{dropdown} See result
    :container: + shadow
    :title: bg-primary text-white font-weight-bold

```{image} ../images/ch01/lab/p5.png
:alt: LED reversed
:class: bg-primary mb-1
:width: 400px
:height: 400px
``` 

LED's are part of a family of electronic parts called `diodes` which only allow electricity to flow in one direction.  They will be very useful for various applications.

````

### Step 6
Let's try another experiemnt and replace the resistor. Reverse the LED so the circuit is correct. Replace the <span style="color:blue">**blue**</span> resistor in the breadboard with the <span style="color:brown">**brown**</span> one.
```{image} ../images/ch01/lab/p6.png
:alt: Dimmer circuit
:class: bg-primary mb-1
:width: 400px
:height: 400px
``` 

Notice how the brightness of the LED changes when we replace the resistor.  That's because the 2nd resistor is letting **less** electricity flow from the voltage source through the LED.

## Summary
In this chapter we made an `LED circuit` and explored how the direction of the `LED` matters as well as the value of the `resistor`.  Next chapter we will use the `Espotek Labador` to further explore this circuit.

#led #voltage_supply #resistor #resistance #espotek_labador #breadboard #usb_cable #led_polarity