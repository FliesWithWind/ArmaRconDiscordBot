# readLog

## Setup:
ReadLog is a python script designed to be a flexible interface of reading all kinds of log files. <br>
It's main purpose is to listen to a servers log file and wait for certain events to happen.
<br><br>
In the current configuration it is confirmed for Arma 3 log entries.
## Related:
This Bot directly works with my RCon API:
https://github.com/Yoshi-E/Python-BEC-RCon

## Features:
 * Read Logs in real time
 * Event based for all functionality 
 * uses a config consisting of regex to be easly configured for other Titles

## Donate

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://paypal.me/TeamYoshiE)

## Core Events

 * 
 
## Arma 3 features
Provides recent mission data in a list grouped by misson:

 * Mission readname: contains Mission name in group 2
 * Mission roles assigned
 * Mission reading
 * Mission starting
 * Mission file: contains Mission file name in group 2 (e.g. becti_current (__cur_mp)) without extension
 * Mission world: contains Mission world in group 2 (e.g. Altis)
 * Mission directory: contains Mission in group 2 (e.g. mpmissions\\__cur_mp.Altis\\)
 * Mission read
 * Mission id: contains unique Mission id in group 2 (e.g. 13dfdd0042a09e918dfe17933d1372e6cefc3f9a). Unique for every session, if you load a save file, the id will remain identical.
 * Mission started
 * Mission finished

## Monetization
This Bot (or code that I own inside) __cannot__ be used in a monetization process.
However you can ask for permission.

## Licence

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">JMWBot</span> by <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">Yoshi_E</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.<br />

This project is not affiliated or authorized by Discord or Bohemia Interactive a.s. Bohemia Interactive, ARMA, DAYZ and all associated logos and designs are trademarks or registered trademarks of Bohemia Interactive a.s. 
