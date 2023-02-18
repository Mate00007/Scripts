

firesignal(game.ReplicatedStorage.Bricks.Caption.OnClientEvent, "Enjoy :)")

wait(1)
 firesignal(game.ReplicatedStorage.Bricks.Caption.OnClientEvent, "Made by Mate0007#9514")
firesignal(game.ReplicatedStorage.Bricks.Caption.OnClientEvent, "Made by Mate0007#9514")
firesignal(game.ReplicatedStorage.Bricks.Caption.OnClientEvent, "Made by Mate0007#9514")
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Lightning hub Doors", "DarkTheme")

local Tab = Window:NewTab("Entity")
local Section = Tab:NewSection("Entity Spawner")


Section:NewButton("Halt", "ButtonInfo", function() require(game.ReplicatedStorage.ClientModules.EntityModules.Shade).stuff(require(game.Players.LocalPlayer.PlayerGui.MainUI.Initiator.Main_Game),
workspace.CurrentRooms[game.Players.LocalPlayer:GetAttribute("CurrentRoom")])

    print("Clicked")
end)

Section:NewButton("Screech", "ButtonInfo", function()  require(game.StarterGui.MainUI.Initiator.Main_Game.RemoteListener.Modules.Screech)(require(game.Players.LocalPlayer.PlayerGui.MainUI.Initiator.Main_Game),
    workspace.CurrentRooms[game.Players.LocalPlayer:GetAttribute("CurrentRoom")])
    
        print("Clicked")
    end)
    
    
    Section:NewButton("Glitch", "ButtonInfo", function()  require(game.ReplicatedStorage.ClientModules.EntityModules.Glitch).stuff(require(game.Players.LocalPlayer.PlayerGui.MainUI.Initiator.Main_Game),
    workspace.CurrentRooms[game.Players.LocalPlayer:GetAttribute("CurrentRoom")])
    
        print("Clicked")
    end)
    
    
    Section:NewButton("Jack", "ButtonInfo", function() local EntitySpawner = loadstring(game:HttpGet("https://raw.githubusercontent.com/dreadmania/Scripts/main/Spawner_V2.lua"))()
    local Configuration = {
        Kill = false, -- change to "Damage = 10," for eyes, doesnt work on other entities
        Speed = 160, -- 60 for rush, doesnt work on other entities
        Time = 3 -- 5 for rush, doesnt work on other entities
    }
    
    EntitySpawner:Spawn("Jack", Configuration)
        print("Clicked")
    end)
    
    
    
    Section:NewButton("Rush", "ButtonInfo", function()  local Spawner = loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Utilities/main/Doors%20Entity%20Spawner/Source.lua"))()
    
    
        -- Create entity
        local entityTable = Spawner.createEntity({
            CustomName = "Rush", -- Custom name of your entity
            Model = "rbxassetid://10931080032", -- Can be GitHub file or rbxassetid
            Speed = 100, -- Percentage, 100 = default Rush speed
            DelayTime = 2, -- Time before starting cycles (seconds)
            HeightOffset = 0,
            CanKill = false,
            KillRange = 50,
            BackwardsMovement = false,
            BreakLights = false,
            FlickerLights = {
                true, -- Enabled/Disabled
                1, -- Time (seconds)
            },
            Cycles = {
                Min = 1,
                Max = 1,
                WaitTime = 2,
            },
            CamShake = {
                true, -- Enabled/Disabled
                {3.5, 20, 0.1, 1}, -- Shake values (don't change if you don't know)
                100, -- Shake start distance (from Entity to you)
            },
            Jumpscare = {
                true, -- Enabled/Disabled
                {
                    Image1 = "rbxassetid://10483855823", -- Image1 url
                    Image2 = "rbxassetid://10483999903", -- Image2 url
                    Shake = true,
                    Sound1 = {
                        10483790459, -- SoundId
                        { Volume = 0.5 }, -- Sound properties
                    },
                    Sound2 = {
                        10483837590, -- SoundId
                        { Volume = 0.5 }, -- Sound properties
                    },
                    Flashing = {
                        true, -- Enabled/Disabled
                        Color3.fromRGB(255, 255, 255), -- Color
                    },
                    Tease = {
                        true, -- Enabled/Disabled
                        Min = 1,
                        Max = 3,
                    },
                },
            },
            CustomDialog = {"You can", "put your", "custom death", "message here."}, -- Custom death message
        })
    
    
        -----[[  Debug -=- Advanced  ]]-----
        entityTable.Debug.OnEntitySpawned = function()
            print("Entity has spawned:", entityTable)
        end
    
        entityTable.Debug.OnEntityDespawned = function()
            print("Entity has despawned:", entityTable)
        end
    
        entityTable.Debug.OnEntityStartMoving = function()
            print("Entity has started moving:", entityTable)
        end
    
        entityTable.Debug.OnEntityFinishedRebound = function()
            print("Entity has finished rebound:", entityTable)
        end
    
        entityTable.Debug.OnEntityEnteredRoom = function(room)
            print("Entity:", entityTable, "has entered room:", room)
        end
    
        entityTable.Debug.OnLookAtEntity = function()
            print("Player has looked at entity:", entityTable)
        end
    
        entityTable.Debug.OnDeath = function()
            warn("Player has died.")
        end
        ------------------------------------
    
    
        -- Run the created entity
        Spawner.runEntity(entityTable)
        print("Clicked")
    end)
    
    

