##2019_Player - STM32

#Overview 
Project is  audio player of wav files. The project reads .wav files from the SD card and sends it to the micro-jack output. Files can be switched using the button.
#Description 
To this project we were used stm32f407vg, buttons module, sd card reader. We used SPI to transfering data from sd card to STM. We used the fatfs library.
#Tools 
STM32CubeMX 5.2.1
System Workbench for STM32 Neon.3 Release (4.6.3)
#How to run
Insert the headphones or speaker into the minijack port. Press K7 button to start or stop playing the .wav file. You can switch .wav files using the K6 button. 
#How to compile
Connect SDcard Module:
GND <---> GND
5V <---> 5V
GND <---> CS
PB5 <---> MOSI
PB3 <---> SCK
PB4 <---> MISO
GND <---> GND

Connect Buuttons Module:
PE9 <--->K7
PE10 <--->K6
GND<--->G
#Future improvements
In the future you can improve the function of skipping wav files, to skip files without having to stop the playback.
#Attributions
http://elm-chan.org/fsw/ff/00index_e.html
https://www.youtube.com/watch?v=QIPQOnVablY&t=793s
https://www.youtube.com/watch?v=Y5UMTGQDmog&t=3s
#License
Licencja MIT
#Credits 
Adam Sibila, Łukasz Kopicki

The project was conducted during the Microprocessor Lab course held by the Institute of Control and Information Engineering, Poznan University of Technology.
Supervisor: Tomasz Mańkowski
