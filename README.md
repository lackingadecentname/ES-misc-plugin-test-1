Just a plugin i made for Endless Sky as a test, don't expect much, just using this to make the process of editing the thing (hopefully) a little less tedious


# mega shipyard template
mission "Mega Shipyard: Level #" # change number
	landing
	source "New Boston"
	destination "Watcher"
	to offer
		"combat rating" > # change number
	on complete
		event "MS Level #"
		payment # change number

event "MS Level #"
	planet "Watcher"
		add outfitter "MS Outfits #"
		add shipyard "MS Ships #"