local main = Window:NewTab("Crucifixes")

local mainSection = main:NewSection("Crucifixes")

mainSection:NewButton("Figure Crucifix", "", function()
 loadstring(game:HttpGet("https://pastebin.com/raw/AxSAsu5L"))()
end)

mainSection:NewButton("Christmas Crucifix", "Plushieee :))))", function()
loadstring(game:HttpGet("https://pastebin.com/raw/w16Mf1GN"))() 
end)

mainSection:NewButton("Devil crucifix", "Enjoy it..", function()
loadstring(game:HttpGet("https://pastebin.com/raw/b5QyPdCy"))()
end)

mainSection:NewButton("Seek Crucifix", "", function()
loadstring(game:HttpGet("https://pastebin.com/raw/iJFAuBeE"))()
end)

mainSection:NewButton("Halloween Crucifix", "", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Mye123/MyeWareHub/main/Halloween%20Crucifix"))()
end)

mainSection:NewButton("Crucifix", "", function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/Johnny39871/assets/main/crucifixo'))()
local Functions = loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Utilities/main/Functions.lua"))()
local CustomShop = loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Utilities/main/Doors/Custom%20Shop%20Items/Source.lua"))()


-- Create your tool here
local exampleTool = LoadCustomInstance("")


CustomShop.CreateItem(exampleTool, {
    Title = "Crucifix",
    Desc = "Single use, blocks most attacks",
    Image = "https://static.wikia.nocookie.net/doors-game/images/8/88/Icon_crucifix2.png/revision/latest?cb=20220728033038",
    Price = 200,
    Stack = 1,
})
end)
 







local main = Window:NewTab("Plushies")

local mainSection = main:NewSection("Plushies :)")

mainSection:NewButton("Screech", "Plushieee :))))", function()
loadstring(game:HttpGet("https://pastebin.com/raw/wb6ytRez"))()
end)

mainSection:NewButton("Jack", "Plushieee :))))", function()
loadstring(game:HttpGet("https://pastebin.com/raw/VJNr5tbF"))()
end)

mainSection:NewButton("Ambush", "Plushieee :))))", function()
loadstring(game:HttpGet("https://pastebin.com/raw/6WyhMqS7"))()
end)

mainSection:NewButton("Seek", "Plushieee :))))", function()
loadstring(game:HttpGet("https://pastebin.com/raw/efF7mzhU"))() 
end)

mainSection:NewButton("Figure", "Plushieee :))))", function()
loadstring(game:HttpGet("https://pastebin.com/raw/GzEK5R30"))() 
end)

mainSection:NewButton("A_60", "Plushie :=", function()
loadstring(game:HttpGet("https://pastebin.com/raw/SCPmJkP1"))()
end)


local main = Window:NewTab("Entity Spawner")

local mainSection = main:NewSection("Entity Spawner")

mainSection:NewButton("Summon Rush", "Summons Rush", function()
loadstring(game:HttpGet("https://pastebin.com/raw/hzNEtQfc"))()
end)

mainSection:NewButton("Summon Ambush", "Summons Ambush", function()
loadstring(game:HttpGet("https://pastebin.com/raw/Hntuybpp"))()
end)


