# Cookie-Clicker-C64

<p align="center">

<img src="https://github.com/IanSkinner1982/Cookie-Clicker-C64/blob/master/Banner.png"/>

<p align="center">

<a href="https://discord.com/invite/kJac2ty">
        <img src="https://img.shields.io/discord/704065693246685225?color=purple&label=Discord&logo=Discord&style=plastic"
            alt="Chat on Discord">
</a>
<a href="https://www.youtube.com/channel/UCjbecKNosrmUgRIOqU0UxCw/" style="padding-left: 5px; padding-right: 5px;">
		<img src="https://img.shields.io/badge/YouTube-Channel-red.svg" height="20">
</a>
  <a href="https://gbatemp.net/download/cookie-clicker-c64.36587/" style="padding-left: 5px; padding-right: 5px;">
		<img src="https://img.shields.io/badge/GBAtemp-Link-blue.svg" height="20">
</a>
  <a href="https://github.com/IanSkinner1982/Cookie-Clicker-C64/" style="padding-left: 5px; padding-right: 5px;">
		<img src="https://img.shields.io/github/downloads/IanSkinner1982/Cookie-Clicker-C64/total?color=Green&label=Downloads&logo=Github" height="20">
</a>
</p>

Cookie Clicker C64 (or CC64 for short) is a Cookie clicker clone for the Commodore 64.

## No this project is not dead. I have been doing a lot of planning for a whole new program design. Join my Discord server if you want to see my progress so far.<br> - Ian Skinner

## How to play : 

- Press the space bar to 'click' for cookies.

- Buy/select items by pressing the letter beside them. (the one in brackets)

## Saves:

Saves must be named cc64.sav and placed in the same directory as cookie.prg. (to copy the save onto a d64 file, use <a href="http://lallafa.de/blog/c64-projects/diskimagery64/" target="_blank">DiskImagery64</a> or another disk editor.)
<br>Currently saves are only available in the nightly builds.
 

### Save file format:

<p>
	Stop key flag
<br>Cookies
<br>Cookie gain
<br>Cursor amount
<br>Grandma amount
<br>Farm amount
<br>Mine amount
<br>Player name
<br>
<br>The stop key flag must be `0` or `1`.
<br>`0` will prevent the player from stoping the program, and `1` allows the player to stop the program.

### Example save file:

<br>0
<br>3426597
<br>0.9823
<br>230
<br>54
<br>32
<br>1
<br>IANSKINNER1982</p>

## Credits and Notes

Credits: 
- [@Orteil](https://orteil.dashnet.org/) (for making the original cookie clicker game)

Notes: 
- Due to the way I have everything set up, some of my commits will appear as commits by [@drskinner](https://github.com/drskinner/)
- Editing program lines larger than 80 characters on the C64 (or on an emulator) will result in parts of them being deleted






