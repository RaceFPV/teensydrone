# teensydrone

=== Autonomous drone using a teensy 3.1 and basic arduino components

* Controlled via a bluetooth module (HC-05)
* Self leveling using an MPU6050 9-axis gyro
* Collision avoidance using sonar sensors (HC-SR04) x5
* Optional multicolor LED to display collision detection status

=== Pinouts
* Sonic sensor 1 trig pin: 12
* Sonic sensor 1 echo pin: 11
* Sonic sensor 2 trig pin: 0
* Sonic sensor 2 echo pin: 1
* Sonic sensor 3 trig pin: 16
* Sonic sensor 3 echo pin: 17
* Multicolor LED blue pin: 23
* Multicolor LED red pin: 22
* Multicolor LED green pin: 21
* MPU6050 INT pin: 6
* MPU6050 SCL pin: 19
* MPU6050 SDA pin: 20
* HC-05 rx pin: 8
* HC-05 tx pin: 7

=== LED status
* green -- All clear
* blue -- object detected
* red -- boot in progress/error
