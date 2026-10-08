# 5V converter evaluation board (MCP1640T-I/CHY)
this board allows user to get 5V power supply with maximum out current of 1A (limited by coil to 0.8A).
You can safely power your 5V devices controlled by MCU's or evaluation boards

<figure>
  <img src="./images\IMG_3017.jpeg" alt="My profile photo." style="width: 75%;">
    <img src="./images\IMG_3015.jpeg" alt="My profile photo." style="width: 75%;">
  <figcaption>
    Image 1 and 2. Board in real usage power 5V servo
  </figcaption>
</figure>

## features
- DC to DC power conversion (boost)
- input voltage 3.0 to 4.2 V (possible change to range of 0.9 to 1.7V by replacing 309ohm resistor with 562ohm resistor)
- up to 95% efficiency in range of 10 - 100mA
- custom enabler: you can control on and off state by EN pin or permanently solder the 0ohm resistor.

<figure>
  <img src="./images\IMG_3018.jpeg" alt="My profile photo." style="width: 75%;">
    <img src="./images\IMG_3019.jpeg" alt="My profile photo." style="width: 75%;">
  <figcaption>
    Image 3 and 4. Detailed view with real scale.
  </figcaption>
</figure>

## issues
- the GPIO pins are not alligned, it requires using 2 bread boards or custom cutouts in pcb.

## components used in the project
1. 5V chip MCP1640T-I/CHY
2. coil LQM21PN4R7MGRD
3. 10uF 0603 capacitor
4. 4.7uG 0603 capacitor
4. 0ohm 0603 resitor
5. 309ohm 0603 resistor
6. 976ohm 0603 resistor