game.StarterGui:SetCore("SendNotification", {
    Title = "Speed638"; 
    Text = "Successfully Executed!"; 
    Icon = "http://www.roblox.com/asset/?id=9680636205"; 
    Duration = 5;
    Callback = bindableFunction;
    Button1 = "Like";  
    Button2 = "Dislike";
})

wait(2)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(701, 196, -211)
wait(2)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1187, 379, 110)
wait(2)
loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\40\39\104\116\116\112\115\58\47\47\103\105\115\116\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\109\101\111\122\111\110\101\89\84\47\98\102\48\51\55\100\102\102\57\102\48\97\55\48\48\49\55\51\48\52\100\100\100\54\55\102\100\99\100\51\55\48\47\114\97\119\47\101\49\52\101\55\52\102\52\50\53\98\48\54\48\100\102\53\50\51\51\52\51\99\102\51\48\98\55\56\55\48\55\52\101\98\51\99\53\100\50\47\97\114\99\101\117\115\37\50\53\50\48\120\37\50\53\50\48\102\108\121\37\50\53\50\48\50\37\50\53\50\48\111\98\102\108\117\99\97\116\111\114\39\41\44\116\114\117\101\41\41\40\41\10\10")()

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1495, 338, -699)
wait(3)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1021, 295, -1771)


local vermLib = loadstring(game:HttpGet("https://pastebin.com/raw/ZHTSgiQF"))()

local window = vermLib:CreateWindow()
local main = window:CreateTab("main", "Bosses", "") -- framename, threadname, author
local Mobs = window:CreateTab("Mobs", "mobs", "")
local Ore = window:CreateTab("Ore", "Ore", "") -- framename, threadname, author
local Farming = window:CreateTab("Farming", "Farming", "") -- framename, threadname, author
local SpiritFarm = window:CreateTab("SpiritFarm", "SpiritFarm", "") -- framename, threadname, author
local Teleports = window:CreateTab("Teleports", "Teleports", "") -- framename, threadname, author
local Mods = window:CreateTab("Mods", "Mods", "") -- framename, threadname, author
local BossBookSpells = window:CreateTab("BossBookSpells", "BossBookSpells", "") -- framename, threadname, author

main:CreateToggle("Slimeking", function(state) -- togglename, callback
getgenv().autofarm = state
while true do
if not getgenv().autofarm then return end
while wait(0.3) do
    function teleportto(placeCFrame)
    local plr = game.Players.LocalPlayer;
    if plr.Character then
        plr.Character.HumanoidRootPart.CFrame = placeCFrame + Vector3.new(0,-8,0)
         end
end

teleportto(game:GetService("Workspace").WildernessIsland.Entities.slimeKing.HumanoidRootPart.CFrame)

end
end
end)

main:CreateToggle("Kor", function(state) -- togglename, callback
getgenv().autofarm = state
while true do
if not getgenv().autofarm then return end
wait(0.1)
    function teleportto(placeCFrame)
    local plr = game.Players.LocalPlayer;
    if plr.Character then
        plr.Character.HumanoidRootPart.CFrame = placeCFrame + Vector3.new(0,-8,0)
         end
end

teleportto(game:GetService("Workspace").WildernessIsland.Entities.golem.HumanoidRootPart.CFrame)
    end
end)

main:CreateToggle("Wizard Boss", function(state) -- togglename, callback
getgenv().autofarm = state
while true do
if not getgenv().autofarm then return end
wait(0.1)
    function teleportto(placeCFrame)
    local plr = game.Players.LocalPlayer;
    if plr.Character then
        plr.Character.HumanoidRootPart.CFrame = placeCFrame + Vector3.new(0,-8,0)
         end
end

function teleportto(placeCFrame)
    local plr = game.Players.LocalPlayer;
    if plr.Character then
        plr.Character.HumanoidRootPart.CFrame = placeCFrame + Vector3.new(0,-13,0)
         end
end

teleportto(game:GetService("Workspace").WildernessIsland.Entities.wizardBoss.HumanoidRootPart.CFrame)
    end
end)
main:CreateToggle("Bhaa", function(state) -- togglename, callback
getgenv().autofarm = state
while true do
if not getgenv().autofarm then return end
wait(0.1)
    function teleportto(placeCFrame)
    local plr = game.Players.LocalPlayer;
    if plr.Character then
        plr.Character.HumanoidRootPart.CFrame = placeCFrame + Vector3.new(0,-8,0)
         end
end

teleportto(game:GetService("Workspace").WildernessIsland.Entities.desertBoss.HumanoidRootPart.CFrame)
    end
end)
main:CreateToggle("Dragon", function(state) -- togglename, callback
getgenv().autofarm = state
while true do
if not getgenv().autofarm then return end
wait(0.2)
    function teleportto(placeCFrame)
    local plr = game.Players.LocalPlayer;
    if plr.Character then
        plr.Character.HumanoidRootPart.CFrame = placeCFrame + Vector3.new(0,-17,0)
         end
end

teleportto(game:GetService("Workspace").WildernessIsland.Entities.magmaDragon.HumanoidRootPart.CFrame)
end
    print(bool)
-- bool is true or false depending on the state of the toggle
end)

