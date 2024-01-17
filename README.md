# Instructions and dependencies:  
Made for Vivado 2018.2, FPGA type xc7a35tcpg236-1  
Unzip the files into the same folder before running the project in Vivado  
Required:  
- 2 FPGAs  
- 2 OLED displays  
- 2 Mice  
- 3 Wires  

# 2 Player FPGA battleship game, made for Xilinx, using Verilog.  
- The game is ran on 2 simulataneous FPGAs using the UART communication protocol  
- Players would begin the game by playing rock paper scissors to determine the attack order  
- Players would then be given the option to select the position and rotations of each ship using the mouse  
- Once ready, the attacking player would begin. If the bomb hits the enemy ship, they would be allowed to continue bombing, else it switches to the other player.  
- Game will end when the score hits 31; i.e. all of the enemy's ships have been sunk

A video demonstration of how our BattleShip Game works can be accessed through this link:   
https://drive.google.com/file/d/1UYKaLDvdHHDu1VS9cNaeV2V7PMgMl8NZ/view?usp=drivesdk 


