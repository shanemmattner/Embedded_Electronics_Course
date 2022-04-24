# 1.1 First circuit: LED's

Electronics are made up of `circuits` which are <ins>**just a bunch of electronics parts connected with wires**</ins>.

Let's build our first circuit:  an **LED circuit**.  This circuit has **4** components.  Take out component kit **01** that includes:
- `Breadboard`: Used for prototyping electronics circuits
<img src="../images/ch01/breadboard.png" width="200" height="200" />
<img src="../images/ch01/breadboard_connections.png" width="200" height="200" />
- `LED`: emits light when electricity flows through it <br/>
![led](../images/ch01/led.png)
- `Resistors`: limit the amount of electricity that can flow <br/>
![resistor](../images/ch01/resistors.png)
- `Espotek Labador`: We will use this as a source of power for the circuit
![Espotek Labador](../images/ch01/espotek_labador.png)

## Lab
### Step 1
Plug the Espotek Labador into the breadboard so that the 2 pins go into the **red** and **blue** rows:
![back of espotek](../images/ch01/lab/espotek_back.png)
![insert espotek](../images/ch01/lab/espotek_insertion.png)
![attached to bb](../images/ch01/lab/p1.png)

### Step 2
Plug in the USB cable from the Labador to your computer and you should see LED's on the board turn on.
![plugged in](../images/ch01/lab/p2.png)

### Step 3
Insert one leg of the <span style="color:blue">**blue**</span> resistor into the  <span style="color:red">**red**</span> column of the breadboard.  Insert the other leg of the resistor into any row:
![resistor position](../images/ch01/lab/p3.png)

### Step 4
Insert the **long** leg of the LED into the same row as the resistor.  The other LED leg goes to the <span style="color:blue">**blue**</span> column of the breadboard:

![led position](../images/ch01/lab/p4.png)

Congratulations on making your first circuit!  

### Step 5
Now let's do a little experiment: take the LED out of the breadboard and flip it around.  Notice what happens...
````{dropdown} See result
    :container: + shadow
    :title: bg-primary text-white font-weight-bold

![led reversed](../images/ch01/lab/p5.png)

LED's are part of a family of electronic parts called `diodes` which only allow electricity to flow in one direction.  They will be very useful for various applications.

````

### Step 6
Let's try another experiemnt and replace the resistor. Reverse the LED so the circuit is correct. Replace the blue resistor in the breadboard with the new one.  It doesn't matter which wire leg goes where:
![dimmer circuit](../images/ch01/lab/p6.png)

Notice how the brightness of the LED changes when we replace the resistor.  That's because the 2nd resistor is letting less electricity flow from the voltage source through the LED.

## Summary
In this chapter we made an LED circuit and explored how the direction of the LED matters as well as the value of the resistor.  Next chapter we will use the Espotek to further explore this circuit.

#led #voltage_supply #resistor #resistance #espotek_labador #breadboard #usb_cable #led_polarity