Mobs:CreateToggle("Slime", function(state) -- togglename, callback
getgenv().autofarm = state
while true do
if not getgenv().autofarm then return end
wait(0.1)
    function teleportto(placeCFrame)
    local plr = game.Players.LocalPlayer;
    if plr.Character then
        plr.Character.HumanoidRootPart.CFrame = placeCFrame + Vector3.new(0,-8,0)
         end
end

teleportto(game:GetService("Workspace").WildernessIsland.Entities.slime.HumanoidRootPart.CFrame)
    end
end)
Mobs:CreateToggle("Buffalkor", function(state) -- togglename, callback
getgenv().autofarm = state
while true do
if not getgenv().autofarm then return end
wait(0.2)
    function teleportto(placeCFrame)
    local plr = game.Players.LocalPlayer;
    if plr.Character then
        plr.Character.HumanoidRootPart.CFrame = placeCFrame + Vector3.new(0,-10,0)
         end
end

teleportto(game:GetService("Workspace").WildernessIsland.Entities.buffalkor.HumanoidRootPart.CFrame)
end
print(bool)
end)
Mobs:CreateToggle("Lizards", function(state) -- togglename, callback
getgenv().autofarm = state
while true do
if not getgenv().autofarm then return end
wait(0.1)
    function teleportto(placeCFrame)
    local plr = game.Players.LocalPlayer;
    if plr.Character then
        plr.Character.HumanoidRootPart.CFrame = placeCFrame + Vector3.new(0,-8,0)
         end
end

function teleportto(placeCFrame)
    local plr = game.Players.LocalPlayer;
    if plr.Character then
        plr.Character.HumanoidRootPart.CFrame = placeCFrame + Vector3.new(0,-13,0)
         end
end

teleportto(game:GetService("Workspace").WildernessIsland.Entities.wizardLizard.HumanoidRootPart.CFrame)
    end
    end)
Mobs:CreateToggle("Skorps", function(state) -- togglename, callback
getgenv().autofarm = state
while true do
if not getgenv().autofarm then return end
wait(0.1)
function teleportto(placeCFrame)
    local plr = game.Players.LocalPlayer;
    if plr.Character then
        plr.Character.HumanoidRootPart.CFrame = placeCFrame + Vector3.new(0,-13,0)
         end
end

teleportto(game:GetService("Workspace").WildernessIsland.Entities.skorpGold.HumanoidRootPart.CFrame)
    end
    end)
Mobs:CreateToggle("Blobs", function(state) -- togglename, callback
getgenv().autofarm = state
while true do
if not getgenv().autofarm then return end
    function teleportto(placeCFrame)
    local plr = game.Players.LocalPlayer;
    if plr.Character then
        plr.Character.HumanoidRootPart.CFrame = placeCFrame + Vector3.new(0,4,0)
         end
end

teleportto(game:GetService("Workspace").WildernessIsland.Entities.magmaBlob.HumanoidRootPart.CFrame)
end
wait(0.2)
-- bool is true or false depending on the state of the toggle
end)
 Orelist = {"Iron","Electrite","Stone","Coal","Gold","Andesite","Clay","Diamond","Snow","DiamondEnchanted"}

local dropdown = Ore:CreateDropdown("Ore", Orelist, function(CurrentOption) -- dropdownname, list, callback
Ore = nil
Ore = CurrentOption
end)

