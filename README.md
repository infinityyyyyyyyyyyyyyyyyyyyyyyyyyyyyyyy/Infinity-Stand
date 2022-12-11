# Infinity Stand

https://github.com/ic3w0lf22/Roblox-Account-Manager - For Multiple Roblox Instances


Execute On Stand Account:

```lua
getgenv().Settings =  {
    --// ! Main ! \\--
    ['Owner'] = 'OWNERUSERNAMEHERE', -- Username Of Owner
    ['Position'] = 'Back', -- Position Of Stand [Back! / Left! / Right!]
    ['Attack'] = 'Heavy!', -- Heavy = Super Punch Light = Spam Punch [Heavy! / Light!]
    ['CrewID'] = 'CREWIDHERE', -- Must Be In A Group For It To Work 
    ['SynapseMode'] = 'Off', -- [On / Off] [Makes Stand Less Buggy] Turn On If On Synapse X
    ['StandMode'] = 'Star Platinum', -- [Star Platinum / Cream / D4C / CMOON] Stand Sounds And Modes

    --// ! Misc ! \\--
    ['FPSCAP'] = '60', -- Limit FPS For Better FPS On Main Account (MAXED IS 60, SUGGEST 30 FPS ON STANDS)
    ['Msg'] = 'Yare Yare Daze..', -- [e/msg]
    ['LowGraphics'] = "On", -- [On/Off] Low Graphics For More FPS
    ['NoFace'] = "On", -- [On/Off] No Face On Your Stand

    --// ! Sounds ! \\--
    --\\ MUST HAVE BOOMBOX //--
    ['Sounds'] = "Off", -- [On/Off] Sounds When You Use Some Commands Like Mimic! And Evolve!
    ['SummonMusicID'] = 'Default', -- Enter A Sound ID Put [Default] If You Would Like The Default Sound
    ['SummonMusic'] = "Off", -- [On/Off]
    ['VanishAppearSound'] = "Off", -- [On/Off]
    ['CustomSong'] = "SONGIDHERE" -- Enter A Song ID And Say "Song!"
}

loadstring(game:HttpGet("https://raw.githubusercontent.com/infinityyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyy/Infinity-Stand/main/Infinity%20Stand"))()
```


Execute On Main Account:

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/infinityyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyy/Infinity-Stand/main/Infinity%20Stand%20GUI"))()
```
