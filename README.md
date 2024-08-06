# task--3-SM
Description 
main.ino
•	WiFi Setup:
o	Connects to a WiFi network using the SSID and password provided.
o	Prints the local IP address once connected.
•	Main Loop:
o	Checks if the interval (2000 milliseconds) has passed since the last request.
o	Creates an HTTPClient object to handle the HTTP request.
o	Sends an HTTP GET request to the specified URL.
o	Prints the HTTP response code and payload to the Serial Monitor.
o	Updates the timestamp for the next interval.



Output:
•	Once the board is connected to the WiFi network, it will start making HTTP GET requests to the specified URL at regular intervals (every 2000 milliseconds or 2 seconds).
•	The HTTP response code and payload will be printed to the Serial Monitor.
•	If there is an error in the HTTP request, the error code will be printed.

URL used in the code:
•	https://s-m.com.sa/s.html
•	https://s-m.com.sa/l.html
•	https://s-m.com.sa/r.html
•	https://s-m.com.sa/f.html
•	https://s-m.com.sa/b.html

