# Grainstation-C

Written by Micah Frank under GPLv3

<http://micahfrank.com>

<http://micahfrank.bandcamp.com>

Grainstation-C is an open-source, granular performance workstation designed to build realtime, evolving sound sculptures with optional ambisonics. It seamlessly integrates with a Novation LaunchControl XL Mark 2 (easily modifiable for any other controller) and can processes 4 disk tracks and 3 live input streams. You can save any state as a snapshot and morph to that snapshot at any point in a performance. It has 6 independent pitch delay lines, 6 switchable low pass and high pass filters, live audio looping and multiple granular processing controls including granular time-stretching, frame animation and granular pitch shifting.

Grainstation-C was originally inspired by the Make Noise System Concrete but shortly took on many unique characteristics of its own. http://www.makenoisemusic.com/synthesizers/system-concrete

I used it on my latest album [Quetico](https://micahfrank.bandcamp.com/album/quetico) extensively to process field recordings and create walls of textures. I very happy happy to now offer it to the public!

Watch this [demo video](https://youtu.be/BQ5MSDqFaX8) to see what it can do!

<a href="https://youtu.be/BQ5MSDqFaX8" target="_blank"><img src="http://img.youtube.com/vi/BQ5MSDqFaX8/0.jpg" alt="Grainstation-C Demo" width="240" height="180" border="0" /></a>

**Questions**

Please ask any questions in the issues section: https://github.com/chronopolis5k/Grainstation-C/issues

**Controller**

Grainstation-C has been developed to integrate with the Novation Launch Control XL Mark2. However, any other controller should work as well. The MIDI note and controller mapping schema is in the [MIDI Specification.txt](https://github.com/chronopolis5k/Grainstation-C/blob/master/MIDI%20Specification.txt) file

This repository includes 4 template pages for the Novation Launch Control XL. To change pages, press [User + Track Focus 1-4] buttons

• Page 1 - Granular Controls - pitch, time-stretch, grain size

• Page 2 - Granular and Filter Controls - grain duration, filter type (low pass, high pass), filter frequency

• Page 3 - Pitch Delay Controls - delay time, delay feedback, delay pitch shift

• Page 4 - Delay and Convolution Controls - delay send amount, convolution send amount

• Page 5 - Ambisonics / Spatial Audio Controls - azimuth angle, altitude angle

Download the Launch Control XL Mk2 software (for loading the templates): https://bit.ly/2y3rWul

**Recording**

You can render a file in real-time to the /renders folder simply by pressing the [Record Arm] button on the Launch Control XL. The button will begin to blink and your performance will be recorded. You can stop and restart recording as needed by pressing the button again.

**Ambisonics**

You can enable the ambisonics flag and immediately tweak the azimuth and altitude for any track. When you render the performance, a multichannel B-encoded file will also be rendered to the "b_format" folder.

**Installation**

Grainstation requires Csound: http://csound.com/download.html CsoundQT comes with Csound and will enable you to run Grainstation C.

See this video for a quick explanation about installation and setup
https://www.dropbox.com/s/im1vivrjv98isub/Grainstation-C_config.mp4?dl=0

**Page Controls Overview**

<img src= "https://github.com/chronopolis5k/Grainstation-C/blob/master/LaunchControl%20XL%20Templates/Page_Overviews/Page1.jpg" width="450" height="507">
<img src= "https://github.com/chronopolis5k/Grainstation-C/blob/master/LaunchControl%20XL%20Templates/Page_Overviews/Page2.jpg" width="450" height="507">
<img src= "https://github.com/chronopolis5k/Grainstation-C/blob/master/LaunchControl%20XL%20Templates/Page_Overviews/Page3.jpg" width="450" height="507">
<img src= "https://github.com/chronopolis5k/Grainstation-C/blob/master/LaunchControl%20XL%20Templates/Page_Overviews/Page4.jpg" width="450" height="507">
<img src= "https://github.com/chronopolis5k/Grainstation-C/blob/master/LaunchControl%20XL%20Templates/Page_Overviews/Page5.jpg" width="450" height="507">
