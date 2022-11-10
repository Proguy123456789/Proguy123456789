local Library = loadstring(game:HttpGet("https://pastebin.com/raw/vff1bQ9F"))()
local Window = Library.CreateLib("Pro Hub V0.10", "DarkTheme")

-- Tabs

local Tab1 = Window:NewTab("Basic Script")
local Tab1Section = Tab1:NewSection("2basic4me")

-- Buttons/Windows/Idk

Tab1Section:NewButton("Inf Jumps", "Enables Inf Jumps", function()
    local InfiniteJumpEnabled = true
game:GetService("UserInputService").JumpRequest:connect(function()
	if InfiniteJumpEnabled then
		game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")
	end
end)
end)

Tab1Section:NewToggle("Fov", "Changes Fov", function(state)
    if state then
        game.Workspace.CurrentCamera.FieldOfView = 120
    else
        game.Workspace.CurrentCamera.FieldOfView = 80
    end
end)

Tab1Section:NewSlider("Speed", "Sussy Speed", 250, 120, function(v)
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = v
end)

local Tab2 = Window:NewTab("GUI Script")
local Tab2Section = Tab2:NewSection("Pro")

-- Buttons/Windows/Idk

Tab2Section:NewButton("IY FE", "L Admin", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
game:GetService("UserInputService").JumpRequest:connect(function()
	if InfiniteJumpEnabled then
		loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
	end
end)
end)

-- Buttons/Windows/Idk

Tab2Section:NewButton("Artic Hub (Da Hood)", "Pro HUB", function()
    loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/PolarWasHere/Arctic/main/Arctic"))()
game:GetService("UserInputService").JumpRequest:connect(function()
	if InfiniteJumpEnabled then
		loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/PolarWasHere/Arctic/main/Arctic"))()
	end
end)
end)

-- Buttons/Windows/Idk

Tab2Section:NewButton("Pro Keyboard Script", "Made By Warriorrroberr", function()
    --Subscribe to Warriorroberr on youtube
--thanks for using my script

loadstring(game:HttpGet(('https://pastebin.com/raw/SxgKjiRT'),true))()
game:GetService("UserInputService").JumpRequest:connect(function()
	if InfiniteJumpEnabled then
		--Subscribe to Warriorroberr on youtube
--thanks for using my script

loadstring(game:HttpGet(('https://pastebin.com/raw/SxgKjiRT'),true))()
	end
end)
end)

-- Buttons/Windows/Idk

Tab2Section:NewButton("Gco Hub V2", "Made By Gco_Sadx (He got acount delete or something)", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/wfej6ENn"))() 
game:GetService("UserInputService").JumpRequest:connect(function()
	if InfiniteJumpEnabled then
		loadstring(game:HttpGet("https://pastebin.com/raw/wfej6ENn"))() 
	end
end)
end)

-- Tabs

local Tab3 = Window:NewTab("Form")
local Tab3Section = Tab3:NewSection("Tranform Script")

-- Buttons/Windows/Idk

Tab3Section:NewButton("Coming Soon Bozo", "Pro HUB", function()
    
game:GetService("UserInputService").JumpRequest:connect(function()
	if InfiniteJumpEnabled then
		
	end
end)
end)

Tab1Section:NewSlider("Jumppower", "Buggy", 500, 0, function(b) -- 500 (MaxValue) | 0 (MinValue)
    game.Players.LocalPlayer.Character.Humanoid.JumpPower =  b
end)

-- Buttons/Windows/Idk

Tab2Section:NewButton("Doors Script", "Made By DarkRai Or something", function()
    -- Buttons/Windows/Idk
     loadstring(game:HttpGet("https://raw.githubusercontent.com/GamingScripter/Darkrai-X/main/Games/Doors"))()
game:GetService("UserInputService").JumpRequest:connect(function()
	if InfiniteJumpEnabled then
		loadstring(game:HttpGet("https://raw.githubusercontent.com/GamingScripter/Darkrai-X/main/Games/Doors"))()
	end
end)
end)
