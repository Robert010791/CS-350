# Robert Robbins
CS-350
CS-350 course work


The two projects from this course that I am most proud of and enjoyed the most are the Morse Code and Thermostat programs. The Morse Code program uses a blue and red light to send messages through morse code. There are two messages that can be transmitted which are “SOS” and “OK” and pressing the button changes the message being transmitted. The problem this project solves is being able to send morse code messages over long distance using lights. If a person was stranded and needed help they could use this system to get help. The Thermostat project uses an LCD screen to display room temperature, the temperature set point and if the thermostat is off, heating or cooling. It solves the problem of controlling a users HVAC system. 
	Both of these projects use a state machine design implemented in python using the state machine library. One thing I did well in this course was translating what I learned about state machines in C and implementing it with python using a library that I had never used before.
One area that I could improve on is understanding how threading works. I ran into an issue with the Thermostat project when frequent multiple calls to the AHT20 sensor cause issues. When testing the system to cycle through states and change the set points the program would crash, the screen would freeze or a state would be skipped. I changed the program to only call the AHT20 sensor once a second and had all functions that used the temperature get it from the same place.
