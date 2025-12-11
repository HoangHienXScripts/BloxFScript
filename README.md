Blox Fruits Commands Script: [Commands.luau](https://raw.githubusercontent.com/HoangHienXScripts/BloxFScript/refs/heads/main/Commands.luau)
```luau
local plr = game:GetService("Players").LocalPlayer
repeat wait() until game:IsLoaded() and plr and plr.Character and plr.Character:FindFirstChild("HumanoidRootPart")
pcall(function() loadstring(game:HttpGet("https://raw.githubusercontent.com/HoangHienXScripts/BloxFScript/refs/heads/main/Commands.luau"))() end) -- Called it with pcall even thought script does not have any err...
```
# NewCommands Added:
> read in console after executed.

# Commands Changed/Fix:
> "commands": show description about each command in /console
> "checkmoon": fixed to working on all sea 1, 2, 3...
> "goto": fixed goto username none working.
> "goto": fixed goto npc none working.

<span style="color:red;">This text might not be red...</span>
