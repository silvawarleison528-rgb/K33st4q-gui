-- LocalScript inside StarterGui

local player = game.Players.LocalPlayer
local playerGui = player:WaitForChild("PlayerGui")

-- Replace these with your asset IDs!
local goldenFreddyImageId = "rbxassetid://YOUR_IMAGE_ID"
local jumpscareSoundId = "rbxassetid://YOUR_SOUND_ID"

-- Main GUI
local screenGui = Instance.new("ScreenGui")
screenGui.Name = "k33st4q_gui"
screenGui.Parent = playerGui

-- Main Frame
local mainFrame = Instance.new("Frame")
mainFrame.Size = UDim2.new(0, 250, 0, 470)
mainFrame.Position = UDim2.new(0.5, -125, 0.5, -235)
mainFrame.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
mainFrame.BorderSizePixel = 0
mainFrame.Parent = screenGui

-- Title
local title = Instance.new("TextLabel")
title.Size = UDim2.new(1, 0, 0, 40)
title.BackgroundTransparency = 1
title.Text = "k33st4q gui"
title.TextColor3 = Color3.fromRGB(255, 255, 255)
title.Font = Enum.Font.SourceSansBold
title.TextSize = 28
title.Parent = main

