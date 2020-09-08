# Fitbit
Using LPCExpresso development board to mimic a fitbit

The fitbit sends data periodically to a server known as FiTrackX.
It has three modes of operation: Initialization, Climb and Emergency modes, and will be transmitting to FiTrackX if certain conditions are met. The initialization mode is the mode in which the fitbit is started. Climb mode is the mode in which it is monitoring the climbing statistics. Emergency mode is activated when danger is detected.

The 3 main sensors to be used are the Accelerometer, Light and Temperature Sensor. The accelerometer is assumed to be mounted on the system to detect falling event of the climber. The light sensor is used to monitor ambient environment, where the intensity decreases as the ambient light is dim. The temperature sensor is used to monitor the body temperature of the climber.

This project applies system design approaches, such as using flowcharts, to design embedded applications, secondly, understand the interfaces between microcontrollers and peripherals, and lastly, develop C embedded programming controller-based applications.

