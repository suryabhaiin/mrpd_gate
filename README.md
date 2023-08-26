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
    doorType = 'sliding',
    authorizedJobs = { ['police'] = 0 },
    objName = -768779561,
    fixText = false,
    objYaw = 90.000022888184,
    distance = 5,
    objCoords = vec3(408.9983, -1024.17957, 28.4454632),
    doorLabel = 'mrpdggate1',
    doorRate = 1.0,
    locked = true,
}

-- mrpdggate2 created by Surya Bhai
Config.DoorList['mrpdggate-mrpdggate2'] = {
    doorType = 'sliding',
    authorizedJobs = { ['police'] = 0 },
    objName = -768779561,
    fixText = false,
    objYaw = 270.0,
    distance = 5,
    objCoords = vec3(409.484467, -1024.80493, 28.6533852),
    doorLabel = 'mrpdggate2',
    doorRate = 1.0,
    locked = true,
}
```
