#Micro-Bit PY Game

## Developers
Jonathan Fermin, Robert Perez, Kushal Joshi

## Goals
To create a working PY game
Using MicroBit 
Controlling the PYGame with MicroBit.

## Tools

[Microbit](http://microbit.org/)

[Processing](http://www.wekinator.org/examples/#BBC_microbit)

[Wekinator](http://www.wekinator.org/examples/)

[Pygame](https://www.pygame.org/news)

## Approach
We used the MicroBit movement and accelerometer data to move a virtual blob in a Pygame. 

### Sensors used
Everything is done through the MicroBit

### Feature extractor approach
Our Wekinator setup dealt with the 3 input, 1 output (4 classes). The 3 inputs are based off accelerometer data provided us with the 3 input data. Our output was the 1 output with 4 classes which represented the 4 dimensions.

### ML model structure - what you did and why, including results from experiments you tried along the way

We used K nearest neighbors, which was effective. The KNN approach was proved to be simplistic, which was perfect for our 2-Dimension. We only had to worry about the x,y direction but if we had the 3rd dimension we might have needed to explore other ML models.

## Ideas about how other might improve upon your work

* Implementing this to a 3-D space would be our next goal in mind. Being able to move in a 2-D space is very neat, but provides limited real world application. 

*Using the 2-D space that we have to work with, implementing this to a wheelchair setting would be a great topic to leap off from. Allowing a wheelchair user to use a device to tilt to move themselves.

## Demo Video

[Demo Video Link](https://youtu.be/K261yyfNX3A)
