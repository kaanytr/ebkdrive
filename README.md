# ebkdrive
An open-source sensored BLDC controller board that integrates all necessary components into a compact form factor which is 65x65mm. I designed it to be cost effective and reliable solution for e-bikes, scooters, skateboards etc.
The controller integrates STM32 blackpill as microcontroller. The converter that steps down a 36V battery input to 5V for powering the microcontroller and a step-up converter that boosts the 5V to 12V in order to supply the gate driver ICs. For now, it runs on open loop speed control by using a potentiometer which can be substituted for a throttle lever. 
The board is designed to work with 36 V but, considering the the parts I have chosen it should tolerate 48 V operation as well(Not tested yet).
Continious Current capacity : 15A
Peak Current : 30A

