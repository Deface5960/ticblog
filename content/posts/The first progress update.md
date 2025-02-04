+++
date = '2025-01-19T15:55:43-06:00'
draft = false
title = 'The first progress update'
+++

Hello again! So what's been going on with me lately? I'm hoping to give you a good idea and description of what I've been working on. Here it goes:

**The Updates**

- Localized LLM 
	- Well this one has been a frustrating experience of patience and buggy software. I've tried over and over again to get open-webui in a functional state, and it just doesn't work, even with the dedicated docker container, I just can't get it to function in a reasonable way, even after making the suggested tweaks by the open-webui GitHub page. This has been a massive hit to my self-esteem and put me off on the project for a few days. I'm hoping to take a step back and reflect on what is going on and possibly switch to another frontend instead of open-webui, maybe that will work better? Who knows.

- NextCloud instance
	- This one has been as successful as standing up the LLM and open-webui. I stood up NextCloud using their docker container, which worked fine for the initial setup, however when setting up the CloudFlare Tunnel in order to access that NextCloud instance, it simply doesn't work even though CloudFlare is configured with the domain and the tunnel is connected and healthy. The NextCloud piece really isn't the issue, it's simply the CloudFlare Tunnel that's making me bang my head against a wall. I tried pointing the tunnel to the IP of the docker container instead of the host, but that doesn't seem to work. I suspect I need to change the networking mode of the container to host mode instead of bridged, but that really shouldn't matter for the most part as long as I'm pointing it to the correct IP address of the container. Yet another frustrating experience, but I don't want that to discourage me and my endeavor to setup my own private cloud.

- Discord bot
	- This just hasn't happened at all, I've been stuck on the other two projects with limited time in the evenings and other hobbies to take on another task. Even then, I still have to get the LLM configured and setup first before I can even think about maybe connecting it to a discord bot in my server. This is the ultimate goal though, to have a Discord bot with interconnectivity with all of my services and provide a cool set of tools for other people to use. I need the other tasks to be completed first before I even think about this one.

**What have I learned?**

- I've learned that docker containers are easy to setup, but also easy to break. After rebooting my container server, I've come to the realization that all of the containers that I've configured are gone, wiped out, terminated, deleted! I have no idea why or how, they're just gone. I still have my container images cached, so it's not like I can't stand them up again, but the containers themselves are just gone. I'm going to attribute this to some kind of setting or configuration I'm not aware of and my inexperience with docker is showing. That's really fine, this is a learning process that only helps me build on what I don't know, so any time I screw up is a learning opportunity.

**What's next?**

- To be straight forward, working on the same stuff I've been working on and hopefully it doesn't implode. I'm having a fun time learning this stuff, but also it's something that's taking up a ton of my time in the evenings. For instance, I recently purchased a brand new Ibanez SR305E bass guitar and would LOVE to start recording music again, but these tech projects also need to have some priority as well, and that's eating into time for other hobbies. That's really fine, because in the end it really does help me overall rather than hurt.

Thanks again for reading if you've made it this far, until next time, this is your man without a face, DeFaced signing off!