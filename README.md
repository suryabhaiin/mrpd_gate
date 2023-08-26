# Image Peview

<img src="https://media.discordapp.net/attachments/977925336882876437/1144983653655523398/image.png?width=1133&height=671"/>
<br>



# Remove Default Gabz Entry gate poles

```Lua

CreateThread(function()
    while true do
        local ent = GetClosestObjectOfType(410.0258, -1020.157, 28.36596, 5.0, -1868050792, false, false, false)
        SetEntityCoords(ent, 410.0258, -1020.157, 0.36596)
        local ent1 = GetClosestObjectOfType(410.0258, -1028.319, 28.40051, 5.0, -1635161509, false, false, false)
        SetEntityCoords(ent1, 410.0258, -1028.319, 0.40051)
        Wait(200)
    end
end)

```

# Add in qb-doorlock MRPD config file

```Lua

-- mrpdggate1 created by Surya Bhai
Config.DoorList['mrpdggate-mrpdggate1'] = {
    distance = 5,
    doorLabel = 'mrpdggate1',
    locked = true,
    doorRate = 1.0,
    authorizedJobs = { ['police'] = 0 },
    fixText = false,
    objYaw = 90.000022888184,
    doorType = 'sliding',
    objCoords = vec3(409.180389, -1017.160645, 28.600508),
    objName = -768779561,
}

-- mrpdggate2 created by Surya Bhai
Config.DoorList['mrpdggate-mrpdggate2'] = {
    distance = 5,
    doorLabel = 'mrpdggate2',
    locked = true,
    doorRate = 1.0,
    authorizedJobs = { ['police'] = 0 },
    fixText = false,
    objYaw = 270.0,
    doorType = 'sliding',
    objCoords = vec3(409.296326, -1031.273926, 28.601299),
    objName = -768779561,
}
```
