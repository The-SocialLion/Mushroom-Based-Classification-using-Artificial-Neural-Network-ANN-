# Simple Pendulum
## JavaScript Files
### Title: Main
This a js format for the working of  simple pendulum simulator.
#### Variables:
Tp:Time Period
Frs:
Fhz:Frequency in Hertz
length:Length of string
start:Click to start the simulator
stop:Click to stop the simulator
ropeLength:Length of string
sineWave:Output 
canvas_width:
canvas_height:
origin:Starting point of the pendulum
pendulam:
#### Functions:
anonymous ():The change event handler callback function to change the pendulum rope length by user input.

click start (): The click event handler callback function to start the simulator.

click stop (): The click event handler callback function to stop the simulator.

drawGraph (): 

draw fn:

This a js format of simple pendulum simulator.
## Title: Pendulum
### Class and method:
#### Class-Vector: 
constructor(): initialing the coordinates and the radius of the ball.

addTo(): Incrementing the coordinates wrt to the position of the pendulum.

#### Class-Pendulum:

constructor():initialing the origin ,ropelength,boolean expression,angle.

reset(): initialing the velocity,accelration to zero ,angle = pi/2.

drawLine(): Outlining the rope connecting the bob and the fixed point.

drawBall(): Outlining the pendulum bob .

draw(): Animating the movement of the pendullum.

setAngle(): Initialising the angle theta.

getAngle(): Returning the angle.

setRopeLength(): Evaluating the RopeLength.

update():  Updating the parameters velocity,accelration,angle for an angle sweep.

getTimePeriod(): Returning the value of time period after one complete swing .





