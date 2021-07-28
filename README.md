# Lighting-LED-on-ESP32-board-from-mobile

This is my introductory project to ESP32. 
Here, I have remotely turned ON and OFF and LED from my mobile phone. 

Note for LED: 
Longer Pin => +ve => Anode
Shorter Pin => -ve => Cathode

The connections I had done for the same are as follows:
LED +ve => 220Ohm resistor -> +ve supply at pin 23 of ESP32
LED -ve => GND pin of ESP32

Note: 
The resistor value can be anything between 200 Ohm to 1kOhm. 
A value larger than 10kOhm will cause the intensity of LED to be very low. 
A value smaller than 200Ohm might kill the LED.

After making the connections, upload the code into the board. 
Download the Serial Bluetooth Terminal App from playstore into your phone.
Turn on Bluetooth in your phone. Search for new device, here I have named the ESP device as "ESP32_Dyuti". 
Then open app. Click on "Devices". Select your device. Open terminal.

Here in the code, 
I have set 'a' as instruction for Turn ON LED.
I have set 'b' as instruction for Turn OFF LED.

Enter a or b and the led will accordingly turn On or Off.

Refer pictures for the connections and the turning ON and turning OFF.

Turn On instruction at Serial Terminal:
![WhatsApp Image 2021-07-28 at 12 50 42](https://user-images.githubusercontent.com/80844300/127283805-a2401da3-8fde-47ae-bce1-bc6a7f12dade.jpeg)

LED has thus turned ON:





