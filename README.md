# Smart-Street-Lighting-System

**OBJECTIVE:**

 Street lighting is an essential infrastructure in urban areas, providing safety and 
security to residents and commuters during the night. However, traditional street lighting 
systems are not energy-efficient and often result in unnecessary energy consumption, light 
pollution, and increased maintenance costs. The primary goal of this project is to design and 
implement an IoT-based smart street lighting system that utilizes ultrasonic sensors and 
Arduino Uno boards to intelligently control street lights, thus improving energy efficiency, 
reducing costs, and contributing to a more sustainable environment.

**COMPONENTS REQUIRED:**
1. Arduino Uno, 
2. Ultrasonic sensor HC-SR04, 
3. 7x LEDs,
4. 7x 220 ohm resistor,
5. 1x Breadboard,  
6. Jumper wires.

**CIRCUIT DIAGRAM:**

![image](https://github.com/user-attachments/assets/9d736e4c-7712-4688-921a-a3151145974e)


**WORKING PRINCIPLE:**

• The Arduino sends a pulse to the trig pin of the ultrasonic sensor and waits for the 
echo pin to go high. 
• The Arduino calculates the distance of the object using the formula: 
distance = (duration of high signal / 2) * speed of sound. 
• The Arduino sends the distance value and stores it in a variable. 
• According to the level of distance between sensor and  object the LED will tun and 
OFF


**OUTPUT:**

![image](https://github.com/user-attachments/assets/f7016b80-9951-4d5d-92bc-844427497f80)




![image](https://github.com/user-attachments/assets/ae8d53ca-3125-4eda-9ba6-9cc33dd4d12a)





