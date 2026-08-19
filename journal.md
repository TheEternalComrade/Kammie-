### August 19, 2026 
Circuit diagram finished! Or so I though...I actually ended up forgetting to save it, so I had to start all over again. 
One thing I learned in the process of designing this diagram was that I needed an additional component: a voltage divider. Luckily, it's trivial to make one with the resistors
I have lying around. Essentially, the Arduino runs on 5v logic, and the ESP32-cam on 3.3v logic. If the Arduino tried to send a message to the ESP32-cam without the voltage divider, 
it could get fried. Yapping aside, this is the final image! Time to start on the CAD.
<img width="3000" height="2041" alt="circuit_image" src="https://github.com/user-attachments/assets/cbbf245b-3511-4fb7-923a-86d91c02a73b" />

-1 hr

*****
