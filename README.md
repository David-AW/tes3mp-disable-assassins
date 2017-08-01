# tes3mp-disable-assassins

If you are **ALSO** running deathdrop.lua, replace the 

`deathDrop.OnObjectSpawn(pid, cellDescription)`

with:

`disableAssassins.OnObjectSpawn(pid, cellDescription)`

inside server.lua
