Name: Sparsh Patel

EID: sdp2557

Team Number: F12

## Questions

1. Why does your program need a setup and a loop?

    The program needs a setup to initialize any inputs and outputs. Loops are used to continously read and
iterate the program without manual input.

2. What is the downside to putting all your code in a loop?

    Putting all code in the loop would create a problem of an infinite loop
that may initiate a function that shouldn't be iterated.

3. Why does your code need to be compiled?

    Code needs to be compiled to be translated into assembly code which is then interperated by the computer through 
its own machine language.

4. When lowering the frequency in procedure A, step 4, what is going wrong? Brainstorm some solutions. Dimmers exist in the real world. What is their solution?

    When lowering the frequency in procedure A, step 4, the period of switching from on and off increases, thus continuously blinking until it is instructed to stop.
Increasing the frequency will lower the period to where the flickering of the LED will look like a smooth transition for dimming and creating the fading effect.
	

5. Why do you need to connect the logic analyzer ground to the ESP32 ground?

    We need to connect those components in that orienation for there to be a drop in voltage to initiate current through the circuit.

6. What is the difference between synchronous and asynchronous communication?

    Synchronous communication requires data to be in a constant stream.
Asynchronous communication requires data to not be in a constant stream.

7. Profile of UART: Sent X bytes in Y time 

    10 bits in .856 milliseconds

8. Profile of SPI: Sent X bytes in Y time

    10 bits in .2616 milliseconds

9. Why is SPI so much faster than UART?

    SPI is much faster because it utilizes a synchronous communication.
UART is slower due to using asynchronous communication because it outputs the information based on the speed of the inputs.

10. list one pro and one con of UART

    Pro: can recieve user input
    Con: slower than other forms of communication

11. list one pro and one con of SPI

    Pro: much faster form of communication based on its run time in congruence with the clock line
    Con: requires more connections and resources to utilize

12. list one pro and one con of I2C

    Pro: utilizes more slave devices
    Con: needs pullup resistors

13. Why does I2C need external resistors to work?

    I2C need external resistors because the lines the I2C uses are open drain.

## Screenshots

Procedure A, step 1:
img/Data Blinker.png

Procedure A, step 4:
img/Data Dimmer.png

Procedure B, UART:
img/Data UART.png

Procedure B, SPI:
img/Data SPI.png
