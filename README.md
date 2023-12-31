# Simonfas Radargun
# Radargun UI Remake for FiveM [Standalone]

[EN]

This is a UI remake of TerbSEC's radar gun / laser gun. 

Original Post: https://github.com/TerbSEC/Radargun

I have corrected it so that the numbers are below the words.

Press Y to open

Press E to freeze Measurement

You can change this in the Config.lua :)

 ```lua
cfg = {}

cfg.menuopen = 246 -- BUTTON TO OPEN MENU (https://docs.fivem.net/game-references/controls/)
cfg.bottomfreeze = 38 -- FREEZE (https://docs.fivem.net/game-references/controls/)
cfg.metric = false --// IF METRIC = FALSE THEN IT WILL SHOW AS KM/H, IF METRIC = TRUE, THEN IT WILL CHANGE TO MPH
cfg.radargun = "WEAPON_VINTAGEPISTOL"
```

--------------------

[DA]

Dette er et UI remake af TerbSEC's radar gun / laser gun. 

Originalt Post: https://github.com/TerbSEC/Radargun

Jeg har rettet i det så talene står under ordene.

Hvis du vil have radaren på dansk, så gå ind i mappen html og find derefter en fil ved navn "-Radargun.png". Slet "-" i navnet og slet den anden Radargun.png. Derefter genstart scriptet.

Tryk Y for at åbne

Tryk E for at fryse farten

Du kan ændre det i Config.lua

 ```lua
cfg = {}

cfg.menuopen = 246 -- KANPPEN FOR AT ÅBNE MENU'EN (https://docs.fivem.net/game-references/controls/)
cfg.bottomfreeze = 38 -- FRYS (https://docs.fivem.net/game-references/controls/)
cfg.metric = false --// HVIS cfg.metric = false SÅ VIL DEN VISE KM/T, HVIS cfg.metric = true, SÅ VIL DEN VISE MPH
cfg.radargun = "WEAPON_VINTAGEPISTOL" -- HVILKEN PISTOL MAN VIL BRUGE (https://wiki.rage.mp/index.php?title=Weapons)
```
