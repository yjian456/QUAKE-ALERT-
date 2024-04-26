# Welcome to Quake Alert
⛰️ What it is: An earthquake early warning (EEW) system that detects shaking waves instantaneously and transmits warnings to help people get to safety.

## Inspiration
⛰️ Earthquakes are one of the deadliest types of disasters in developing countries. One of the main contributing factors to it’s deadliness is the delayed reaction by emergency officials. Often warnings are sent out too late, or individuals do not have access to technology to listen in on the warnings. We wanted to develop something that was simple and cheap so that these countries can get to safety in time.

## What it does
⛰️ Quake Alert is an earthquake detection system that utilizes an accelerometer to measure the amplitude and frequency of seismic waves that typically occur with local earthquakes. 

⛰️ What it does: Once the arduino has identified an abnormal vibration with the assistance of some sensor, the sound buzzer, LED light, and OLED light will display a warning. The warning will offer time to the individuals to go from the effective region and seek shelter in a safer region. Also, the warning will automatically stop once the vibrations have stopped. 

⛰️ How it works: The acceleration measures vibrations from three directions such as x-axis, y-axis and also from the z-axis, which are displayed on the screen during normal activities.

⛰️ The technology: Our strong-motion sensor is an accelerometer, and is designed to measure the large amplitude, high-frequency seismic waves typical of large local earthquakes. These seismic waves result in the strong ground motion we feel during a large earthquake.  The accelerometer is a vibration sensor that measures acceleration directly proportional to the force applied to an object that causes it to change its position or speed. Our seismograph is used as an instrument to detect and record earthquakes.

⛰️ In this project we have combined the use of both a seismograph and the richter scale, as they both depict very important information. The Richter scale rates the amount of energy released from a single earthquake, letting us know the magnitude of the disaster. A seismograph is what is used to actually measure the earthquake and the Richter scale is a way of putting the data into an understandable context.

## How we built it
⛰️ We used C++ for our arduino code with the addition of special methods and functions.

⛰️ The hardware of the Quake Alert is built using an arduino uno. The Arduino is connected to a 3-axis accelerometer in order to detect the vibrations. The information detected by the accelerometer is displayed on an OLED display (measurements from the x, y, and z axes). During irregular vibrations, the alert will sound through a buzzer, and syncs with a flashing red LED light. Once the value of the x, y, and z becomes irregular, the OLED will no longer display measurements and IT will display a warning sign instead that reads “EARTHQUAKE ALERT! SEEK SHELTER” and will have a sound buzzer that is similar to an amber alert.
