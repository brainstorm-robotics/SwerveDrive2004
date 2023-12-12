# SwerveDrive2004
Code base for 2024 FRC competition robot with swerve drive 
----------------------------------------------------------
In the spring of 2023, we built a test chassis with four REV MAXSwerve modules. Using the code available
at https://github.com/REVrobotics/MAXSwerve-Java-Template, we successfully got the robot working. We
did not at that time implement a gyro and we found the swerve drive very fast and a bit hard to control
on shiny hallway floors with the chassis bearly tipping the scales at 40 lbs. (Undoubtedly, a heavier
robot on carpeted floors would behave more as expected...)

Now, in the fall/winter of 2023, we werw slow off the start line but are investigating NAVX-2 gyros, FRC Gyro,
infrared and ultrasonic distance sensors and infrared obstacle sensors. We coded classes for:

Analog Devices (Analog ports on RoboRIO)

   ultrasonic distance sensors (distances up to 5000mm)
   infrared distance sensors (distances up to 800mm)

Digital devices (DIO ports on RoboRIO)

   distance sensors and for infrared obstacle sensors (behaving like limit switches

Gyros (each has a special port on the RoboRIO)

   FRC Gyro
   NavX-2 Gyro

Necessary now is to test these sensors and gyros to verify that they work and that we can use them
in suitable applications, e.g. confirming that the gyro orientations are consistent both in terms of 
axes and in terms of whether angles are increasing clockwise or anticlockwise.
- - - - -
<< add more here >>
