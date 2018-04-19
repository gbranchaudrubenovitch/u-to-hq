# u-to-hq
increases power limit of 8th-gen U intel cpus up from 15 to 3X watts

## How to run
* Install [RWEverything](http://rweverything.com/download/)
* Add it to your path
* Execute `increase-pl1.bat`
* Your `Power Limit (PL1)` is increased up to 36 watts, until next sleep/hibernation or reboot.

## What's the worst that can happen?
* Blue screen on execution.
* Thermal shutdown under heavy CPU load if laptop fan cannot dissipate CPU heat fast enough.
* Charger failure (fuse blowing? :fire:?) if system pulls too much power while under load and recharge.

## References
* This is taken from http://forum.notebookreview.com/threads/the-throttlestop-guide.531329/page-738#post-10662460
* It's been tested on a i5-8250U and, according to the above thread, an i7-7500U.
