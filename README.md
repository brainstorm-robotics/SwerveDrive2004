<h1><u>Code base for 2024 FRC Competition Robot<br>with REV MAXSwerve Modules</u></h1>
In the spring of 2023, we built a test chassis with four REV MAXSwerve modules. Using the code available
at https://github.com/REVrobotics/MAXSwerve-Java-Template, we successfully got the robot working. We
did not at that time implement a gyro and we found the swerve drive very fast and a bit hard to control
on shiny hallway floors with the chassis bearly tipping the scales at 40 lbs. <i>Undoubtedly, a heavier
robot on carpeted floors would behave more as expected...</i>

Now, in the fall/winter of 2023, we were slow off the start line but are investigating NAVX-2 gyros, FRC Gyro,
infrared and ultrasonic distance sensors and infrared obstacle sensors. We coded classes for:

<h3>Analog Devices (Analog ports on RoboRIO)</h2>
<ul>
   <li>ultrasonic distance sensors (distances up to 5000mm)</li>
   <li>infrared distance sensors (distances up to 800mm)</li>
</ul>
<h3>Digital devices (DIO ports on RoboRIO)</h2>
<ul>
   <li>distance sensors and for infrared obstacle sensors (behaving like limit switches</li>
</ul>
<h3>Gyros (each has a special port on the RoboRIO)</h2>
<ul>
   <li>FRC Gyro</li>
   <li>NavX-2 Gyro</li>
</ul>
Necessary now is to test these sensors and gyros to verify that they work and that we can use them
in suitable applications, e.g. confirming that the gyro orientations are consistent both in terms of 
axes and in terms of whether angles are increasing clockwise or anticlockwise.
<hr>
[add more here]