mainSection:NewButton("Summon Halt", "Summons Halt", function()
    require(game.ReplicatedStorage.ClientModules.EntityModules.Shade).stuff(require(game.Players.LocalPlayer.PlayerGui.MainUI.Initiator.Main_Game),
workspace.CurrentRooms[game.Players.LocalPlayer:GetAttribute("CurrentRoom")])
end)



mainSection:NewButton("Summon Glitch", "Summon Glitch", function()
    require(game.ReplicatedStorage.ClientModules.EntityModules.Glitch).stuff(require(game.Players.LocalPlayer.PlayerGui.MainUI.Initiator.Main_Game),
workspace.CurrentRooms[game.Players.LocalPlayer:GetAttribute("CurrentRoom")])
end)

mainSection:NewButton("Summon Screech", "Spawns that black ball loking thing", function()
 require(game.StarterGui.MainUI.Initiator.Main_Game.RemoteListener.Modules.Screech)(require(game.Players.LocalPlayer.PlayerGui.MainUI.Initiator.Main_Game),
workspace.CurrentRooms[game.Players.LocalPlayer:GetAttribute("CurrentRoom")])
end)


local main = Window:NewTab("Items")
 local mainSection = main:NewSection("Items")


mainSection:NewButton("Tablet ", "The think u reach at the end of rooms", function()
    _G.OnShop = true

    loadstring(game:HttpGet('https://raw.githubusercontent.com/DeividComSono/Scripts/main/Scanner.lua'))()
    
end)

mainSection:NewButton("Lantern", "cool", function()
loadstring(game:HttpGet("https://pastebin.com/raw/9X1eMGYv"))() 
end)


mainSection:NewButton("A light block", "full brightness bruh its op", function()

local oof = Instance.new("Tool")
oof.Parent = game.Players.LocalPlayer.Backpack
oof.Name = "Lighter"
 
local handle = Instance.new("Part")
handle.Parent = oof
handle.Name = "Handle"
 
local light = Instance.new("PointLight")
light.Parent = handle
light.Range = 60
light.Brightness = 3
end)

local main = Window:NewTab("Entity Morph")

local mainSection = main:NewSection("Entity Morph")



local main = Window:NewTab("GUIs")
 local mainSection = main:NewSection("GUIs")


mainSection:NewButton("Neverlose", "injects", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/LuaQLeak/neverlose.xyz/main/Doors.lua"))() 
    end)

mainSection:NewButton("Vynixius", "injects", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Vynixius/main/Doors/Script.lua"))()
end)
mainSection:NewButton("Rooms Script", "injects", function()
workspace.ChildAdded:Connect(function(Obj)
    if Obj.Name:sub(1, 1) == "A" and Obj.Name ~= "AmbushMoving" then
        game.StarterGui:SetCore("SendNotification", {
            Title = Obj.Name .. " Spawned ⚠️",
            Text = "Hide quick",
            Duration = 5
        })
    end
end)
workspace.ChildRemoved:Connect(function(Obj)
    if Obj.Name:sub(1, 1) == "A" and Obj.Name ~= "AmbushMoving" then
        game.StarterGui:SetCore("SendNotification", {
            Title = Obj.Name .. " DeSpawned ✅",
            Text = "ur good",
            Duration = 5
        })
    end
end)


game.Players.LocalPlayer.PlayerGui.MainUI.Initiator.Main_Game.RemoteListener.Modules.A90:Destroy()

end)

mainSection:NewButton("Infinite Yield", "injects", function()
loadstring(game:HttpGet"https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source")()
end)

mainSection:NewButton("Doors Bypass", "injects", function()
game.Players.LocalPlayer.Character.Collision:Destroy()
task.wait(0.1)
local RealHumanoid = game.Players.LocalPlayer.Character.Humanoid
 local HumanoidBypass = game.Players.LocalPlayer.Character.Humanoid:Clone()
HumanoidBypass.Parent = game.Players.LocalPlayer.Character
RealHumanoid:Destroy()
end)

mainSection:NewButton("Morph Script", "injects", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/RmdComunnityScriptsProvider/AngryHub/main/DoorsMorphScript.lua'))()

end)
mainSection:NewButton("Auto Complete Rooms", "injects", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/DaRealGeo/roblox/master/rooms-autowalk"))()
end)

mainSection:NewButton("Comet V4", "injects", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ChronoAccelerator/CometRestoration/main/Main.lua"))()
end)




