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
![WhatsApp Image 2021-07-28 at 12 51 11](https://user-images.githubusercontent.com/80844300/127283852-dc32851c-1c16-491c-ade4-55ed43027738.jpeg)

Turn OFF instruction at Serial Terminal:
![WhatsApp Image 2021-07-28 at 12 50 42 (1)](https://user-images.githubusercontent.com/80844300/127283912-22db474e-3cee-49f8-8e18-8e4d0d998d04.jpeg)

LED has turned OFF:
![WhatsApp Image 2021-07-28 at 12 51 32](https://user-images.githubusercontent.com/80844300/127284025-980a14c1-f810-4bef-9fb4-fcbabfe8e0bf.jpeg)

How the serial monitor looks when signals exchanged:
![WhatsApp Image 2021-07-28 at 12 51 11 (1)](https://user-images.githubusercontent.com/80844300/127284099-d51acc5b-3aa3-45be-9f53-be2b132d9c40.jpeg)

Hope my instructions were helpful



