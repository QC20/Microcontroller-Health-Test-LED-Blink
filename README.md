# Arduino Blinking LED
This code implements a simple Arduino program to blink an LED connected to pin 13. It can be uploaded to an Arduino board or its clones to test the functionality of the board. The purpose of the code is to test if microcontroller boards are working by only having the on-board LED blink in a recognizable pattern.

<img width="715" alt="Skærmbillede 2023-06-30 kl  00 44 31" src="https://github.com/QC20/Microcontroller-Health-Test-LED-Blink/assets/36644388/a3133efa-a470-492a-9a7c-002dac08470f">

## Prerequisites
To run this code, you need the following:

- Arduino board or compatible clone
- LED connected to pin 13

## Circuit Setup
Connect an LED to pin 13 of your Arduino board. The longer leg of the LED (the positive side) should be connected to pin 13, and the shorter leg (the negative side) should be connected to the ground (GND) pin on the Arduino board.

## Code Explanation
The code uses the `digitalWrite()` function to turn the LED on and off by setting the pin's state to `HIGH` and `LOW`, respectively. It uses the `delay()` function to control the timing of the LED's on and off states.

The LED blinks in a specific pattern, with varying delays between each on and off state. The pattern creates a visually distinct and repetitive blinking effect.

## Uploading the Code
1. Connect your Arduino board to your computer using a USB cable.
2. Open the Arduino IDE or compatible development environment.
3. Select the appropriate board and port from the Tools menu.
4. Copy the code and paste it into a new sketch in the IDE.
5. Click the "Upload" button to upload the code to your Arduino board.
6. The LED connected to pin 13 should start blinking according to the defined pattern.

## Customize the Blinking Pattern
To customize the blinking pattern, you can modify the delays in the `loop()` function. By changing the duration of the delays, you can create different blinking effects.

Experiment with different delay values to achieve the desired blinking pattern.

## License
This code is released under the [MIT License](LICENSE).

Feel free to modify and distribute it according to your needs.

## Resources
For more information about Arduino and getting started with microcontroller programming, refer to the following resources:

- [Arduino Official Website](https://www.arduino.cc/)
- [Arduino Documentation](https://www.arduino.cc/reference/en/)
- [Arduino Forum](https://forum.arduino.cc/)

