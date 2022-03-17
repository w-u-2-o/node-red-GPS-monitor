# node-red-GPS-monitor

Node-RED flow to monitor the serial port NMEA output of a GNSS receiver
and show fix state, UTC time, and a chart of satellite signal to noise (SNR) values.

The serial port node has to be manually changed to define the serial port parameters
because that node has no way to input them from the flow. I hate hard coding--grrrrr :-(

Developed under node 16.12.0 and npm 8.1.0.
