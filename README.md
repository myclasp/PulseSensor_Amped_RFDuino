# PulseSensor_Amped_RFDuino

Modified the original pulsesensor.com code https://github.com/WorldFamousElectronics/PulseSensor_Amped_Arduino to work with RFDuino timer.

Works with the pulsesensor.com processing code.

If you try and run the original pulsesensor.com code you will get "error: 'TCCR2A' was not declared in this scope". This is because RFDuino uses a different chip and timers and interrupts are used a little differently. Here we use timer2 that doesn't interfere with BLE comms.

No BLE comms yet in this...
