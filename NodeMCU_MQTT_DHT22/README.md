Create Virtual Sensor for temperature and humidity in Domoticz
* Under Setup/Hardware add a device of type: "Dummy (Does nothing, use for virtual switches only)" with the name "Virtual Sensors".
* In the corresponding entry of your just created "Dummy" hardware, click the "Create Virtual Sensors" button that appear following the type. Then enter a device name and set Sensor Type: Temp+Hum.
* Under Setup/Devices, get the "idx" number of your device which is 321 in this installation.

The following libraries should be added to the Arduino IDE to handle the DHT interface:
* Sketch in Adruino IDE -> Include Library -> Manage Libraries and select to install: Adafruit Unified Sensor
* Sketch in Adruino IDE -> Include Library -> Manage Libraries and select to install: DHT sensor library for ESPx - Works better than the standard DHT sensor library from Adafruit
