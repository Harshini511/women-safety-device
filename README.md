# women-safety-device
Using arduino

Our project aims at developing a wearable safety device for women based on voice sensors and a button access to detect situations of distress. Our plan is to achieve this by means of an elegant algorithm using arduino, such that a given wearable device can ably give information to trusted contacts by simple actions such as wailing a particular keyword that can be set by the user or clicking a button on the wearable device. 

Methodology  
1. The voice recognition module recognizes the keyword that is wailed and the device is activated accordingly. The proximity and heart rate sensor(s) are attached to the given wearable device.
2. The pressing of button(action) and discontinuous heartbeat of the user is recorded by the proximity and heart rate sensor and the data is sent to the Arduino Uno.
3. Data including the hard-coded numbers of the rescue officials is inbuilt.
4. The Arduino Uno processes the data sent and upon following algorithms, various appliances are called. In order to send SMS to the required contacts, A GSM shield is used and a    Bluetooth arduino module is used to connect the device to a mobile phone network so that the control can be given from the mobile.
5. The Arduino Uno is further connected to various devices using connecting wires.
