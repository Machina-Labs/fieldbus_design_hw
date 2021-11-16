# fieldbus\_design\_hw

Robots are cool, but are they cool enough? The answer is no, without gadgets and gizmos that lets them actually do stuff besides dance around. Those gizmos need to be wired to the robot somehow so that they can eat power and poop data, or make things move. The standard solution in robotics is a field bus - a physical network that connects both digital and analog IO, complex sensors, etc. to the robot.

## Your Job

Time to design a fieldbus. I've given you a list of sensors and actuators that we need to put on the robot (`devices.csv`), as well as where each one is located (`cell_map.png` && `sheet_clamp_fixture_map.png`). For relevant components, I've included the documentation in `docs/`. It's not complete, but it should get you pretty far.

Your task is to design and spec a FieldBus system to manage all this stuff. The field bus should be compliant with KRC2 robots, which gives you a few different options. You'll need to spec all fieldbus-relevant components to get the devices listed to function together.

### Specifications

- The fieldbus should be compliant with Kuka KRC2 controllers.
- If there is a sensor that provides data that you think shouldn't be on the field bus, specify how that data gets handled.

Provide any files you believe are necessary to understand, purchase, and construct the fieldbus. Some good suggestions are:
- Bill of Materials
- Block Diagram
- Design Document (explaining your design choices)

Don't forget about connectors!

## Submission
In order to submit the homework, do the following:

- Fork the GitHub repository (create a Github account if you don't have one)

- Clone the repository to your computer and develop your solution. Extra points for multiple commits & good commit messages.

- Once you're done, Push your changes to Github and send us a link to your forked repository.
