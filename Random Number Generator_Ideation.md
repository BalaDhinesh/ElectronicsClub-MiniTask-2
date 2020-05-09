__The web link for this project description:__
https://www.electronicshub.org/random-number-generator-using-8051/



# Problem Statement:
To generate a random number in between 0 to 100 when a push button is pressed. 



__Components Used:__


- 8051 Microcontroller


- LCD Display


- Push button



# Ideation:


__Understand the project mechanism:__


Push button -> Random Number Generator -> Push button -> Random number on LCD Display



| __Component__ | __Feasibility__ | __Advantages__ | __Disadvantages__ |
| --- | --- | --- | --- |
| 8051 microcontroller | Easy to implement and work with knowing some programming skills beforehand. | Execution speed is high since it is not reprogrammable | Cost is little high. It is also a bit outdated and slow. |
| LCD Display | Very Feasible | Compact, thin and light and consumes less amount of power | In high temperature environments there is loss of current. From the viewing angle, the color and contrast not consistent. It is not suitable for very brightly environments.



The suggested idea is very good. I would like to add further with my ideas. Instead of 8051 microcontroller (which is used to store the program by burning the code to the microcontroller by any compatible software which consumes more time) we can use IC 555 timer and IC 4026 where timer is wired as astable multivibrator where it generates square waves to feed the IC 4026(7 segment decoder). We can keep the frequency output high so that the user cannot judge the number sequence by any means. A button can be placed in way of this signal which is feed to the IC 4026 when button is pressed. The random number generated between 0 and 99 can be displayed with two common cathode 7 segment displays thereby consuming less power and time. 8051 microcontroller and 16x2 LCD display costs around 1200INR and 500INR respectively. Whereas 555 timer, IC 4026 and two 7 segment display costs around 20INR, 50INR, 30INR respectively thereby saving a lot a money.  




__Resource that help me to a better solution:__
https://www.gadgetronicx.com/random-number-generator-circuit/
