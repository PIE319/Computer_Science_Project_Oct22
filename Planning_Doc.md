# Rotating servo fan

### Brainstorm ideas

#### Topic 1 

Description of topic: Fan on a 180-servo rotating towards two fixed directions depending on which is hotter. There will be a microbit at each side to read the temperatures 

Target audience: People sharing a desk or working in crowded spaces 

Problem it will solve: It will half the number of fans needed to cool an area 

Requirements: 3 microbits, 1 fan, 1 servo, 2 heat sensors 

Expectations: To provide a useful product that increase the quality of life in the workplace or at school 

Pros vs Cons: pros: would save a lot of money in large scales, efficiently uses energy as it will not waste power cooling areas that do not need it. Cons: needs multiple people working nearby, wont cool as effectively as just having two fans 

Group Decision: We decided this would be the best project to do. 


#### Topic 2  

Description of topic: Step counter 

Target audience: A person looking to keep track of their steps and their fitness 

Problem it will solve:   

Requirements: 1 microbit 

Expectations: To provide a useful project to help people track their fitness 

Pros vs Cons: Easy to use/Can break easil 

Group Decision: We decided not to go ahead with this project 


#### Topic 3  

Description of topic: Weather station; a station to measure many things such as a temperature sensor, a gauge to measure wind strength, a light sensor and a humidity sensor. 

Target audience: People looking for an easy and cheap option to measure the weather. 

Problem it will solve: This is an easier and cheaper option to track weather patterns in a controlled area. 

Requirements: 1-3 Microbits, 1 heat sensor, 1 light sensor, 1 compass, a float and tilt sensor. 

Expectations: To be a useful product to help people who want to track the weather 

Pros vs Cons: May be difficult to build and code. 

Group Decision: We decided not to go ahead with this product.

### Design statement
The project will consist of a fan connected to two temperatur sensors. It will be able to dynamically choose where to cool depending on these inputs.
The two fan will be mounted on a 180 degree rotating servo. It will read the temperatures of the two sensors and decide which direction it should point towards.
The temperature sensors will consist of a microbit to read the temperature and send it to the fan, as well as an OLED screen to display the temperature.
These will be placed at different directions relative to the fan but should be at the same distance.
The fan will consist of a single microbit which will handle recieving inputs from the two temperature sensors. It will then control the 180 servo to point in a direction it will calculate based on the inputs recieved.
It will also handle turning the fan on and off.

### Target audience
The target audience of this project is anybody looking to save money and efficently cool an area. The Rotating Servo Fan will be able to cool an area that would usually require 2 fans, thus saving energy
and requiring less fans to be bought. It will be much less wasteful that traditional fans. The ideal use case of this is in offices with mutiple peopl working nearby. It will be able to keep 2 people cool by directing cold air at the person that most needs it.

### Roughwork diagrams and mindmap:
<img width="500" alt="planning1" src="https://user-images.githubusercontent.com/73748751/195827017-2085def9-23bb-4d43-ac39-c77159be29a8.png">
<img width="500" alt="planning2" src="https://user-images.githubusercontent.com/73748751/195827032-a814ab12-797f-44d5-b267-4aa1a93a995c.png">
<img width="500" alt="planning3" src="https://user-images.githubusercontent.com/73748751/195827040-8a683f8c-28d6-4ccd-a2aa-77d66d7e99e6.png">
<img width="500" alt="planning4" src="https://user-images.githubusercontent.com/73748751/196133200-198c5c9f-6bdf-43ac-8f01-6757c2b29462.png">

### Desired features:
- Rotating fan
- Fan points towards hotter area
- Fan turns off when both areas are cool enough
- User can input desired temperature at both or either areas
- Each sensor displays the current temperature
- Entire system runs of battery power
- Can be powered on and off
- Power on and off sounds

### Team members and roles:
- Jason: construction and programming
- Pierse: planning and documentation
- Cormac: testing and documentation

### Field research
The typical 120w pedestal fan using costs around 4c an hour to run on average, according to [Uswitch](https://www.uswitch.com/gas-electricity/guides/which-appliances-use-the-most-energy/).

An office building running fans for an 8 hour work day will cost 32c a day.
This means each fan costs 1 euro and 60 cent a week, not accounting for overtime or weekend shifts

If our project can replace 2 fans for the same energy cost it will save 1.60 a week by doing the job of 2 fans for the cost of 1.
On large scale operations this can easily amount to a lot of saved money.
