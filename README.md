# README

MCU code: converts user action to signals
* input: motion, sensed by imu —> i2c 
* input: button presses
* output: orientation of pen, speed of pen, what light is being tracked, buttons pressed
  * may need to do integration of imu and magnetometer

i2c:
TODO: 2/9 JL
  read IMU data
  read button output
  write LED 
