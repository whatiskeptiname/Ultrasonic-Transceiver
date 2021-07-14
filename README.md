# RC-Car

RC-Car is an Arduino-based Remote Controlled car with Servo arm, developed for two events Vector organized by Western Region Campus (WRC) and Locus organized by Pulchowk Engineering Campus.

## Images

<div align="center">
   <img src="./images/arduino_circuit.png" width="100%" height="50%" />

<br/>

   <img src="./images/circuit.jpg" width="100%" height="100%" />
</div>

## Components Used

1. Arduino Uno
2. Bot Chassis
3. Geared Motor *4
4. Lipo Battery
5. Servo
6. Transmitter FLYSKY
7. Receiver FS-IA10B

## Working

The communication between bot and transmitter is done in Pulse Position Modulation (PPM) mode. **PPMReader.cpp**, **InterruptHandler.h**, **WInterrupts.cpp** and **PPMReader.h** files are used to convert the raw ppm signals to control information. In **wrapper.h**, functions used for the bot control are described and these functions are implemented in **RC-Car.ino**.

## Watch The Video

<div align="center">
  <a href="https://youtu.be/Ozrh0uvRL1c"><img src="https://img.youtube.com/vi/Ozrh0uvRL1c/0.jpg"></a>
</div>