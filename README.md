<h1>MP3 shield</h1>

<p>The SparkFun MP3 Shield is an MP3 decoder with the capabilities of storing music files onto a microSD card, therefore giving you the ability to add music or sound effects to any project, very similar principle works with Touch-board. With this board you can pull MP3 files from a microSD card and play them using one shield, effectively turning any Arduino into a fully functional stand-alone MP3 player. The VS1053 receives its input bit stream through a serial input bus (SPI). After the IC has decoded the stream, the audio is sent out to both a 3.5mm stereo headphone jack, as well as a 2-pin 0.1” pitch header. The Sparkfun MP3 shield is also capable of decoding MP3/AAC/WMA/MIDI audio.</p>

<p>Load mp3 files onto the SD card. Use the convention of 8 characters for the name, no spaces or illegal characters. They will be played based on their order in the directory (i.e. first file= [0] second file=[1] etc)</p>

<p>playing an mp3 causes an interupt. During playing, the arduino is in a delayed state. We found that by connecting the arduino with the shield to a second arduino, then using this second arduino to send serial commands to play the mp3s allows you to run synchoronous code and logic on the first board.</p>

<p>A full guide for setting up the mp3 shield can be found here...</p>

<link>https://learn.sparkfun.com/tutorials/mp3-player-shield-hookup-guide-v15</link>
