# Muppet Class Node 4
 LIDAR on RP2040 w/ CAN
 Hardware: 
 - Adafruit RP2040 CAN
 - RPLIDAR C1

This application will run the LIDAR from start up. 
 - 1 Hz Heartbeat which 10 deg proximity bite (1 = something within 1M, 0=clear)
 - CAN command to start publishing with frequency for 5Hz increments with speed.
 