dropdown:Refresh(Orelist) -- refresh dropdown with new options
Ore:CreateToggle("Farm Ore", function(state) -- togglename, callback
getgenv().autofarm = state
while true do
if not getgenv().autofarm then return end
local rock = game:GetService("Workspace").WildernessBlocks:FindFirstChild("rock"..Ore)
if rock ~= nil then
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = rock.CFrame + Vector3.new(0,-7,0)
local A_1 = 
{
	["player_tracking_category"] = "join_from_web",
	["part"] = rock["1"],
	["block"] = rock,
	["norm"] = Vector3.new(0,0,0),
	["pos"] = rock.Position
}
local Event = game:GetService("ReplicatedStorage")["rbxts_include"]["node_modules"].net.out["_NetManaged"]["CLIENT_BLOCK_HIT_REQUEST"]
Event:InvokeServer(A_1)
end	
wait()
end    
end)
Farmlist = {"berry","blueberry","lol","lol","none"}

local dropdown = Farming:CreateDropdown("Choose To Farm", Farmlist, function(CurrentOption) -- dropdownname, list, callback
Farming = nil
Farming = CurrentOption
end)

dropdown:Refresh(Farmlist) -- refresh dropdown with new options
Farming:CreateToggle("Start Farm", function(state) -- togglename, callback
getgenv().autofarm = state
while true do
if not getgenv().autofarm then return end
local Bush = game:GetService("Workspace").WildernessBlocks:FindFirstChild("Bush"..harvest)
if Bush ~= nil then
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Bush.CFrame + Vector3.new(0,-7,0)
local args = {
    [1] = {
        ["player"] = game:GetService("Players").LocalPlayer,
        ["player_tracking_category"] = "join_from_web",
        ["model"] = workspace.Islands:FindFirstChild("54ff3df8-f0de-4b9e-b6b3-152df961fe16-island").Blocks.Bush
    }
}

game:GetService("ReplicatedStorage").rbxts_include.node_modules.net.out._NetManaged.CLIENT_HARVEST_CROP_REQUEST:InvokeServer(unpack(args))
end
wait()
end    
end)
Spiritlist = {"spirit"}

local dropdown = SpiritFarm:CreateDropdown("Choose Spirit", Spiritlist, function(CurrentOption) -- dropdownname, list, callback
Spirit = nil
Spirit = CurrentOption
end)

dropdown:Refresh(Spiritlist) -- refresh dropdown with new options
SpiritFarm:CreateToggle("Farm Spirit", function(state) -- togglename, callback
getgenv().autofarm = state
while true do
if not getgenv().autofarm then return end
local spirit = game:GetService("Workspace").WildernessIsland.Entities.spirit.Bigspirit1
if spirit ~= nil then
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = spirit.CFrame + Vector3.new(0,2,0)
function getNil(name,class) for _,v in pairs(getnilinstances())do if v.ClassName==class and v.Name==name then return v;end end end

local args = {
    [1] = {
        ["entity"] = getNil("spirit", "Model")
    }
}

game:GetService("ReplicatedStorage").rbxts_include.node_modules.net.out._NetManaged.CLIENT_CATCH_INSECT:InvokeServer(unpack(args))
end	
wait()
end    
end)


Teleports:CreateButton("Slime Summon", function()  -- buttonname, callback
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(726, 167, 140)
end)
Teleports:CreateButton("Buffalkor Island", function()  -- buttonname, callback
    function teleportto(placeCFrame)
    local plr = game.Players.LocalPlayer;
    if plr.Character then
        plr.Character.HumanoidRootPart.CFrame = placeCFrame + Vector3.new(0,2,0)
         end
end

teleportto(game:GetService("Workspace").SpawnLocations.buffalkor_spawn.CFrame)
end)
Teleports:CreateButton("Diamond Mine Island", function()  -- buttonname, callback
function teleportto(placeCFrame)
    local plr = game.Players.LocalPlayer;
    if plr.Character then
        plr.Character.HumanoidRootPart.CFrame = placeCFrame + Vector3.new(0,2,0)
         end
end

teleportto(game:GetService("Workspace").SpawnLocations.diamond_mine_spawn.CFrame)
    end)
