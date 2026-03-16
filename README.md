# DwarfFortress_NewVenice
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
