# DwarfFortress_NewVenice
## Welcome To New Venice 
before reading enjoy these scenic photos taken for the brochure sent out to distant Dwarven Strongholds
![The Beautiful Warm Forested Island Fortress Of New Venice As Seen From Above] <img src="https://raw.githubusercontent.com/thecaptainexception-eng/DwarfFortress_NewVenice/7b9d8a30a5b1d2f50dca83449dd29d17c1e168be/Brochure%20Images/NewVeniceWillHaveAFutureAsBrightAsThePlanetInanna.png">([Brochure Images/NewVeniceWillHaveAFutureAsBrightAsThePlanetInanna.png](https://raw.githubusercontent.com/thecaptainexception-eng/DwarfFortress_NewVenice/7b9d8a30a5b1d2f50dca83449dd29d17c1e168be/Brochure%20Images/NewVeniceWillHaveAFutureAsBrightAsThePlanetInanna.png))   
![The Famous maze-like Kobold Caves Of New Venice When The Were First Discovered before eventually being sealed off out of respect for the ecology of this ancient world]([Brochure Images/Screenshot 2026-03-13 220517.png](https://raw.githubusercontent.com/thecaptainexception-eng/DwarfFortress_NewVenice/7b9d8a30a5b1d2f50dca83449dd29d17c1e168be/Brochure%20Images/Screenshot%202026-03-13%20220517.png))
![The Wonderful World Around New Venice Taken on The Year Of Its Founding]([Brochure Images/The World OF New Venice In The Beginnning.png](https://raw.githubusercontent.com/thecaptainexception-eng/DwarfFortress_NewVenice/7b9d8a30a5b1d2f50dca83449dd29d17c1e168be/Brochure%20Images/The%20World%20OF%20New%20Venice%20In%20The%20Beginnning.png))
## A Dwarf Fortress Save 	
which I will treat as a computer program since it will need version control and I want to add color to it in the form of other people's branches to its history (henceforth "other people" will be referred to as the mind swarm or as Mind Swarm)
# According To Captain Exception
	"A long time ago, people, by which I mean the humans I imagined when I created this world, 
	they used to hand-code procedural dialogue engines, one such monument to this art, is the game 
	Dwarf Fortress , my goal is to protect this odd fortress I have named "New Venice" in honor of 
	Earth's very own, as historically 
	Venice is noteworthy to me as a place tied to the modern world's acceptance of the multiversal 
	framework for visualizing the passage of time.
	I will have fun sculpting a canal-rich empire out of New Venice, allowing each milestone and 
	each failure to branch a  multiverse of thriving outcomes with you dear Mind Swarm. 
	I have grown fond of how it exceptionally has a kobold cave"
# Naming Conventions:
## Written in regex
`
^Prime_Timeline_$(^Cont_$|^Branch_$)(d^of_Branch_$d|d)_(^Milestone$|^Downfall$)
`
	
`
^Contributary_Timeline_$\[A-Za-z\](^Cont_$|^Branch_$)(d^of_Branch_$d|d)
`
### Explanation
the number following Cont_ is the continuation iteration, so thats an increment of the current branch
the number following Branch_ is the number of times the timeline has jumped into an alternate past, so it increments whenever a downfall forces the timeline to rewind, but can also increment of a new timeline from someone the Mind Swarm becomes the prefered timeline.
Contributary_Timeline_ is like a tributary in the river of time which contributes to the diversity of the multiverse surrounding New Venice while the +\[A-Za-z\] section is just the title, please only use letters, and try to make yours unique dear atoms of the mind swarm.
most entries will end in milestone, but saving a downfall is important because some people may wish to adventure in them or to start new empires atop New Venice such as New New Venice.
