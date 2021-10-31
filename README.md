# Introduction: 
In this project you are required to implement a simple calculator on Basys 3 FPGA boards.
Note: Due to the big size of the project, you should create a new project, and take the uploaded source code.

# Specifications: 
You are required to build a simple calculator such that it:
- Generates two numbers from 0 to 99
- Displays the two numbers on the 7-segment displays The first two digits are of the 1st number (located on the left) and the second two digits are of the 2nd number (located on the right) with the decimal point in between always “on”. B1, B2, B3 and B4 are used to adjust the digits of each number respectively. Ex: B1 sets the tens of the 1st number.
- If B5 is pressed the FPGA displays the result of addition of the two numbers on  the 7-segment display.
- If B6 is pressed, the FPGA shows the result of subtracting the 2nd number  from the 1st one. For example if the two numbers are 50 and 75 respectively, -25 should be displayed.
- If B7 or B8 are pressed, multiplication or division (1st number over the 2nd one) is performed respectively. 
- If B9 is pressed, the FPGA displays the original two numbers on the 7-segment display.
- In the division part, integer division should be applied (round to the nearest integer)
