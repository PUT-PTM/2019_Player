<h1>2019_Player - STM32</h1>

<h2>Overview </h2>
<br>
Project is  audio player of wav files. The project reads .wav files from the SD card and sends it to the micro-jack output. Files can be switched using the button.
<br>
<h2>Description</h2>
<br>
To this project we were used stm32f407vg, buttons module, sd card reader. We used SPI to transfering data from sd card to STM. We used the fatfs library.
<br>
<h2>Tools</h2>
<br>
STM32CubeMX 5.2.1
System Workbench for STM32 Neon.3 Release (4.6.3)
<br>
<h2>How to run</h2>
<br>
Place .wav files from the "sdcard" folder on the sd card, then place the sd card in the card reader. Insert the headphones or speaker into the minijack port. Press K7 button to start or stop playing the .wav file. You can switch .wav files using the K6 button. 
<br>
<h2>How to compile</h2>
<br>
<h3>Connect SDcard Module:</h3>
<br>
GND <---> GND<br>
5V <---> 5V<br>
GND <---> CS<br>
PB5 <---> MOSI<br>
PB3 <---> SCK<br>
PB4 <---> MISO<br>
GND <---> GND<br>
<br>
<h3>Connect Buuttons Module:</h3>
PE9 <--->K7<br>
PE10 <--->K6<br>
GND<--->G<br>
<br>
<h2>Future improvements</h2>
<br>
In the future you can improve the function of skipping wav files, to skip files without having to stop the playback.
<br>
<h2>Attributions</h2>
<br>
http://elm-chan.org/fsw/ff/00index_e.html
https://www.youtube.com/watch?v=QIPQOnVablY&t=793s
https://www.youtube.com/watch?v=Y5UMTGQDmog&t=3s
<br>
<h2>License</h2>
<br>
Licencja MIT
<br>
<h2>Credits</h2>
<br>
Adam Sibila, Łukasz Kopicki
<br>
The project was conducted during the Microprocessor Lab course held by the Institute of Control and Information Engineering, Poznan University of Technology.
Supervisor: Tomasz Mańkowski