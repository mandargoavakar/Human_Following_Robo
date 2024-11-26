# Obstacle_Robot
The **All_in_One_Robot_2.ino** file is Arduino code for a robot using motor drivers, IR, ultrasonic sensors, and a servo. It includes libraries for Bluetooth and IR control. Functions handle motor speed, obstacle detection, and modes like manual or autonomous. It’s modular and easily customizable.
The All_in_One_Robot_2.ino file contains Arduino code designed to control a multifunctional robot. It incorporates various hardware components and libraries to enable features like motor control, sensor readings, and communication. Key elements include:

Libraries:

SoftwareSerial: Facilitates communication with a Bluetooth module.
IRremote: Handles infrared (IR) communication, possibly for remote control.
Hardware Setup:

Motor Driver (L298): Controls two motors using defined pins (enA, in1, in2, etc.).
Sensors:
IR sensors: Detect obstacles or line positions (R_S, L_S).
Ultrasonic sensor: Measures distances using echo and trigger pins.
Servo Motor: Controlled via pin A4 for precise positioning.
Variables:

Parameters for sensor thresholds, motor speed, and modes of operation are pre-defined, such as distance_F (forward distance threshold, 30 units) and Speed (default motor speed, 130).
Setup Function:

Initializes pin modes for input/output.
Configures communication with peripherals and sensors.
This code is structured to handle multiple functions, potentially including manual and autonomous modes of operation. Its modular design supports easy customization and integration of additional features.
