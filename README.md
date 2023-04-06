<h1 align = "center"> Aarogya </h1>
<p align="center">
 <img src="https://user-images.githubusercontent.com/71590944/111881788-33353b80-89d8-11eb-9db1-746eba087b05.png" ><br>
 <img src=""><br>
</p>

Aarogya- This project is an hardware project combined with IoT made during Project cycle of 2021-2022.

This is a system that can continuously monitor a patient's heart rate and detect any abnormal spikes or drops in their heart rate. The system would then alert the patient's family or caregiver in real-time, allowing them to take immediate action if necessary.
This project has the potential to help save lives by providing real-time monitoring of a patient's heart rate and alerting their emergency contacts if there is a problem.

## Authors

- [@Archit Patro](https://github.com/Archit-Patro)
- [@Vanya Nandwani](https://github.com/vannyyyaaa)
- [@Ansh Verma](https://github.com/anshverma1612)
- [@Harshal Bhure]()


## Features

It is a health monitoring system which is used to check the heart rate of a person and if the person has high/low heartbeat and is on the verge of getting a heart attack, it automatically gives an emergency call, describing the patient's health conditions and requesting for ambulance.

## Tech Stack
**Software** The app was developed in android studio and was supported as a database by firebase. The android app  code was written in Java with XML involved in GUI designing. We have also used two external dependencies named Biometric Prompt which helps in the detection and verification of user’s biometrics. We have initiated the automated mail upon not meeting necessary conditions using JavaMail API and GMAIL’s SMTP server. 
For the above-mentioned feature, 3 libraries namely additional, mail, activation libraries have also been added externally.

**Hardware**From the hardware side , we used NODEMCU which is apparently the best and cheapest option for this project. We had chosen the MAX30102 module for detecting the heartbeat and the SpO2% of the individual. This data is sent to ThingSpeak where we have connected the the app IFTTT. IFTTT mobile app has to be installed in the individual's phone where it will give a call whenever there is a fluctuation in the person's heartbeat.

**Components:** NodeMCU, MAX30102

**EDITOR:** Arduino IDE, Android Studio



## Circuit Diagram

![CircuitDiagram](https://user-images.githubusercontent.com/91776131/213242261-07d7a4be-4740-446d-a5d2-b3b9169d31a4.jpg)


<p align="center">
	With :heart: &nbsp;by <a href="https://istevit.in/" target="_blank">ISTE-VIT</a>
</p>
