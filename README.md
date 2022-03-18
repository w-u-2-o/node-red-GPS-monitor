# node-red-GPS-monitor

Node-RED flow to monitor the serial port NMEA output of a GNSS receiver
and show fix state, UTC time, and a chart of satellite signal to noise (SNR) values.

SCREENSHOTS

Screenshots can be found in the Github Wiki entry for this repository.

DESCRIPTION

The serial port node has to be manually changed to define the serial port parameters
because that node has no way to input them from the flow. I hate hard coding--grrrrr :-(

You do have to have an understanding of NMEA messaging to understand this flow. There are plenty of internet resources available on the subject.

Developed under node 16.12.0 and npm 8.1.0.
