Just a plugin i made for Endless Sky as a test, don't expect much, just using this to make the process of editing the thing (hopefully) a little less tedious


# mega shipyard template
mission "Mega Shipyard: Level #"
	landing
	source "#"
	destination "Watcher"
	to offer
		"combat rating" > #
	on complete
		event "MS Level #"
		payment #

event "MS Level #"
	planet "Watcher"
		add outfitter "MS Outfits #"
		add shipyard "MS Ships #"

outfitter "MS Outfits #"
	

shipyard "MS Ships #"
