# [HoloFire](https://www.sjsuvrlab.org/project_holofire.html)
## HoloLens App for Fire Safety Training
https://www.sjsuvrlab.org/project_holofire.html
***********

The HoloFire project utilizes Microsoft HoloLens in order to create a training system designed to build skills for combating fire emergencies, operate calmly under stressful situations, and reduce unnecessary workload for firefighters. Users are educated on crucial actions to take and factors to consider in order to survive and escape a burning building. The HoloLens simulates fire and smoke to construct scenarios and a Heads-up Display to help the users navigate through each scenario.

### Heads-Up Display Features
 
The HUD is the UI that can be seen when a scenario is started and will remain on top of a user’s view as an overlay throughout a scenario. It consists of seven primary components and can be seen in Figure 5.
 
##### Timer

The amount of time left to complete the scenario is shown in the bottom right corner of the user’s perspective. The time is displayed only at beginner levels. In advanced levels, the time will not be displayed to give the user a sense of realism as, in reality, one would not know exactly how much time they have left in a burning building. The timer was designed to turn red and blink during the last 10 seconds of the scenario in order to emphasize a sense of urgency to the user. 
 
##### Temperature Sensor

The temperature sensor indicates the temperature in the user’s current position. A thermometer icon was used as the temperature sensor’s visual. When the user is in close proximity to fire or in very high temperature areas, the sensor will rapidly increase in temperature. In all other areas the temperature sensor will increase at a slower rate. The temperature can be seen in text format while the icon for the temperature sensor will fill up with red based on the temperature. The temperature sensor text was designed to turn red and blink during the last few units of filling the sensor icon with red in order to emphasize a sense of urgency to the user. The idea for the temperature sensor to be added was feedback the team received from the Milpitas Fire Department.
 
##### Oxygen Concentration Indicator

The oxygen indicator gives the user information about how much oxygen is available to the user. The concentration of oxygen is based on the user’s posture. For example, if the user is standing up the oxygen indicator would decay at a faster rate than when compared to when the user is crouching in the same location. 
 
##### Heartbeat Indicator

The heartbeat is an audible and visual notification. There is a regular heartbeat that the user can hear and the pace changes according to the user’s current condition. If the user is in danger (close proximity to fire), the pace is faster. In addition, there is an animated heart icon on the UI of the user to provide a visual depiction. This visualization helps users who are hearing impaired.

##### Posture Indicator

The posture indicator shows the current posture the HoloLens assumes the user is in. Since different people have different forms of crouching, the HoloLens can inform the user if it detects the user as crouching or standing. This indicator is available in advanced levels as well.
 
##### Hints

The hints bar is positioned at the top of the HUD and is only available at beginner levels as it is to give the user tips on how to successfully escape the fire. For example, the user is hinted to crouch and move forward in a very smoky area as shown in Figure 11, above.

##### Directional Indicator

The directional indicator is an arrow that points to the escape location or the final destination to give the user a sense of which direction to move. This is also available only to users completing a scenario in less difficult levels.
