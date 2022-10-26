
--   ____      _               _  _    ___   ___   ___  __ 
--  / __ \    | |            _| || |_ / _ \ / _ \ / _ \/_ |
-- | |  | |___| | ____ _ _ _|_  __  _| | | | | | | | | || |
-- | |  | / __| |/ / _` | '__|| || |_| | | | | | | | | || |
-- | |__| \__ \   < (_| | | |_  __  _| |_| | |_| | |_| || |
--  \____/|___/_|\_\__,_|_|   |_||_|  \___/ \___/ \___/ |_|

-- Give credit pls


-- [ Base UI + Theme ] --

local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Kryptic Hub // https://discord.gg/jqtx62Tc3j ", "Ocean")

-- [ Credit Section ] --
local Credits = Window:NewTab("Credits")
local CreditsSection = Credits:NewSection("GUI Fully scripted and tested by Oskar#0001")

CreditsSection:NewButton("Copy Discord to clipboard", "Copies our discord link to your clipboard.", function()
	  print("Copied to clipboard!") -- idk how to make it copy lmao
end)

-- [ Main Section ] --
local Main = Window:NewTab("Main")
local MainSection = Main:NewSection("Player Options")

-- [ Player Speed Slider ] --
MainSection:NewSlider("Player Speed", "Increase or decrease player speed.", 500, 20, function(s) -- 500 (MaxValue) | 0 (MinValue)
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s
end)

-- [ Player Jump Power Slider ] --
MainSection:NewSlider("Jump Power", "Increase or decrease player jump power.", 500, 50, function(s) -- 500 (MaxValue) | 0 (MinValue)
    game.Players.LocalPlayer.Character.Humanoid.JumpPower = s
end)

-- [ Player Size Slider ] --
MainSection:NewSlider("Character Size", "Increase or decrease player size.", 50, 0.7, function(s) -- 500 (MaxValue) | 0 (MinValue)
    game.Players.LocalPlayer.Character.Humanoid.HeadScale = s
    game.Players.LocalPlayer.Character.Humanoid.BodyWidthScale = s
    game.Players.LocalPlayer.Character.Humanoid.BodyHeightScale = s
    game.Players.LocalPlayer.Character.Humanoid.BodyDepthScale = s

end)

-- [ Enable Noclip ] --
MainSection:NewButton("Enable Noclip", "Let's you phase through objects!", function()
	print("Noclip Enabled!")
end)

-- [ Remove Head / Headless ]

MainSection:NewButton("Give Headless", "Make you look rich.", function()
    game.Players.LocalPlayer.Character.Head.Transparency = 1
end)

-- [ Give Korblox ]
MainSection:NewButton("Give Korblox", "Gives you a toothpick leg.", function()
    print("Failed.")
end)
