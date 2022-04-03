# Smart-bag-tracking-system
IOT based tracking system that helps track a lost bag in public spaces or in cases misplaced in a room.

## Hardware
* Arduinouno R3 - https://docs.arduino.cc/hardware/uno-rev3
<img src="https://github.com/VaporFoxLash/Smart-bag-tracking-system/blob/main/Docs/Arduino-UNO.jpg"><br/>

* GSM SIM808 - https://www.simcom.com/product/SIM808.html
<img src="https://github.com/VaporFoxLash/Smart-bag-tracking-system/blob/main/Docs/SIM808pins.jpg"><br/>
* The GSM module uses GSM and GPRS technology to communicate with another device wirelessly. It uses 2G network to connect with the internet
### The circuit
<img src="https://github.com/VaporFoxLash/Smart-bag-tracking-system/blob/main/Docs/Circuit.png">

## Software and Technologies
* Arduino IDE 1.8.19 <br />
Visit https://www.arduino.cc/en/software to download and install the IDE.

* Android Studio
https://developer.android.com/studio

## TODO
- [ ] Arduino reads and sends data over HTTP
  - [ ] Read data(location).
  - [ ] Send data to the databse
  - [ ] Store the longitute and latitude in the database
 - [ ] Request the location by sending an SMS
- [ ] Android App fetch and display data from the database
  - [ ] Fetch data
  - [ ] Display the locaion
  - [ ] Get notifications and update the screen
- [ ] Monitoring
  - [ ] Monitor the weight of the bag
  - [ ] Real time location
  - [ ] The speed at wwhich it's moving(If in motion)
  - [ ] Temperature of the sarounding area
- [ ] Collect data and improve the system
- [ ] Use a more portable device for easy use and carry

## Usage
```ruby
 $ git clone https://github.com/VaporFoxLash/Smart-bag-tracking-system.git
 $ cd /Smart-bag-trascking-system
```

## References
* https://www.arduino.cc/reference/en/libraries/
* https://developer.android.com/docs/
