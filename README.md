# Smart Electronic Voting Machine Using Arduino Uno R3

### Introduction :
In this project we have used four push buttons for four different candidates. We can increase the number of candidate but for better understanding we have limited it to four. When any voter press any of four button then respecting voting value will increment by one each time. After whole voting we will press result button to see the results. As the "result" button is pressed, arduino calculates the total votes of each candidate and show it on LCD display.
Circuit of this project is quite easy which contains Arduino, push buttons and LCD. Arduino controls the complete processes like reading button, incrementing vote value, generating result and sending vote and result to LCD. Here we have added five buttons in which first button is for BJP, second for MNS, third is for NCP, forth is for OTH means others and last button is used for calculating or displaying results.

### Block Diagram :

![image](https://github.com/user-attachments/assets/d420d9a5-40c2-493d-bae1-2a0bfcb59a76)


### Circuit Diagram :

![image](https://github.com/user-attachments/assets/82075c1c-12fa-4e67-ba92-4b1f744e9a5b)

### Hardware : 
1. Arduino Uno  
2. 16x2 LCD  
3. Push button  
4. Bread board  
5. Power  
6. Connecting wires

### Software : 
1. Arduino IDE

### Pin Connection :
1) Connect push buttons to Arduino UNO:  
I. The five push buttons are directly connected with pin A1 to A5 of Arduino uno with respect to ground.  

2) Connect LCD 16*2 to Arduino UNO:  
II. Control pin RS, RW and En are directly connected to Arduino uno pin 12, GND and 11 respectively 
III. Data pin D4 to D7 is connected to pins 5, 4, 3 and 2 respectively of Arduino uno

### Working : 
Arduino controls the complete voting processes like reading button, incrementing vote value, generating a result, and sending vote and result in LCD Display. Here we have added five buttons that are assigned for BJP, MNS, NCP, OTH, and the last button is used for calculating or displaying results.

![Smart Electronic Voting Machine](https://github.com/user-attachments/assets/1f8dd5bc-e4bb-48ef-b1a6-be8e5a4c4ee8)


