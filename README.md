# Raspberrypi-ledStrip
I Use Lsm9ds0 3D digital accelerometer to write script into name pipe in raspberrypi and control LED strip through PWM protocol
following is my demo video
https://youtube.com/shorts/05-Jp3Resa0?feature=share

1. LSM9DS0 3D Digital Accelerometer:
The LSM9DS0 is a sensor module that includes a 3-axis accelerometer, a 3-axis gyroscope, and a 3-axis magnetometer. For this project, you're specifically using the accelerometer part of the sensor. Accelerometers measure acceleration in three dimensions: X, Y, and Z. In your case, you're interested in these values to determine the orientation or movement of the Raspberry Pi.

2. Name Pipe (FIFO - First In, First Out):
A named pipe, or FIFO, is a method for interprocess communication on Unix and Unix-like systems. It provides a way for processes to communicate with each other without being directly connected. In your project, the accelerometer data is likely being read by a script and then written into a named pipe. Other scripts or programs can then read data from this pipe to obtain the accelerometer values.
