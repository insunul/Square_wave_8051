# Square_wave_8051
10k hz square wave with 8051 microcontroller
8051 one machine cycle have 12 pluse.
time cycle shuld be 12/11.0592=1.085 micro second.
so , want to dalay = delay*time cycle.
so ,delay=want to delay/time cycle.
for timer (max count-delay).
make dalay for 10khz T=(1/f)=(1/10000)=0.1 milli second
count =(0.1/1.085)*1000=90
90 convart to hex velue .uplod to timer. and run to make 10k hz
