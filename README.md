# Hyperion_Gerbers
Gerber files of PCB designed for task 2 of Hyperion



-----------------Summary-------------------
The MPU6050 is a Micro Electro Mechanical System that integrates a 3 axis accelerotmeter and 3 axis gyroscope in a 4 x 4 x 0.9 mm pcb. The onboard Digital Motion Processor simultaneously measures angular velocity (gyro) and linear acceleration (acc) and provides sensor fusion with other sensors, freeing up the uController for other tasks. 
The I2C bus present allows it to act as a master while the other sensors as slave, creating sensor fusion with other sensors and gaining 9 dof. (Example it can create sensor fusion with a magnetometer and create a 6+3 dof). The auxilary bus can also interface with other sensors such as barometric pressure sensors, further enhancing data gathering capabilities. 
It consists of a 1024 byte FIFO buffer which collects data in constant burst, providing efficient reading from uController instead of contantly polling the device. Thus the microcontroller can enter low-power sleep mode to gather more data.
