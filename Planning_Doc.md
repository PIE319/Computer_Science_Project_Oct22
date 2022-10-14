# Rotating servo fan

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
![20221014_112851](https://user-images.githubusercontent.com/73748751/195827017-2085def9-23bb-4d43-ac39-c77159be29a8.png)
![20221014_112838](https://user-images.githubusercontent.com/73748751/195827032-a814ab12-797f-44d5-b267-4aa1a93a995c.png)
![20221014_112844](https://user-images.githubusercontent.com/73748751/195827040-8a683f8c-28d6-4ccd-a2aa-77d66d7e99e6.png)

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
