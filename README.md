Blox Fruits Commands Script: [Commands.luau](https://raw.githubusercontent.com/HoangHienXScripts/BloxFScript/refs/heads/main/Commands.luau)
```luau
local plr = game:GetService("Players").LocalPlayer
repeat wait() until game:IsLoaded() and plr and plr.Character and plr.Character:FindFirstChild("HumanoidRootPart")
pcall(function() loadstring(game:HttpGet("https://raw.githubusercontent.com/HoangHienXScripts/BloxFScript/refs/heads/main/Commands.luau"))() end) -- Called it with pcall even thought script does not have any err...
```
# NewCommands Added:
> ..., old i won't write. (nil)
> "checkmoon": displaying a small GUI appearance on top left of the screen, show current moon state! (23:30-14/11/2025)
> "collectberries": get berries existing anywhere on the map, work for both sea 1, 2 and 3! (02:44-2/12/2025)

# Commands Changed/Fix:
> "commands": show description about each command in /console
> "checkmoon": fixed to working on all sea 1, 2, 3...
> "goto <player>": fixed!
