# Planned-Projects 🥳
Justin's bucket list of ideas he'd like to play with when he has time. <br />
It's a repo because I have no idea how to use Github Projects, and I needed somewhere accessible to put this. 

This used to be hosted on another platform. However, they paywalled me so I'm migrating to Github now.

## Finish UAV Security Research
* Add more UAV attack detections to `DVDsh`
* Create accurate XML/JSON documentation for `MAVLink` (the official ones are borderline unusable; this one is purely out of spite)
* Check if `Damn Vulnerable Drone` actually needs to expose all those UDP/TCP ports (I highly doubt that)
* Find a cheap way to get into IEEE Milcom because I lowkey can't afford to pay $1,000 to present my own co-authored paper

## Look into LPE Malware
Never really got time to do it because of finals week, but:
* Reverse engineer `CopyFail`
* Create Sigma rules for `fragnesia` bc my friends have been freaking out about this (WIP)
* Look at `fragnesia` or `CopyFail` variants out in the wild

## Meshnet Persistence
* `From Threat Intel side`: Lowkey curious how traffic/logs would look like if I just `ssh`'d in via `Tailscale` or `NordVPN meshnet` and then caused some chaos
  * Probably do this first. I'm *much* much more interested in Threat Intel/Detect stuff than I am actually in red teaming/making the hacking tool
* `From attacker side`: Most enterprise servers are not accessible to the public (you can't directly `$ssh` into them with a public IP). This makes things very annoying for an attacker. Maybe create a hacking/persistence tool that drops a meshnet into target device to allow for persistent access
  * Maybe create own meshnet centralized server/endpoint for this because it'll be really obvious if a server is sending heartbeat messages to `tailscale.com` every 60 seconds like uhhhh what are we doing
  * `<rant>` Unless your name is `Canvas LMS` in which case I guess we just ignore the most transparently malicious alerts out there and take a 2 week trip to Cancun. And then come back and go "um justin sorry we got ransomwared 2 weeks ago and all your work/data is getting sold on the dark web now. sorry i could have stopped it a week ago but I didn't expect `ShinyHunters` to actually call my dumb ahh bluff"
  * But seriously how do you see `ShinyHunters` leaving a ransomware letter on your system in 2026 and just go "they're nobodies let's just pretend we didn't see that" `</rant>`

## Document how insecure TPLink routers are
* Been putting it off for 1.5 years now, just got reminded because my friend bought a TPLink router off Amazon
* This is such a dumpster fire that it warrants a writeup (I'm surprised I'm not hacked yet)
* Buy a TPLink router off Amazon again since I wiped the firmware of the TPLink router I had at home with `openwrt`

## Create iOS automated morning messages pointing to this website
* <a href="https://istheinternetonfire.com/">https://istheinternetonfire.com/</a>
* Not really important, but would be funny if I woke up to this:
* <image src="https://i.imgur.com/fY9cD6A.png">

## Create a small blog idk
* Most of my notes/writeups I have right now are on Google Docs
* Probably not a good idea; would like to migrate them all to a website
* (Sorry Rimmo I know you've been telling me to do this for the past like 2 years now, I'll get to it someday)

<hr>

# Very Long Term things I'd like to do someday

## Build a tool to decompile Go
* If I had a penny every time I had to decompile Go since last summer, I would have 5 cents. Which isn't a lot but it's weird that it happened 5 times.
* I'm pretty sure decompiled Go isn't supposed to look as weird as it does on Ghidra