Teleports:CreateButton("Kor Summon", function()  -- buttonname, callback
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2867, 285, 1177)
end)
Teleports:CreateButton("Wizard Island", function()  -- buttonname, callback
    function teleportto(placeCFrame)
    local plr = game.Players.LocalPlayer;
    if plr.Character then
        plr.Character.HumanoidRootPart.CFrame = placeCFrame + Vector3.new(0,2,0)
         end
end

Teleportto(game:GetService("Workspace").SpawnLocations.wizard_spawn.CFrame)
    end)
Teleports:CreateButton("Wizard Summon", function()  -- buttonname, callback
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1805, 412, -990)
end)
Teleports:CreateButton("Desert Island", function()  -- buttonname, callback
    function teleportto(placeCFrame)
    local plr = game.Players.LocalPlayer;
    if plr.Character then
        plr.Character.HumanoidRootPart.CFrame = placeCFrame + Vector3.new(0,2,0)
         end
end

teleportto(game:GetService("Workspace").SpawnLocations.desert_spawn.CFrame)
    end)
Teleports:CreateButton("Bhaa Summon", function()  -- buttonname, callback
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(644, 309, -2075)
end)
Teleports:CreateButton("Underworld Island", function()  -- buttonname, callback
function teleportto(placeCFrame)
    local plr = game.Players.LocalPlayer;
    if plr.Character then
        plr.Character.HumanoidRootPart.CFrame = placeCFrame + Vector3.new(0,2,0)
         end
end

teleportto(game:GetService("Workspace").SpawnLocations.underworld_spawn.CFrame)
    end)
Teleports:CreateButton("Dragon Summon", function()  -- buttonname, callback
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-9196, 407, -1402)
end)

Mods:CreateToggle("Esp", function(state)  -- buttonname, callback
getgenv().autofarm = state
if not getgenv().autofarm then return end
local esp_settings = { ---- table for esp settings 
    textsize = 20,
    colour = 255,255,255
}
 
local gui = Instance.new("BillboardGui")
local esp = Instance.new("TextLabel",gui) ---- new instances to make the billboard gui and the textlabel
 
 
 
gui.Name = "Cracked esp"; ---- properties of the esp
gui.ResetOnSpawn = false
gui.AlwaysOnTop = true;
gui.LightInfluence = 0;
gui.Size = UDim2.new(1.75, 0, 1.75, 0);
esp.BackgroundColor3 = Color3.fromRGB(255, 255, 255);
esp.Text = ""
esp.Size = UDim2.new(0.0001, 0.00001, 0.0001, 0.00001);
esp.BorderSizePixel = 4;
esp.BorderColor3 = Color3.new(esp_settings.colour)
esp.BorderSizePixel = 0
esp.Font = "GothamSemibold"
esp.TextSize = esp_settings.textsize
esp.TextColor3 = Color3.fromRGB(esp_settings.colour) -- text colour

game:GetService("RunService").RenderStepped:Connect(function() ---- loops faster than a while loop :)
    for i,v in pairs (game:GetService("Players"):GetPlayers()) do
        if v ~= game:GetService("Players").LocalPlayer and v.Character.Head:FindFirstChild("Cracked esp")==nil  then -- craeting checks for team check, local player etc
            esp.Text = ""..v.Name..""
            gui:Clone().Parent = v.Character.Head
    end
end
end)
end)
Mods:CreateToggle("Speed", function(state)  -- buttonname, callback
getgenv().autofarm = state
while true do 
    wait()
if not getgenv().autofarm then return end
game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 60
end
end)

Mods:CreateToggle("Infinite jump", function(state)  -- buttonname, callback
getgenv().autofarm = state
if not getgenv().autofarm then return 
    end
    game:GetService("UserInputService").JumpRequest:connect(function() do
        game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")
    
end
end)
end)

Mods:CreateToggle("Kill Aura", function(state)  -- buttonname, callback
getgenv().autofarm = state
if not getgenv().autofarm then return end

while true do wait()

game:GetService("Players").LocalPlayer.Character.Humanoid:EquipTool(game:GetService("Players").LocalPlayer.Backpack.swordWood)

game:GetService("ReplicatedStorage").Remotes.Functions["SWING_SWORD"]=aZ.Parent.MouseButton1Click:Connect(function()


    
end)

end
end)



