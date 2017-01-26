#L3GD20H breakout PCB
This is a breakout board for the I2C functionality of the L3GD20H IC gyroscope.
This chip does have SPI and interrupt capabilities, but these are not broken out on this board.

The desgine for this board is dervided from [Adafruits breakout board](https://github.com/adafruit/Adafruit-L3GD20-Breakout-PCB),
the differences are that this board only has I2C capabilities and does not have a voltage regulator. This means that the board should be
powered with 3.3V.

Additionaly this board was desgined in such a way to be pin compatable with [Sparkfun's MMA8452Q breakout board](https://www.sparkfun.com/products/12756). 
These boards can be stacked to help save space in embedded projects.

Design/Changes by William Laney,
Original Design by Adafruit Industries.

Creative Commons Attribution, Share-Alike license, check license.txt for more information. All text above must be included in any redistribution.

##Desgine Notes
This is the first PCB I designed and there are some parts of it that I would change, however I have built this board and it functions properly.
