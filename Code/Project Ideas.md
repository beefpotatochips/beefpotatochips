List of project ideas. If I don't make the notes here, I won't at all.
Everything in this list is free to use as a concept. I'll update the list as the projects get actualized with links to them. 

- Anglers Handbook
	- Simple to use optimiser for FFXIV's Fishing Content. There's a lot of optimizations and useful info that can be collated and displayed:
	- Best route (chaining uptimes, start-from-x-go-to-y TSP solutions for each zone/aetheryte)
	- Average bait needed (each fish has specific chances to be caught, and we can utilise that info to determine, on average how much bait you'd need to catch a fish with safety guards for over/under pct chance.)
	- Pre-window prep (sometimes, fish have requirements other than weather/time. if those parts can be preloaded, to help increase the chance you catch the fish you should be able to have an alarm set prior)
	- Stat tracking (hey, numbers are fun! if you could sync your local data to send the stats and draw some pretty info on it, why not?)
	- Leaderboards (Ocean Fishing. What if FFLogs existed for it?)
- Anglers Umbrella 
	- [Dalamud](https://github.com/goatcorp/Dalamud) plugin, written in c# for encoding & sending fishing info. Lets you see your spoon rate, average time to catch, etc. Websockets a likely candidate! I need to look into how sensible ws is in c# these days...