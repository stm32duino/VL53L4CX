# VL53L4CX
Arduino library to support the VL53L4CX Time-of-Flight high accuracy ranging sensor with multi target detection.

## API

This sensor uses I2C to communicate. An I2C instance is required to access to the sensor.
The APIs provide simple distance measure in both polling and interrupt modes.

## Examples

There are 2 examples with the VL53L4CX library.

In order to use these examples you need to connect the VL53L4CX satellite sensor directly to the Nucleo board with wires as explained below:
- pin 1 (GND) of the VL53L4CX satellite connected to GND of the Nucleo board
- pin 2 (VDD) of the VL53L4CX satellite connected to 3V3 pin of the Nucleo board
- pin 3 (SCL) of the VL53L4CX satellite connected to pin D15 (SCL) of the Nucleo board
- pin 4 (SDA) of the VL53L4CX satellite connected to pin D14 (SDA) of the Nucleo board
- pin 5 (GPIO1) of the VL53L4CX satellite connected to pin A2 of the Nucleo board
- pin 6 (XSHUT) of the VL53L4CX satellite connected to pin A1 of the Nucleo board

* VL53L4CX_Sat_HelloWorld: This example code is to show how to get proximity
  values of the VL53L4CX satellite sensor in polling mode.

* VL53L4CX_Sat_HelloWorld_Interrupt: This example code is to show how to get proximity
  values of the VL53L4CX satellite sensor in interrupt mode.

## Documentation

You can find the source files at  
https://github.com/stm32duino/VL53L4CX

The VL53L4CX datasheet is available at  
https://www.st.com/en/imaging-and-photonics-solutions/vl53l4cx.html
