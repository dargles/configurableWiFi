# configurableWiFi
A configurable WiFi client.
The idea behind this project is to set up an ESP so that it has a default WiFi access point that it tries to connect to. If it fails, it instead sets itself up as a web server so it can be fed the correct WiFi connection details and then reconnect. The WiFi connection details are held in SPIFFs memory so it can carry through deep sleep or switch-off. 
