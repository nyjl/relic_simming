# 847 "One against many" or 758.6 "Unending rage"?

Remember, there are no stupid questions!
Except for this one though, because the answer is always "sim it yourself".

# Step 1. Get SimulationCraft

Using the latest nightly build is recommended as it includes the latest hotfixes/changes.

http://downloads.simulationcraft.org/?C=M;O=D

![](http://i.imgur.com/6ZojHKe.png)

Pick the one with the most recent date (should be at the top) that ends in .7z. Download, unzip.

# Step 2. Launch SimulationCraft

Go to unzipped folder, launch SimulationCraft64.exe (or 32 if you are using 32bit version)

![](http://i.imgur.com/nGq8XnN.png)

you'll end up here

![](http://i.imgur.com/undefined.jpg)

# Step 3. Import your character

There are two ways to do it. You can install this addon

https://mods.curse.com/addons/wow/simulationcraft

go ingame, write "/simc", copy your profile from the window, go to "Simulate" tab

![](http://i.imgur.com/7GvVu27.png)

push on the plus to add a new profile

![](http://i.imgur.com/vDDupCV.png)

and paste your profile here. All set!

Second way is go to import tab

![](http://i.imgur.com/ZHmpElZ.png)

Write all your character info, push Import, and it will be exported from WoW armory

![](http://i.imgur.com/9gpi6Mx.png)

Your profile ends up in the same place, at "Simulate" tab

# Step 4. Find a relic you want to try out on Wowhead
http://wowhead.com

find you relic through search

![](http://i.imgur.com/undefined.jpg)

choose the correct ilvl version of you relic

![](http://i.imgur.com/zlvT8P2.png)

now you need info from your URL string

![](http://i.imgur.com/BDfYZoX.png)


# Step 5. Edit your profile to change a relic

Scroll to the end of your profile and find a line starting with "main_hand=", copy it

![](http://i.imgur.com/SmBqhXw.png)

Add couple of lines at the end of your profile


`copy="me with a new relic"`

`paste a main hand line here`

this will look like this

![](http://i.imgur.com/eyrjZmo.png)

now we have do edit your new main_hand line to change a relic in it

here is an example of my line

`main_hand=stromkar_the_warbreaker,id=128910,bonus_id=750,gem_id=143529/143524/137399/0,relic_id=3454:1472/3454:1477:3336/3418:1532:3337/0`

`gem_id=143529/143524/137399/0`
this is relics item id's, iron/blood/shadow/0 (don't ask me what is zero, it's just there)
so to place our relic in blood slot we need to change 143524 to 139254 (item id of our relic from wowhead)

`relic_id=3454:1472/3454:1477:3336/3418:1532:3337/0`
these are bonus id's of your relics, iron/blood/shadow/0 (again, dont touch the zero)
our new blood relic has bonus id 1507:1807 so we change 3454:1477:3336 to 1507:1807

this is what we get
`main_hand=stromkar_the_warbreaker,id=128910,bonus_id=750,gem_id=143529/139254/137399/0,relic_id=3454:1472/1507:1807/3418:1532:3337/0`
done.

# Step 6. Simulate.

![](http://i.imgur.com/qO8Ueje.png)

this is what we get

![](http://i.imgur.com/Ove2SAh.png)


Easy, now stop spamming discord with your stupid question.