Mods:CreateToggle("Auto Sell", function(state)  -- buttonname, callback
getgenv().autofarm = state
if not getgenv().autofarm then return end
while wait() do
local args = {
    [1] = {
        ["merchant"] = "cropSell",
        ["offerId"] = 1,
        ["amount"] = all
    }
}

game:GetService("ReplicatedStorage").rbxts_include.node_modules.net.out._NetManaged.CLIENT_MERCHANT_ORDER_REQUEST:InvokeServer(unpack(args))
wait()
local args = {
    [1] = {
        ["merchant"] = "cropSell",
        ["offerId"] = 50,
        ["amount"] = all
    }
}

game:GetService("ReplicatedStorage").rbxts_include.node_modules.net.out._NetManaged.CLIENT_MERCHANT_ORDER_REQUEST:InvokeServer(unpack(args))
wait()
-- Script generated by R2Sv2
-- R2Sv2 developed by Luckyxero
 
-- Script generated by R2Sv2
-- R2Sv2 developed by Luckyxero
 
local A_1 = 
{
	["merchant"] = "cropSell", 
	["offerId"] = 2, 
	["amount"] = all
}
local Event = game:GetService("ReplicatedStorage")["rbxts_include"]["node_modules"].net.out["_NetManaged"]["CLIENT_MERCHANT_ORDER_REQUEST"]
Event:InvokeServer(A_1)
wait()
-- Script generated by R2Sv2
-- R2Sv2 developed by Luckyxero
 
local A_1 = 
{
	["merchant"] = "cropSell", 
	["offerId"] = 3, 
	["amount"] = all
}
local Event = game:GetService("ReplicatedStorage")["rbxts_include"]["node_modules"].net.out["_NetManaged"]["CLIENT_MERCHANT_ORDER_REQUEST"]
Event:InvokeServer(A_1)
wait()
local A_1 = 
{
	["merchant"] = "cropSell", 
	["offerId"] = 6, 
	["amount"] = all
}
local Event = game:GetService("ReplicatedStorage")["rbxts_include"]["node_modules"].net.out["_NetManaged"]["CLIENT_MERCHANT_ORDER_REQUEST"]
Event:InvokeServer(A_1)
wait()
local A_1 = 
{
	["merchant"] = "cropSell", 
	["offerId"] = 7, 
	["amount"] = all
}
local Event = game:GetService("ReplicatedStorage")["rbxts_include"]["node_modules"].net.out["_NetManaged"]["CLIENT_MERCHANT_ORDER_REQUEST"]
Event:InvokeServer(A_1)
wait()
local A_1 = 
{
	["merchant"] = "cropSell", 
	["offerId"] = 8, 
	["amount"] = all
}
local Event = game:GetService("ReplicatedStorage")["rbxts_include"]["node_modules"].net.out["_NetManaged"]["CLIENT_MERCHANT_ORDER_REQUEST"]
Event:InvokeServer(A_1)
wait()
local A_1 = 
{
	["merchant"] = "cropSell", 
	["offerId"] = 9, 
	["amount"] = all
}
local Event = game:GetService("ReplicatedStorage")["rbxts_include"]["node_modules"].net.out["_NetManaged"]["CLIENT_MERCHANT_ORDER_REQUEST"]
Event:InvokeServer(A_1)
wait()
local A_1 = 
{
	["merchant"] = "cropSell", 
	["offerId"] = 10, 
	["amount"] = all
}
local Event = game:GetService("ReplicatedStorage")["rbxts_include"]["node_modules"].net.out["_NetManaged"]["CLIENT_MERCHANT_ORDER_REQUEST"]
Event:InvokeServer(A_1)
wait()
end
end)

