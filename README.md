# Infinity Stand

Execute On Stand Account:

```lua
getgenv().Settings =  {
    --// !Main! \\--
    ['Owner'] = 'OWNERUSERNAMEHERE', -- Username Of Owner
    ['Position'] = 'Back', -- Position Of Stand [Back! / Left! / Right!]
    ['Attack'] = 'Heavy!', -- Heavy = Super Punch Light = Spam Punch [Heavy! / Light!]
    ['CrewID'] = 'CREWIDHERE', -- Must Be In Group For It To Work 
    ['SynapseMode'] = 'Off', -- [On / Off] Synapse X Only [Makes The Stand Less Buggy!]
    ['StandMode'] = 'Star Platinum', -- [Star Platinum / Cream / D4C / CMOON] Stand Sounds And Modes

    --// ! Misc ! \\--
    ['FPSCAP'] = '60', -- This is so your main account gets the most fps (MAXED IS 60, SUGGEST 30 FPS ON STANDS)
    ['Msg'] = 'Yare Yare Daze..', -- When you say /e msg it makes all the alts say that message
    ['LowGraphics'] = "On", -- [On/Off] Turns graphics down so your stand doesnt lag too much
    ['NoFace'] = "On", -- [On/Off] For A Better Look On Your Stand

    --//    ! Sounds !     \\--
    --\\ MUST HAVE BOOMBOX //--
    ['Sounds'] = "Off", -- [On/Off] Sounds when you use some commands like Mimic! Evolve! etc
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
