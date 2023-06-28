# 3-Jointed robotic arm
<!---
Replace this text with a brief description (2-3 sentences) of your project. This description should draw the reader in and make them interested in what you've built. You can include what the biggest challenges, takeaways, and triumphs from completing the project were. As you complete your portfolio, remember your audience is less familiar than you are with all that your project entails!
-->

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Harish B | Mission San Jose High | Mechanical Engineering | Incoming jounior 

<img src="Harish-Headshot.png"  width="300" height="300">
  
# Final Milestone
<!---
For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
-->
# Second Milestone
<!---
For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone 

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
-->
## Summary
My second milestone was achieved when I accomplished my goal of adding wheels to the claw in order to have more movement. The claw originally was only able to pick up things near it and that severely held it back from doing anything, and I fixed this by designing a chassis in Fusion 360 and 3D-printing it to hold the claw on the back while being able to move in a direction I pleased in order for the claw to pick up more items.  

## Components
1. Arduino Mega - This is the controller of the arm, it takes in the inputs of the joysticks and using the programmed code sends a signal to the servos to move that much. It has much more of the same pins than the Arduino Nano allowing for more components to be added
2. L298N motor driver - This motor driver controls the direction and power of the dc motors that are on the chassis.
3. Dc motors - These motors are more powerful than servos and are used to move my wheels since they have a continuous rotation unlike servos which only go from 0-270
4. Mehcanum wheels - These are wheels that have a special roller on their outer diameter allowing them when all four spun in a certain direction they move side to side in what's known as strafing.

This all works together starting at the joysticks where once detected input will send it into the Arduino mega. The Arduino Mega now takes in the joystick input and turns it into something that the H bridge can understand and sends it to the H bridge. The H bridge now takes the input from the Arduino Mega and sends it to the two dc motors that are connected to it and the dc motors turn the mechanum wheels that are attached to it 

## Progress 

## Challenges
My main challenge was coding my modified arm, I was using the previous arms code however the one I designed had 2 servos for more power on the claw and one of the servos were in the opposite direction. After assembling the arm and beginning to code the arm I realized the code was very hard to understand as it had no documentation as to how the custom libraries that the default arm had worked which was difficult for me. 
## Next steps
My next step is to make the controller and joysticks wireless, then put the whole arm on wheels to add more maneuverability to the arm. 
# First Milestone
## Summary
My first milestone was achieved when I managed to control my arm manually and pick up a paper cylinder. I did this by first assembling the arm and utilizing the 3 servo pivots to maneuver my arm in various directions. 
## Components 
1. 5g Servos - these are what move the arm, they are programmed to move from anywhere from 0-180 degrees.
2. Arduino Nano - this is what takes the code and inputs and tells certain pins on the Arduino to power, essentially it moves and controls the servos. The Arduino nano has pins on the bottom which vary from grounding, 5-volt power, reading and transmitting data, and data ports. The data ports are used to receive and send signals to the different things connected to it for example in my case how much to move the servo. Also, It can be used to receive, when it takes the input of the joystick.
3. Arduino Nano shield - this takes the pins of the Arduino and expands it to be more user-friendly. It also adds the necessary components to input more power into the system as the servos need more than the 5v that the Arduino provides. I used this to plug in my servos and also used this to add my 9v power supply.
4. Joysticks - This turns the hand movements into signals that the Arduino can understand and is used to control the arm
## Challenges
One main challenge I faced was trying to add my Bluetooth module to control the arm using a phone app. When trying to connect the first issue I encountered was that I was unable to build my code onto the Arduino. The reason for this was I was plugging the bluetooth modules transmitting data cable into the default read data pin on the Arduino. This meant that the Arduino wasn't reading the code I was uploading but the bluetooth module was instead so the code didn't upload. 
## Next steps
My next step for this project is to create a wireless controller as right now the joysticks have to be plugged into the Arduino sheild which is very inconvenient. I also am going to strengthen the arm to hold at least two AA batteries along with putting it on wheels to add more maneuverability to the arm.


<iframe width="560" height="315" src="https://www.youtube.com/embed/7PaMYvwxk2c" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# Starter Project
## Summary
For my starter project I built a Simon says game. The game works by pushing the rubber pad onto the motherboard to complete the circuit allowing the microcontroller to understand that the button has been pressed. The goal is to click the colors in the order the game displays them using the LEDs. 
## Components 
1. ATmega328 - this is the brains of the game and holds the code which is preprogrammed in.
2. 10k resistor - this makes sure that the whole circuit isn't overloaded from the power being inputted. It takes the power and only lets some pass and lets the rest go as heat
3. Through-hole PCB - this connects all the components together in an organized manner.
4. Battery clips - this takes the battery charge and inputs it into the PCB. It acts as a bridge for the battery to the PCB
5. Slide switch - this turns on and off certain parts of the PCB, for example, the power and sound. I simply just break and connects different circuits
6. 0.1μF Capacitor - this stores and releases energy 
## Challenges
The only challenge I faced was understanding which sides are positive and negative since they were not labeled, and to identify them I used a multimeter and used black and red pins to check continuity.
## Next Steps 
My next step is to start working on my intensive project which is the 3-jointed robotic arm

<iframe width="560" height="315" src="https://www.youtube.com/embed/bRiTaQy16FM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# Schematics 
<!---
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 
-->

# Code
<!---
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```
-->
# Bill of Materials
<!---
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
-->
