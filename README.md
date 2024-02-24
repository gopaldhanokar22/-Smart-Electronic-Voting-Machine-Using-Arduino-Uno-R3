Smart Electronic Voting Machine Using Arduino Uno R3

In this project we have used four push buttons for four different candidates. We can increase the number of candidate but for better understanding we have limited it to four. When any voter press any of four button then respecting voting value will increment by one each time. After whole voting we will press result button to see the results. As the "result" button is pressed, arduino calculates the total votes of each candidate and show it on LCD display.
Circuit of this project is quite easy which contains Arduino, push buttons and LCD. Arduino controls the complete processes like reading button, incrementing vote value, generating result and sending vote and result to LCD. Here we have added five buttons in which first button is for BJP, second for MNS, third is for NCP, forth is for OTH means others and last button is used for calculating or displaying results.
The five push buttons are directly connected with pin 15-19(A1-A5) of Arduino with respect to ground. A 16x2 LCD is connected with arduino in 4-bit mode. Control pin RS, RW and En are directly connected to arduino pin 12, GND and 11. And data pin D4-D7 is connected to pins 5, 4, 3 and 2 of arduino.

Skills: I2C · LCD · Arduino IDE · Arduino · Project Management · Problem Solving
