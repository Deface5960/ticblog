+++
date = '2025-02-06T15:55:43-06:00'
draft = false
title = 'It lives again!!!!!!'
+++

It lives! My Jellyfin media server and CloudFlare Tunnel lives again! Finally, after a week of banging my head against the wall I was able to get a second set of eyes on the problem. The issue was due to the docker containers being on separate bridged networks when deployed through the docker compose file. I had no idea this was a problem, and I suspect the only reason it worked previously was because of how I had the host network configured originally and just sheer dumb luck. Regardless, it's working again and I couldn't be happier! Thanks to my buddy PurpleK who assisted with the troubleshooting and helped me narrow down the problem with idea to try. I'm having a problem with cached credentials not working, but honestly I don't really care, I'm just glad it's working and I can troubleshoot that later, it's probably the mount points for the cache and config that need tweaked.

 The next project to tackle is going to be the beginning of my Discord bot. There's tons of documentation out there to help and reference so I don't think it'll be too difficult to navigate my way around the setups and problems that can occur with a Discord bot, but I think I'm going to start small with something simple then build my way up to larger goals like localized LLM's to incorporate into the bot. I might even just use an already established API to get the job done so I don't have to bog down my own desktop with the massive performance requirements of LLM's.

 This is a short update, just wanted to express my excitement over solving something that has been beating me down for the past week. Again, this is your friendly man without a face, DeFaced, signing off!