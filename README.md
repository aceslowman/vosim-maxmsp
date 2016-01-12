# vosim-maxmsp
Experiments with the vosim voice synthesis method in Max/MSP and Gen.

The vosim system for vocal synthesis was created by Kaegi and Templaars in the 1970's, but it still seems like an interesting alternative to formant subtractive synthesis. 

It is characterized by a series of pulsetrains, consisting of sin^2 waves of a specified number of periods, decay rate, and delay. The result is a formant, and with the extended parameters that were developed through the 70's and 80's, it began to allow for fricatives, plosives, and greater flexibility for transitional sounds. 

Currently, my experiments with it in Gen have been interesting, but definitely not complete. The variables are there, but I am currently having problems getting multiple vosim generators to sync accurately, having trouble getting plosives and fricatives to sound right, and haven't really thought through how to approach a system of interpretting speech commands to generate speech in real time. 
