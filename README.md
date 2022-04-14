# code_Project_83-DS1307
Chapter 3 code_Project_83 The second part 2 of "The Arduino World Book" code_Project_83
-  By:Farkad Adnan فرقد عدنان - 
-  E-mail: farkad.hpfa95@gmail.com 
-  inst : farkadadnan 
-  #farkadadnan , #farkad_adnan , فرقد عدنان# 
-  FaceBook: كتاب عالم الاردوينو 
-  inst : arduinobook
1. #كتاب_عالم_الاردوينو
2. #كتاب_عالم_الآردوينو

- https://www.facebook.com/profile.php?id=100002145048612-
- https://www.instagram.com/farkadadnan/
- https://www.linkedin.com/in/farkad-adnan-499972121/

 <p>
 <a href='https://mobile.twitter.com/farkadadnan'>
        <img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/farkadadnan?label=%40farkadadnan&style=social" alt='Twitter' align="center"/>
    </a>
</p>
# General structure
At the heart of the module is a low-cost, quite accurate RTC chip from Maxim – DS1307. It manages all timekeeping functions and features a simple two-wire I2C interface which can be easily interfaced with any microcontroller of your choice.
![DS1307-RTC-Module-Pinout](https://user-images.githubusercontent.com/35774039/163474128-c0e4c962-d3fd-4826-a9bc-5b51ed9d868d.png)

# library 

```
#include <Wire.h>
#include "RTClib.h"
RTC_DS1307 rtc;
```

# شريحة أو رقاقةDS1307  RTC عن قرب

![DS1307-Module-Provision-for-DS18B20](https://user-images.githubusercontent.com/35774039/163474481-69efb5ff-f45d-42e0-a3b1-5c5b9f45be42.jpg)
![DS1307-Module-24C32-EEPROM-Chip](https://user-images.githubusercontent.com/35774039/163474490-6f8800d9-f11b-4945-96ec-30ecafd391ef.jpg)
![DS1307-Module-Chip-Crystal-Oscillator](https://user-images.githubusercontent.com/35774039/163474495-31bc8614-f322-482c-8e99-bf7a378f4d5a.jpg)
![DS1307-Module-CR2032-Battery-Holder](https://user-images.githubusercontent.com/35774039/163474498-b402b555-6cc5-4432-b03b-c80fcb3cf151.jpg)



# Installing RTClib library
- Communicating with a RTC module is a bunch of work. Fortunately, RTClib library was written to hide away all the complexities so that we can issue simple commands to read the RTC data.

- To install the library navigate to the Sketch > Include Library > Manage Libraries…Wait for Library Manager to download libraries index and update list of installed libraries

![Manage-Libraries](https://user-images.githubusercontent.com/35774039/163475038-132e383d-5075-4aa6-9b13-593e4711cec0.png)

- Filter your search by typing ‘rtclib’. There should be a couple entries. Look for RTClib by Adafruit. Click on that entry, and then select Install.
![3](https://user-images.githubusercontent.com/35774039/163475430-4fcbfd94-4b46-4fd9-9462-03596eeb0082.JPG)



