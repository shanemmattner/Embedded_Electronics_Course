# First circuit: LED's

The foundation of electronics is `circuits` which are <ins>**just a bunch of electronics parts connected with wires**</ins>.

Let's look at one of the most basic circuits in electronics:  **LED circuit**.  This circuit has **3** electronic parts:
- `LED`: emits light when electricity is applied <br/>
![led](../images/ch01_led.png)
- `Voltage supply`:  source of electricity, like a battery</br>
![battery](../images/ch01_battery.png)
- `Resistor`: limits the amount of electricity that can flow <br/>
![resistor](../images/ch01_resistor.png)

Take out the following components from your kit:
- Breadboard
- Red LED
- Resistor with these color bands
  - **TODO** picture of resistor to use
- ESP32 dev kit
- Jumper wires

Put the ESP32 pins into the breadboard like this:
**TODO** add image of esp32 in breadboard

Then put the LED in the breadboard:
**TODO** picture of LED in breadboard

Now add the resistor to the breadboard:
**TODO** picture of resistor in breadboard

Finally, attach jumper wires.  After placing all the wires you should see the LED light up!
**TODO** add picture of full circuit with LED on

Congratulations on making your first circuit!  

Now let's do a little experiment: take the LED out of the breadboard and flip it around.  Notice what happens
**HIDDEN TAB that student clicks on after doing experiment**
LED's are part of a family of electronic parts called `diodes` which only allow electricity to flow in one direction.  They will be very useful for various applications.
**TODO** picture of LED off



Let's try another experiemnt and replace the resistor. Take out this resistor from your parts:
**TODO** picture of new resistor

Replace the resistor in the breadboard with the new one.  It doesn't matter which wire leg goes where:
**TODO** picture of complete circuit

Notice how the brightness of the LED changes when we replace the resistor.  That's because the resistor is letting less electricity flow from the voltage source through the LED.  This new resistor has more **<abbr title="Opposing the flow of electricity">resistance</abbr>**