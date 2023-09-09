# Smart Door Lock Project Material <span style ="font-size : 18px">( Supervised by Dr  Gouda Ismail ) </span>

<br>
<hr>

![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=Raspberry%20Pi&logoColor=white)
![Research_Gate](https://img.shields.io/badge/Research_Gate-00CCBB.svg?&style=for-the-badge&logo=ResearchGate&logoColor=white)
![Google_Scholar](https://img.shields.io/badge/Google_Scholar-4285F4?style=for-the-badge&logo=google-scholar&logoColor=white)
![Academia](https://img.shields.io/badge/Academia-fff?style=for-the-badge&logo=academia&logoColor=black)
![Academia](https://img.shields.io/badge/Mendeley-9D1620?style=for-the-badge&logo=Mendeley&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![IOS](https://img.shields.io/badge/iOS-000000?style=for-the-badge&logo=ios&logoColor=white)
![Firebase](https://img.shields.io/badge/firebase-ffca28?style=for-the-badge&logo=firebase&logoColor=black)
![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)
![Github](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)

<hr>
<br>

<div style ="display : flex">
 <img src="https://i.ibb.co/M8drFGh/Untitled-1.png" alt="Untitled-1" border="0" width = "200px" style = "border-radius : 15px"> 
<p style = "margin : 0px 20px ; font-size : 16px ; display : inline">This project builds a system to help people feel safe at their homes. The system helps people to know who is behind the door. This system home owner can access the Mobile App with username and password and then if any guest come to his/her home the device will capture an image of his/her using Raspberry pi and send it to the owner by wifi, then the owner will decide either to open the door or not. Finally, this system will increase safety and privacy, save time. Help the elderly, employees and people with special needs</p>
 </div>

 <br>

---------------
 ## There are Some Reference Projects and Articles We Learned a lot From 

 * IoT Based Home Security System Using Raspberry Pi-3 - [View Paper](https://github.com/john-safwat/Smart-Door-Lock-Material/blob/main/Articales/6-9-2023/IJRAR190O064.pdf)

    * IoT Based Home Security System Using ```Raspberry Pi-3!``` 
This article provides valuable insights on how to use Raspberry Pi-3 to create a secure home environment. 

    * This System Recognize any Visitor When it Near To the Door Using ```PIR Sensor``` When Visitor Come Closer To the Door The System Capture an Image Using The ```Pi Camera``` Which Installed To The ```Raspberry Pi``` Then the Raspberry Pi Store The Image on Micro SD and Analysis The Image Using ```YOLO``` algorithm 

    * After Analyzing The Image The System Send Email With The Image and recorded Video and Audio To the Owner 
<br>
<br>

* Smart Doorbell Using Raspberry Pi and Pi Camera - [View Paper](https://github.com/john-safwat/Smart-Door-Lock-Material/blob/main/Articales/6-9-2023/Smart%20Doorbell%20Using%20Raspberry%20Pi%20and%20Pi%20Camera.pdf)

    *  Smart Doorbell Using Raspberry Pi and Pi Camera
        This article presents a low-cost Raspberry Pi device for home automation, utilizing a sensor to detect physical movement and record visitor images. The project uses face recognition systems like ```Markov Hidden Model``` and geometric matching for face detection, ensuring accurate and practical applications. 

    * The Raspberry Pi receives a doorbell signal and passes it to a camera, which captures an image and checks if it exists in the database.then the user decides whether to let him in or not.

    * will use : Raspberry pi - power supply - pi camera - internet - door bell - solenoid lock - phone - Application
<br>
<br>

* Security System for Visitor Validation at Entrance using Raspberry Pi and Elliptical Curve Digital Signature - [View Paper](https://github.com/john-safwat/Smart-Door-Lock-Material/blob/main/Articales/6-9-2023/Security_System_for_Visitor_Validation_at_Entrance.pdf) 
    * Hardware setup
        * Connecting the Raspberry Pi‟s general-purpose input output ports (GPIO) to a tactile  switch We connect one side of the switch to an 
            input pin on the Raspberry Pi using pin 18 general purpose input output ports (GPIO) The other side of the switch is connected to 
            ground using pin 6 using jumper wires. when the button is pressed program runs that reads the state of the button.
    * conclusion
        * This paper introduces an IoT security mechanism using ```ECDSA``` for reliable and cost-effective data verification. It utilizes the ```MIRACL crypto library```, enhancing existing methods with digital signatures for data integrity through private and public key verification.

<br>
<br>

* IoT-Based_Smart_Doorbell_Using_Raspberry_Pi.pdf - [View Paper](https://github.com/john-safwat/Smart-Door-Lock-Material/blob/main/Articales/6-9-2023/IoT-Based%20Smart%20Doorbell%20Using%20Raspberry%20Pi.pdf)

    * This system ensures security when the occupants leave home; it activates when needed, transmitting information about potential intruders over IoT.
    * The proposed system
        1. uses switch sensors placed under floor tiles to detect pressure, enhancing efficiency and accuracy. These sensors can measure pressure on tiles, avoiding temperature constraints, and can be executed using Python scripts using OpenCV.
        2. Collecting input signal from the sensor to Raspberry pi Controller. 
        3. Generating rotation in the servo motor based on the signal received from the raspberry Pi
        4. Capturing Video frames and transmitting to the user over network and enabling alarm
        
    * This System Depend on ```Piezoelectric Sensor``` Instead of Using ```PIR``` Because It can withstand high temperature (```500°C```)

<br>
<be>

* Raspberry Pi based Smart Home for Deployment in the Smart Grid - [View Paper](https://github.com/john-safwat/Smart-Door-Lock-Material/blob/main/Articales/6-9-2023/PaperinIJCA.pdf)

    * This system triggers an email notification with a "Door Open" message and a picture when a door with a reed switch is opened, alerting the owner of the breach and sounding an alarm. Configuration details are managed via Python scripts.


------------

## Raspberry Pi Model 

* Raspberry Pi ```Zero 2 W```

    * Zero 2 W is RP3A0 , a custom-built system-in-package designed by Raspberry Pi in the UK. With a ```Quad-core``` 64-bit ARM Cortex-A53 processor clocked at ``1GHz`` and ``512MB of SDRAM``, zero 2 is up to five times as fast as the original Raspberry Pi Zero
    
    * Wireless LAN is built in to a shielded enclosure with improved RF compliance, giving you more flexibility when designing with Raspberry Pi Zero 2 W

    * Raspberry Pi Zero 2 W is `perfect for a range of smart home applications and other IoT projects`. From security cameras to Bluetooth speakers, zero 2 W has the tiny form factor and impressive power that make it an ideal computer for your projects.

    * The Raspberry Pi Zero 2 is capable of playing retro games with Recalbox or Retropie, and can also play modern games with Steam Link. You can also make many fun projects such as drones and a Magic Mirror

<br>
<br>

* Raspberry Pi `Pico` 

    * The Raspberry Pi Pico series is a range of tiny, fast, and versatile boards built using RP2040, the flagship microcontroller chip designed by Raspberry Pi in the UK

    * Specifications :

        * 21 mm × 51 mm form factor RP2040 microcontroller chip designed by Raspberry Pi in the UK 
        * `Dual-core` Arm Cortex-M0+ processor
        * Flexible clock running up to `133MHz`
        * `264kB` on-chip SRAM
        * `2MB` on-board QSPI flash `2.4GHz` `802.11n`wireless LAN 
        * Bluetooth `5.2` 
        * 26 multifunction GPIO pins, including 3 analogue inputs 2 × UART, 2 × SPI controllers, 2 × I2C controllers, 16 × PWM channels
        * 1 × USB 1.1 controller and PHY, with host and device support 
        * 8 × Programmable I/O (PIO) state machines for custom peripheral support
        * Supported input voltage `1.8–5.5V DC`
        * Operating temperature -20°C to +85°C (Raspberry Pi Pico and Pico H); -20°C to +70°C (Raspberry Pi Pico W and Pico WH) Castellated module allows soldering direct to carrier boards
        *  Drag-and-drop programming using mass storage over USB Low-power sleep and dormant modes
        *  Accurate on-chip clock Temperature sensor Accelerated integer and floating-point libraries on-chip


    * Connect wirelessly :
        * Network your Pico for a complete IoT solution. Raspberry Pi Pico W comes with a fully certified module on board featuring 2.4GHz 802.11n wireless LAN and Bluetooth 5.2, making it the perfect solution for IoT applications and projects requiring wireless communication
               
    * Debugging with ease :
        * The Raspberry Pi Debug Probe is an all-in-one USB-to-debug kit that provides all the necessary hardware and cables for easy, solderless, plug-and-play debugging, making it easy to use a Raspberry Pi Pico with non-Raspberry Pi platforms such as Windows and Mac, and with typical Linux computers.

    * Good For : IoT applications and projects requiring wireless communication

<br><br>

* Raspberry Pi 4 
    * Dual-display, desktop computer and robot brains, smart home hub, media center, networked AI core, factory controller

    * Silent, energy-efficient : The fanless, energy-efficient Raspberry Pi runs silently and uses far less power than other computers.
    * Fast networking :  Raspberry Pi 4 comes with Gigabit Ethernet, along with onboard wireless networking and Bluetooth.
    * USB 3 : Your new Raspberry Pi 4 has upgraded USB capacity: along with two USB 2 ports you'll find two USB 3 ports, which can transfer data up to ten times faster.
    * Your choice of RAM :  We're making different variants of the Raspberry Pi 4 available, depending on how much RAM you need — 1GB, 2GB, 4GB, or 8GB.
    
    * Good For : learning PC for the kids, a media center, a web server, a game emulation machine or as the brains of a robot or IoT device

<br><br>

* Raspberry Pi `3 Model A+`

    * Specifications :
        * The Raspberry Pi 3 Model A+ extends the Raspberry Pi 3 range into the A+ board format .
        * Broadcom BCM2837B0, Cortex-A53 (ARMv8) 64-bit SoC @ `1.4GHz`
        * `512MB LPDDR2` SDRAM
        * `2.4GHz and 5GHz` IEEE `802.11.b/g/n/ac` wireless LAN, Bluetooth `4.2/BLE`
        * Extended 40-pin GPIO header
        * Full-size HDMI®
        * Single USB 2.0 ports
        * CSI camera
        * DSI display
        * 4-pole stereo output and composite video port
        * Micro SD port for loading your operating system and storing data
        * `5V/2.5A DC` power input

    * Good for : home servers, IOT and robotic projects

<br>        <br>

* Raspberry Pi `3 Model B`
    * Single-board computer with wireless LAN and Bluetooth connectivity

    * Specifications :
        * `Quad Core` `1.2GHz` Broadcom BCM2837 64bit CPU
        * `1GB RAM`
        * BCM43438 wireless LAN and Bluetooth Low Energy (BLE) on board
        * 100 Base Ethernet
        * 40-pin extended GPIO
        * `4 USB 2` ports
        * 4 Pole stereo output and composite video port
        * Full size HDMI
        * `CSI camera port for connecting a Raspberry Pi camera`
        * DSI display port for connecting a Raspberry Pi touchscreen display
        * `Micro SD port` for loading your operating system and storing data
        * Upgraded switched Micro USB power source up to `2.5A`

    * Good For : Internet of Things projects due to their processing power

<br>        <br>


* Raspberry Pi `1 Model B+`

    * Raspberry Pi Model B+ is the final revision of the original Raspberry Pi. It replaced the Model B in July 2014 and was superseded by Raspberry Pi 2 Model B

   * Specification ```Compared to the Model B it has```:
        * More GPIO pins. The GPIO header has grown to `40 pins`, while retaining the same pinout for the first `26 pins` as the Model A and B.
        
        * More USB ports. It comes with 4 USB 2.0 ports, compared to 2 on the Model B, and better hotplug and overcurrent behaviour.

        * `Micro SD`. The old friction-fit SD card socket has been replaced with a much nicer push-push micro SD version.

        * 100 Base Ethernet (same as the original Model B)

        * Lower power consumption. By replacing linear regulators with switching ones we’ve reduced power consumption by between `0.5W and 1W`.

        * Better audio. The audio circuit incorporates a dedicated low-noise power supply.
        
        * Neater form factor. We’ve aligned the USB connectors with the board edge, moved composite video onto the 3.5mm jack, and added four squarely-placed mounting holes.

    * Good For : word-processing, spreadsheets, high-definition video, games, and programming

<br>        <br>


* Raspberry Pi `1 Model A+`
    * The Model A+ is the low-cost variant of the Raspberry Pi. It replaced the original Model A in November 2014.

    * Specification ```Compared to the Model A it has``` :
        * More GPIO pins. The GPIO header has grown to 40 pins, while retaining the same pinout for the first 26 pins as the Model A and B.
        * Micro SD. The old friction-fit SD card socket has been replaced with a much nicer push-push micro SD version.

        * Lower power consumption. By replacing linear regulators with switching ones we’ve reduced power consumption by between 0.5W and 1W.
        * Better audio. The audio circuit incorporates a dedicated low-noise power supply.
        * Smaller neater form factor. We’ve aligned the USB connector with the board edge, moved composite video onto the 3.5mm jack, and added four squarely-placed mounting holes. Model A+ is approximately 2cm shorter than the Model A.

    * Good For : embedded and low-power projects that do not require Ethernet or multiple USB ports , graphic terminals, motor control in machinery and home automation
    
<br>        <br>

* Raspberry Pi `Zero W`

    * The Raspberry Pi Zero W extends the Pi Zero family and comes with added wireless LAN and Bluetooth connectivity.

    * Specification :
        * `802.11 b/g/n` wireless LAN
        * Bluetooth `4.1`
        * Bluetooth Low Energy (BLE)
        * `1GHz`, `single-core` CPU
        * `512MB RAM`
        * Mini HDMI port and micro USB On-The-Go (OTG) port
        * HAT-compatible 40-pin header
        * Composite video and reset headers
        * `CSI camera connector`

    * Good For :  making embedded Internet of Things (IoT) projects
    
<br>        <br>


* Raspberry Pi `Zero`

    * Raspberry Pi Zero is half the size of a Model A+, with twice the utility. A tiny Raspberry Pi that’s affordable enough for any project!

    * Specifications :
        * `1GHz` `single-core` CPU
        * `512MB` RAM
        * Mini HDMI® port
        * Micro USB OTG port
        * HAT-compatible `40-pin` header
        * Composite video and reset headers
        * `CSI camera connector` (v1.3 only)

    * Good For :  portable game consoles, home network music systems, WiFi security cameras, and even weather stations


<br>        <br>


   ``` 
   If you're looking for a low-cost web development project, you may consider using your 
   Raspberry Pi Zero web server. The project will allow you to host and run web applications 
   and sites. If you're a web designer or developer, you can use this to deploy and test your 
   application 
   ```