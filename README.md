﻿# LoraShieldIOT2000  
 Library is modified for custom interrupt pins of Dragino Shield.  
 
 ````
 /**
     * SX1276 constructor
     *
     * Since this is a shield, you will not have much choice as to
     * what pins are used.
     *
     * @param chipRev chip revision, default is 0x12
     * @param bus spi bus to use
     * @param cs GPIO pin to use as SPI Chip Select
     * @param resetPin GPIO pin to use as reset (A0=GPIO14)
     * @param dio0 GPIO pin to use as reset DIO0 intr
     * @param dio1 GPIO pin to use as reset DIO1 intr
     * @param dio2 GPIO pin to use as reset DIO2 intr
     * @param dio3 GPIO pin to use as reset DIO3 intr
     * @param dio4 GPIO pin to use as reset DIO4 intr
     * @param dio5 GPIO pin to use as reset DIO5 intr
     */
    SX1276(uint8_t chipRev=chipRevision, int bus=1, int cs=10, int resetPin=9,
           int dio0=2, int dio1=6, int dio2=4, int dio3=5, int dio4=17,
           int dio5=8);
````
