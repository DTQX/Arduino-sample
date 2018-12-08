#MPU6050_DMP6

This sample is based on https://github.com/jrowberg/i2cdevlib.git .

I update it so that it can be just download and complied with Arduino IDE 
and run on board(Arduino uno and Arduino mega2560, Leonardo, Due) with no modify.

Uart rate 115200

pins connections: (reference to https://www.arduino.cc/en/Reference/Wire)
    Board	        I2C / TWI pins
    Uno, Ethernet	A4 (SDA), A5 (SCL)
    Mega2560	    20 (SDA), 21 (SCL)
    Leonardo	    2 (SDA), 3 (SCL)
    Due	            20 (SDA), 21 (SCL), SDA1, SCL1

    INT --> 2 (same for each board)