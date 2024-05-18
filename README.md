<h1 align="left">UltraSonic Sensor with Radar</h1>
<span>
    <img alt="GitHub forks" src="https://img.shields.io/github/forks/ahmedyar7/Ultrasonic-Radar-Sensor?style=for-the-badge&logo=github&logoColor=white&logoSize=20&label=FORKS&labelColor=black&link=https%3A%2F%2Fgithub.com%2Fahmedyar7%2FUltrasonic-Radar-Sensor">
    <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/ahmedyar7/Ultrasonic-Radar-Sensor?style=for-the-badge&logo=github&logoColor=blue&labelColor=black&color=grey">
  
</span>
<h2 align="left">Contributors ✏</h2>
<span>
    
<a href="https://github.com/ahmedyar7" target="_blank">
  <object data="https://img.shields.io/badge/AhmedYar-grey?style=for-the-badge&logo=github&logoColor=white" type="image/png">
    <img alt="Static Badge" src="https://img.shields.io/badge/AhmedYar-grey?style=for-the-badge&logo=github&logoColor=white">
  </object>
</a>
<a href="https://github.com/gulzrn" target="_blank">
<img alt="Static Badge" src="https://img.shields.io/badge/GulZareen-black?style=for-the-badge&logo=github&logoColor=white&link=github.com%2Fahmedyar7">
</a>
<a href="https://github.com/gulzrn" target="_blank">
<img alt="Static Badge" src="https://img.shields.io/badge/SyedMuska-4275c7?style=for-the-badge&logo=github&logoColor=white&link=github.com%2Fahmedyar7">
</a>




  
</span>



###

<h2 align="left">Abstract 🌌</h2>

###

<p align="left">This project outlines the development of an ultrasonic radar system using an Arduino Uno, an ultrasonic sensor (HC-SR04), and a servo motor. This radar can detect objects within its range and visualize them using Processing software.</p>

###

<h2 align="left">Components and Materials: 🔨⚙️</h2>

###

<h3 align="left">Hardware: 🔧</h3>

###

<p align="left">• Arduino Uno<br>• SG90 Micro-servo motor<br>• Ultrasonic Sensor - HC-SR04 (Generic)<br>• Jumper wires<br>• Hot glue gun (optional)</p>

###

<h3 align="left">Software: 💻</h3>

###

<p align="left">• Arduino IDE (Integrated Development Environment)<br>• Processing IDE</p>

###

<div align="center">
    <a href="https://www.arduino.cc">
  <img src="https://img.shields.io/badge/Arduino-00979D?logo=arduino&logoColor=white&style=for-the-badge" height="40" alt="arduino logo"  />
  <img width="12" />
  <a/>
    <a href="https://processing.org/">
  <img src="https://img.shields.io/badge/Processing Foundation-006699?logo=processingfoundation&logoColor=white&style=for-the-badge" height="40" alt="processing logo"  />
        <a/>
</div>

###


<h2 align="left">Methodology 🧾</h2>

###


<p align="left">This ultrasonic radar system operates by:</p>

###


<h3 align="left">1. Mounting the Ultrasonic Sensor: 📌</h3>

###


<p align="left">The HC-SR04 sensor is attached to the servo motor using hot glue (or a more permanent method) to enable scanning in different directions.</p>

###

<h3 align="left">2. Sensor Connection: 📡</h3>

###


<p align="left">The HC-SR04 connects to the Arduino Uno as follows:<br>• VCC (sensor) to 5V (Arduino) ⚡<br>• GND (sensor) to GND (Arduino)<br>• TRIG (sensor) to pin 2 (Arduino) - trigger pin.<br>• ECHO (sensor) to pin 3 (Arduino) - echo pin.</p>

###


<h3 align="left">3. Servo Motor Connection: 🔌</h3>

###


<p align="left">The servo motor connects to the Arduino Uno as follows:<br>• Red wire (servo) to 5V (Arduino) – power.<br>• Brown wire (servo) to GND (Arduino) – ground<br>• Orange wire (servo) to pin 4 (Arduino) - control pin.</p>

###

<h3 align="left">4. Software Functionality 👩🏻‍💻</h3>

###


<h4 align="left">Arduino Code 📝</h4>

###


<p align="left">• Defines a function to measure distance using the ultrasonic sensor's time-of-flight principle.<br>• Implements a loop to continuously:<br>• Rotate the servo motor from a start angle to an end angle (scanning range).<br>• Measure the distance to any object detected by the sensor in its path.<br>• Send this distance data to the Processing software.</p>

###


<h4 align="left">Processing Code: 🌐</h4>

###


<p align="left">• Receives distance data from the Arduino via the serial port.<br>• Visualizes the radar display based on the received distances:<br>• Green lines represent no object detected (distance beyond a threshold).<br>• Red lines represent object detected (distance within the threshold).</p>

###


<h2 align="left">Conclusion 🏁</h2>

###

<p align="left">This project demonstrates the capabilities of Arduino in building a simple yet practical ultrasonic radar system. The project provides a valuable learning experience in interfacing sensors, motors, and software for real-world applications.</p>
