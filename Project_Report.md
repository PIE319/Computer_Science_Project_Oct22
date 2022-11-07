# Project report

### Overview
Our project is a rotating fan that points in whichever direction is hotter. It does this to avoid wasting energy on cold areas and to do the job of 2 fans at once as efficently as possibly. It achieves this through 2 temperature sensors placed in the areas that need to be cooled. They record the temperature where they are and transmit this data to the fan which uses this information to decide where to point. This project is intended to save money on large scale operations by halfing the amount of fans needed for the customer. The idea use cases are schools or offices.

### Early Pictures
<img width="500" alt="servoModule" src="https://user-images.githubusercontent.com/73748751/200275035-b4c79d9d-e900-4ee5-a03f-099ecec3da72.png">
<img width="500" alt="servoModule" src="https://user-images.githubusercontent.com/73748751/200275027-f45da4c9-48aa-49ed-973d-91db1ede9ce7.png">

### Later Pictures
<img width="500" alt="servoModule" src="https://user-images.githubusercontent.com/73748751/200273157-8d64f005-2a80-4910-af0e-70202265eb13.png">
<img width="500" alt="servoModule" src="https://user-images.githubusercontent.com/73748751/200273031-a49f52ed-e772-4054-bcbe-6d01ee169032.png">
<img width="500" alt="servoModule" src="https://user-images.githubusercontent.com/73748751/200274175-db4410fb-b18e-4ad8-9017-cbf827c8831b.png">
<img width="500" alt="servoModule" src="https://user-images.githubusercontent.com/73748751/200274122-41762af4-d83d-4e70-9ec5-0c5e5e8ad9e2.png">
<img width="500" alt="servoModule" src="https://user-images.githubusercontent.com/73748751/200274621-86465076-06e8-45fc-ab81-acb6145440ca.png">
<img width="500" alt="servoModule" src="https://user-images.githubusercontent.com/73748751/200274601-815ce628-69c0-4c02-9aae-17ec93367519.png">

These temperature sensors are the same as before but now have a protective lego casing to keep all the parts together and avoid any damages.
The main module has been largely rebuilt using a small LED light to indicate when the fan turns on and off. It also has connected the 180 servo to the fan module.

### Early Code
<img width="500" alt="servoModule" src="https://user-images.githubusercontent.com/73748751/196128727-cd5654d6-ada8-4244-8f9e-fd933ed736dd.png">
<img width="500" alt="tempA" src="https://user-images.githubusercontent.com/73748751/196122398-80815351-7f3c-410f-96e0-bf0e3060a0f0.png">
<img width="500" alt="tempB" src="https://user-images.githubusercontent.com/73748751/196122401-7d1fc877-64d4-421d-966d-7e73145bab91.png">

### Updated Code
<img width="500" alt="servoModule" src="https://user-images.githubusercontent.com/73748751/200275537-e9ff7022-ed7a-4410-a486-c1f1f621639a.png">
<img width="500" alt="servoModule" src="https://user-images.githubusercontent.com/73748751/200275671-f9cc9c44-dc1c-4d85-ad05-623c42573fe4.png">

This code for the temperature sensors separates some of the code into a start statement to avoid it running when not needed. This speeds up the code by reducing what is done every loop.
It also reworks the displays to update only when the temperature changes. This removes the unwanted flashing effect on the OLED displays.

### Planning vs implementation
- We planned to use a fan but instead used a light as a subsitute
- We had no clear plan on what material but decided to use legos as they were the most durable and readily available
- We estimated we would need a 

### Biggest challenges
- The fans did not work consistently
- Connecting the 180 servo to the fan was difficult to do effectively. There were problems with it falling off but the final solution works well.

### Known issues/bugs
- The 180 servo and fan do not currently work
- The project can not adapt effetively to different angles as it only rotates to 180 degrees and 0 degrees. We wanted to allow the user to customise the Angles but ran out of time to implement this feature.

## Weekly reflections

#### Week 1:	10th-15th October
- This week’s task:	Decide what we are going to do our project on and begin operations. 
- What did you do:	Chose our project idea and assigned each of us a role and began our work
- Outcome:	We completed the code and got the correct equipment. We also began the write up and the brainstorm ideas document
- Reflection	We are pleased with the work we got done this week.	 
			

#### Week 2:	17th-21st October
- This week’s task:	Correcting and testing the code. Completing our write up and reflection log.
- What did you do:	We decided how to build our device with Lego and microbit equipment. We tested our code and filled in write up.
- Outcome:	We build our Lego devices to hold the microbits and fan.
- Reflection:	We are satisfied with the work we did this week

### Week 3:	24th-28th October
- This week’s task:	We must assemble our project to completion and complete our write up 
- What did you do:	We completed our Lego build for all the microbits and the fan
- Outcome:	Our project is almost fully completed
- Reflection:	We are happy with the work we got done this week
