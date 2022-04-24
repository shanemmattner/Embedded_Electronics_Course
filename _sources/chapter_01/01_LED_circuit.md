# 1.1 First circuit: LED's

Electronics are made up of `circuits` which are <ins>**just a bunch of electronics parts connected with wires**</ins>.

Let's build our first circuit:  an **LED circuit**.  This circuit has **5** components:

- `Voltage supply`:  source of electricity, like a battery</br>
![battery](../images/ch01_battery.png)
-`Jumper wires`: connect the electronic parts
![jumper wires](../images/ch01_jumpers.png)


Take out component kit **01** that includes:
- 2 x Breadboards
![breadboard](../images/ch01_breadboard.png)
- `LED`: emits light when electricity flows through it <br/>
![led](../images/ch01_led.png)
- `Resistor`: limits the amount of electricity that can flow <br/>
![resistor](../images/ch01_resistor.png)
- `ESP32 development kit`: We will use the ESP32 for a source of electricity to power the LED.  Later this part will do much much more
![esp32](../images/ch01_esp32_dev_kit.png)
-`Jumper wires`: connect the electronic parts
![jumpers](../images/ch01_jumper.png)

1. Put the ESP32 dev kit into the breadboards:
![esp32](../images/ch01_esp32_dev_kit.png)

2. Plug in the USB cable from the ESP32 to your computer and you should see LED's on the board turn on.
![plugged in](../images/ch01_lab_02.png)

3. Insert one leg of a jumper into the **3v3** row the ESP32 is connected to.  Insert the other leg of the jumper in the top row of the breadboard:



4. Insert one leg of the resistor into the same row as the jumper, and the other resistor leg goes to the row directly across the divit:
![resistor position](../images/ch01_lab_04.png)

5. Insert the **long** leg of the LED into the same row as the resistor.  The other LED leg can go into a row below:

![led position](../images/ch01_lab_05.png)

6. Take the 2nd jumper and insert one leg to the row with LED, and the other leg goes to **GND** row of the ESP32.  You should see the LED light up!

![complete circuit!](../images/ch01_lab_06.png)

Congratulations on making your first circuit!  

7. Now let's do a little experiment: take the LED out of the breadboard and flip it around.  Notice what happens
**HIDDEN TAB that student clicks on after doing experiment**
LED's are part of a family of electronic parts called `diodes` which only allow electricity to flow in one direction.  They will be very useful for various applications.
![led reversed](../images/ch01_lab_07.png)



8. Let's try another experiemnt and replace the resistor. Reverse the LED so the circuit is correct.  Take out this resistor from your parts:
![new resistor](../images/ch01_lab_08_resistor.png)

Replace the resistor in the breadboard with the new one.  It doesn't matter which wire leg goes where:
![dimmer circuit](../images/ch01_lab_08.png)

Notice how the brightness of the LED changes when we replace the resistor.  That's because the 2nd resistor is letting less electricity flow from the voltage source through the LED.  This new resistor has more **<abbr title="Opposing the flow of electricity">resistance</abbr>**


#led #voltage_supply #resistor #esp32 #breadboard #jumper_wires #usb_cable #led_polarity