BossBookSpells:CreateToggle("Slime SpellBook Cast", function(state)  -- buttonname, callback
getgenv().AutoCast = state
while true do
if not getgenv().AutoCast then return end
local args = {
    [1] = {
        ["direction"] = CFrame.new(Vector3.new(682.844970703125, 177.4847412109375, 276.4657897949219), Vector3.new(0.06836026906967163, -0.5933000445365906, -0.8020734786987305)),
        ["charge"] = 1.5785262459202818,
        ["spellType"] = "spell_fireball",
        ["cameraCFrame"] = CFrame.new(Vector3.new(682.844970703125, 177.4847412109375, 276.4657897949219), Vector3.new(0.06836026906967163, -0.5933000445365906, -0.8020734786987305)),
        ["firstPerson"] = true,
        ["spellCastType"] = 1,
        ["shooter"] = game:GetService("Players").LocalPlayer
    }
}

game:GetService("ReplicatedStorage").rbxts_include.node_modules.net.out._NetManaged.CLIENT_CAST_SPELL:InvokeServer(unpack(args))

wait(0.001)
    
-- bool is true or false depending on the state of the toggle
end
end)
BossBookSpells:CreateToggle("Kor SpellBook Cast", function(state)  -- buttonname, callback
getgenv().AutoCast = state
while true do
if not getgenv().AutoCast then return end
local args = {
    [1] = {
        ["direction"] = CFrame.new(Vector3.new(2802.1630859375, 286.34698486328125, 1204.4609375)),
        ["charge"] = 4.3624337848864103,
        ["spellType"] = "spell_fireball",
        ["cameraCFrame"] = CFrame.new(Vector3.new(2802.1630859375, 286.34698486328125, 1204.4609375), Vector3.new(-0.8809597492218018, -0.08948773890733719, -0.46465256810188293)),
        ["firstPerson"] = true,
        ["spellCastType"] = 1,
        ["shooter"] = game:GetService("Players").LocalPlayer
    }
}

game:GetService("ReplicatedStorage").rbxts_include.node_modules.net.out._NetManaged.CLIENT_CAST_SPELL:InvokeServer(unpack(args))

wait(0.001)
    
-- bool is false or true depending on the state of the toggle
end
end)
BossBookSpells:CreateToggle("Bhaa SpellBook Cast", function(state)  -- buttonname, callback
getgenv().AutoCast = state
while true do
if not getgenv().AutoCast then return end
local args = {
    [1] = {
        ["direction"] = CFrame.new(Vector3.new(610.9420166015625, 310.787841796875, -2179.197509765625), Vector3.new(-0.11049311608076096, -0.4081510901451111, -0.906203031539917)),
        ["charge"] = 1.0692358016967773,
        ["spellType"] = "spell_fireball",
        ["cameraCFrame"] = CFrame.new(Vector3.new(613.7052001953125, 319.12811279296875, -2164.867431640625), Vector3.new(-0.17302609980106354, -0.4221571385860443, -0.8898568749427795)),
        ["firstPerson"] = true,
        ["spellCastType"] = 1,
        ["shooter"] = game:GetService("Players").LocalPlayer
    }
}

game:GetService("ReplicatedStorage").rbxts_include.node_modules.net.out._NetManaged.CLIENT_CAST_SPELL:InvokeServer(unpack(args))

wait(0.001)
    
-- bool is true or false depending on the state of the toggle
end
end)
BossBookSpells:CreateToggle("Wizard SpellBook Cast", function(state)  -- buttonname, callback
getgenv().AutoCast = state
while true do
if not getgenv().AutoCast then return end
local args = {
    [1] = {
        ["direction"] = CFrame.new(Vector3.new(1829.3541259765625, 416.5289001464844, -1076.020751953125), Vector3.new(-0.4577021598815918, -0.2294384390115738, -0.8589916825294495)),
        ["charge"] = 1.5785262459202818,
        ["spellType"] = "spell_fireball",
        ["cameraCFrame"] = CFrame.new(Vector3.new(1840.3529052734375, 423.27947998046875, -1058.1190185546875), Vector3.new(-0.5082239508628845, -0.24489010870456696, -0.8256738781929016)),
        ["firstPerson"] = true,
        ["spellCastType"] = 1,
        ["shooter"] = game:GetService("Players").LocalPlayer
    }
}

game:GetService("ReplicatedStorage").rbxts_include.node_modules.net.out._NetManaged.CLIENT_CAST_SPELL:InvokeServer(unpack(args))

wait(0.001)
    
-- bool is true or false depending on the state of the toggle
end
end)
game.StarterGui:SetCore("SendNotification", {
    Title = "Speed638"; 
    Text = "Successfully Loaded!"; 
    Icon = "http://www.roblox.com/asset/?id=9680636205"; 
    Duration = 5;
    Callback = bindableFunction;
    Button1 = "Like";  
    Button2 = "Dislike";
})
