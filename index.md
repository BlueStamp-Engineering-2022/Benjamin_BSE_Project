# Metal Detector
The Metal Detector is mainly built with three parts. A search coil, a base, and a circuit. When all of the components are combined, it makes a complete detector that buzzes whenever there is anything metal nearby. The way it works is that the inductor has a magnetic field. If there is anything metal near it, there will be a signal that will pass through the search coil, which is also connected to the circuit. The circuit includes a buzzer and an LED. The buzzer and LED will buzz and blink rapidly when the circuit receives the signal. That is how you would know that there is metal near the search coil. Finally, mounting both parts to the base would allow you to scan the ground while walking around, enabling you to go around and find a metallic object on or under the ground.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Benjamin | Cupertino High School | Engineering | Rising Junior


![BSEphoto](https://user-images.githubusercontent.com/107588607/174402480-b11bf8b3-0c12-43dc-b338-a652963c8ed0.JPG)

  
# Final Milestone

Once I fully assembled my metal detector, I wanted to make a few of my changes to it. First of all, I wanted to be able to manually change the sensitivity of the detector without having to go and change it manually in the code. The way that I did was was that I used a potentiometer. I connected it to pin A0, where I then coded the SENSITIVITY variable into the value the potentiometer gave. This allowed me to turn a knob to change the sensitivity from interrupting every 0 to 1023 oscillations. Another change I made was installing a larger LED that flashes when the buzzer buzzes. This change was much easier since all I did was replace the small LED that I already installed on the protoshield with a new and larger LED.

[![](https://res.cloudinary.com/marcomontalbano/image/upload/v1658521045/video_to_markdown/images/youtube--p0N1wCRUJes-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=p0N1wCRUJes&ab_channel=BlueStampEng "")


# Second Milestone

After finishing the electric components of the metal detector, I wanted to fully assemble all the parts to make a fully working metal detector. At first, I was testing designs that would allow me to hold the detector comfortably. I used tape to make a prototype of the fully built metal detector. After creating a prototype I liked, I went into CAD to 3D design two mounts that would allow me to put the circuit and search coil onto a base without any tape. The search coil mount I made includes three main shapes, a cylinder, rectangular prism, and triangular prism. The rectangular prism is a base, with the triangular prism sitting on top. The triangular prism creates an angle when the metal detector is fully built. Finally, I made a hole in the center of a cylinder to fit part of the pole with the search coil. My 2nd mount was used for the battery, circuit, and Arduino. I designed a circular ring with a gap on one of the sides. This would allow me to snap the mount onto the pole. I then created a hollow rectangle that would fit the battery and decided to hot glue the Arduino on top of the mount. After receiving my 3D mounts, I hot glued the search coil mount with the bottom of the pole. I then snapped the battery mount near the handle of the pole.

[![](https://res.cloudinary.com/marcomontalbano/image/upload/v1658183900/video_to_markdown/images/youtube--zBByEamxRj0-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=zBByEamxRj0&ab_channel=BlueStampEng "")

# First Milestone

I chose to do the Metal Detector project, which uses a search coil and a circuit to see if there is any metal nearby. The circuit consists of resistors, capacitors, transistors, and piezo buzzers. The search coil is made by wrapping wire around a lid to create an inductor. The ends of the wire then connect to the circuit. The search coil works because the inductor contains a magnetic field, so a signal will be produced when metal is near it. The signal then travels to the circuit, which causes the LED to blink faster and the buzzer to buzz more quickly. The circuit also contains a null button allowing me to recalibrate the metal detector. After completing the circuit and search coil, I soldered the circuit into a protoshield directly connecting to the Arduino. By using the protoshield, the components are more compact and will not be disconnected from a simple pull.

[![](https://res.cloudinary.com/marcomontalbano/image/upload/v1656711322/video_to_markdown/images/youtube--OLQX2sniHew-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=OLQX2sniHew&ab_channel=BlueStampEng "")

# Starter Project Milestone
The Starter Project that I did was the Useless Machine. Here, I first soldered the switches, LED, and resistors onto the circuit board. I also connected the wires on the motors and batteries with the circuit board. The machine works because when you flip a switch, the motor turns on, moving an arm that eventually flips the switch the other way. This causes the motor to spin the other way until the arm hits a snap switch which turns off the machine. The LED also changes color according to what direction the motor is moving. When the switch is first flipped, a green color emits from the LED. Once the arm hits the switch, the LED changes to a red color until the arm hits the snap switch, which turn it off.

[![](https://res.cloudinary.com/marcomontalbano/image/upload/v1657750274/video_to_markdown/images/youtube--wxl1eijLKvY-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=wxl1eijLKvY&ab_channel=BlueStampEng "")
