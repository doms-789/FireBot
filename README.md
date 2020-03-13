# FireBot


We are creating a fire fighting robot using 3 ultrasonic sensors in the front, left and right. And multiple fire sensors. 

Desired Functionality:
1. Move in a bounded area (no obstacles in the boundary)
2. Approach a wall and turn around to return into the boundary area (do not wall follow)
3. At any time in the roaming - if he sees a fire, approach the fire. 
4. Exstinguish fire - no code for this part yet. 

We are experiencing issues getting the robot to return to the middle of the bounded area. We were able to successfully turn back into the boundary by using a delay in the turning functions, but this delay would render the other sensor data useless. Basically he would overlook the fire while he was turning around. 
