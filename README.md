# tes3mp-disable-assassins

If you are also running deathdrop.lua, replace the 

deathDrop.OnObjectSpawn(pid, cellDescription) 

with:

disableAssassins.OnObjectSpawn(pid, cellDescription)

inside server.lua
