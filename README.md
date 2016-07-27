# PiBadge24 -- Defcon 24 / Bsides PiBadge Stuff

__ToDo List__

  
  - [x] Download Current Adafruit Raspbian Lite w/ TFT Driver
  - [x] download omxplayer + dependices packages
  - [x] make omxplayer install script - http://omxplayer.sconde.net/
  - [x] make mplayer install package
  - [x] make / borrow script to resize partition
  - [x] make script to change kb layout / locale
  - [x] make script to enable ssh
  - [x] make network config script
  - [x] make script to change refresh rate of display?
  - [x] make fbcp install script? 
  - [x] Check out other video looper - https://github.com/timatron/videolooper-raspbian
  - [ ] Upload new videos
  - [ ] Make installer script
  - [ ] Make updated Generic TFT Raspbian Image
  - [ ] Make updated PiTFT Image
  
Optional Tasks
  - [ ] Configure day / con based video playback script
  - [ ] Add "Touch to skip video function for touchscreen displays
  - [ ] Make "Party Mode"
  - [ ] Make quake3 package
  - [ ] make doom package
  - [ ] metasploit framwork? 
  - [ ] custom boot logo / image?
  - [ ] dosbox? Windows 3.1?
  - [ ] mesh networking


__From Scratch Install Steps__
* Download the Adafruit PiTFT+ lite image: https://learn.adafruit.com/adafruit-pitft-3-dot-5-touch-screen-for-raspberry-pi/easy-install
* Burn it to a sd card
* log in, connect to a network, update packages "sudo aptitude update && sudo aptitude upgrade"

__Video Players / Issues__

There are two video players that do not require X and work well on the pi. Those are:
mplayer2
omxplayer

Mplayer2 can output directly to an arbitrary framebuffer eg. /dev/fb1 which is where our TFT lives. Omxplayer will only output to /dev/fb0 so you need to use a tool to copy the memory of fb0 to fb1. There are two tools that do this. fbcp and raspi2fb. Raspi2fb is supposed to be faster, but I have had issues getting it to work.

rpi-fbcp: lower cpu usage 
raspi2fb: higher cpu usage, but video seems smoother https://github.com/AndrewFromMelbourne/raspi2fb

__Video Ideas__

The theme of Defcon this year is "Rise of the Machines" Im thinking of going with some crazy AI movie clips + random CG art 

* Terminator
* Hal 9000
* Blade Runnner
* DC Zia Logo Exploding
* VLA Clips
* Random www.beeple-crap.com
* Ghost in the Shell
* The Matrix
* Systems crashing anthology?
* Hackers
* Neon Genesis Evangellion

## Defcon / Bsides Random info

Schedules! Print one out or download a pdf:

--Bsides Schedule: https://bsideslv2016.sched.org/

--Defcon Schedule: https://defcon.org/html/defcon-24/dc-24-schedule.html

--Defcon Bands / music: https://defcon.org/html/defcon-24/dc-24-entertainment.html


__Parties__

Defcon Parties: http://defconparties.com

Key Parties:

Tue Aug 2nd

--Cylance / Alice in Chains @ House of Blues: Full? https://info.cylance.com/blackhat-2016-house-of-blues

--FireEye @ Eyecandy: https://www2.fireeye.com/Black-Hat-Las-Vegas-2016.html

--Distil Networks with Coolio?! @ Light http://info.distilnetworks.com/blackhat-2016-light-nightclub?utm_campaign=Black%20Hat%202016&utm_source=BugCrowd


Wed Aug 3rd

--BSides Pool Party (Dual Core, YT Cracker, Jakalope): Wed 10pm

--Rapid7 @ Hakkasan https://www.google.com/url?q=http%3A%2F%2Fbit.ly%2Fdcprapid716&sa=D&ust=1469211023115000&usg=AFQjCNFnrAxwy-nfvUpxvxAjAY9_KdKw_Q

--Cylance @ Minus5


Thusday Aug 4th

--All in Party @ Minus5 https://www.eventbrite.com/e/the-all-in-party-5th-annual-tickets-26245471913


Friday Aug 5th

--DCParties music (Zebbler Encanti, Dual Core, Jakalope)

--DC505

--DC303


Saturday Aug 6th

--DCParties Music pt 2 (Insoc / Berlin)

--IOActive Freakshow

--DC801


Sunday Aug 7th
