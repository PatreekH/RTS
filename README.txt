To open:

right click on rts-engine-v1-copy.html

select "open with" ... "chrome browser"

this should default to Chrome. (let me know if not)


To Edit:

right click on rts-engine-v1-copy.html

select "open with" ... "notepad"

scroll down about 200 lines until you find this:

	var unit1 = { //player unit
	    "x": 550,
	    "y": 150,
	    "width": 25,
	    "height": 25,
	    "enemy": false,
	    //"ally": false,
	    "agro": true,
	    "player-color": "#0066FF",
	    "object-type": "unit",
	    "sub-type": "tank",
	    "speed": 2.5, //**MUST BE MULTIPLE OF 25 FOR THE CURRENT VERSION. 1, 2.5, 5 (etc)
	    "damage": 25,
	    "cooldown-active": false,
	    "cooldown-time": 150,
	    //"range": 75,
	    "health": 100,
	    "underAttack": false,
	    "color": "#0066FF",
	    "selectable": true,
	    "selected": false,
	    "moving": false,
	    "currentTile": [(550/25), (150/25)],
	    "hitTile": [],
	    "destinationTile": [],
	    "screenDestinationTile": null,
	    "targetTile": [],
	    "currentPath": [],
		"currentStepInPath": null,
	    "direction_moving": null,
	    "status": "halted" //halted, moving, attacking, firing
	};

You can play around with this however you want. but most of it will probably fuck up the game lol