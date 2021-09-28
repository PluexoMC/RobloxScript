--TwitchSagde--

local ScreenGui = Instance.new("ScreenGui")
local main = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local MM2 = Instance.new("TextButton")
local DaHood = Instance.new("TextButton")
local PSX = Instance.new("TextButton")
local TextButton = Instance.new("TextButton")
local TextButton_2 = Instance.new("TextButton")
local TextButton_3 = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.CoreGui

main.Name = "main"
main.Parent = ScreenGui
main.BackgroundColor3 = Color3.fromRGB(58, 58, 58)
main.Position = UDim2.new(0.477405161, 0, 0.57914108, 0)
main.Size = UDim2.new(0, 717, 0, 343)
main.Active = true
main.Draggable = true


TextLabel.Name = ""
TextLabel.Parent = main
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BorderSizePixel = 4
TextLabel.Size = UDim2.new(0, 717, 0, 50)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "S4dge Menu3 | By TwitchSadge"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextSize = 14.000

MM2.Name = "MM2"
MM2.Parent = main
MM2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
MM2.Position = UDim2.new(0.0585774072, 0, 0.227405265, 0)
MM2.Size = UDim2.new(0, 200, 0, 50)
MM2.Font = Enum.Font.SourceSans
MM2.Text = "MM2"
MM2.TextColor3 = Color3.fromRGB(0, 0, 0)
MM2.TextSize = 14.000
MM2.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/Doggo-cryto/EclipseMM2/master/Script", true))()
end)

DaHood.Name = "DaHood"
DaHood.Parent = main
DaHood.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
DaHood.Position = UDim2.new(0.38075313, 0, 0.227405265, 0)
DaHood.Size = UDim2.new(0, 200, 0, 50)
DaHood.Font = Enum.Font.SourceSans
DaHood.Text = "DaHood"
DaHood.TextColor3 = Color3.fromRGB(0, 0, 0)
DaHood.TextSize = 14.000
DaHood.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/lerkermer/lua-projects/master/SwagModeV002'))() 
end)

PSX.Name = "PSX"
PSX.Parent = main
PSX.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
PSX.Position = UDim2.new(0.702928841, 0, 0.227405265, 0)
PSX.Size = UDim2.new(0, 200, 0, 50)
PSX.Font = Enum.Font.SourceSans
PSX.Text = "Pet Simulator X"
PSX.TextColor3 = Color3.fromRGB(0, 0, 0)
PSX.TextSize = 14.000
PSX.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/TurfuGoldy/GoldenScripts/main/EzPets.lua", true))()
end)

TextButton.Parent = main
TextButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton.Position = UDim2.new(0.0585774072, 0, 0.521865904, 0)
TextButton.Size = UDim2.new(0, 200, 0, 50)
TextButton.Font = Enum.Font.SourceSans
TextButton.Text = "Soon"
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextSize = 14.000

TextButton_2.Parent = main
TextButton_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_2.Position = UDim2.new(0.38075313, 0, 0.521865904, 0)
TextButton_2.Size = UDim2.new(0, 200, 0, 50)
TextButton_2.Font = Enum.Font.SourceSans
TextButton_2.Text = "Soon"
TextButton_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.TextSize = 14.000

TextButton_3.Parent = main
TextButton_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_3.Position = UDim2.new(0.702928841, 0, 0.521865904, 0)
TextButton_3.Size = UDim2.new(0, 200, 0, 50)
TextButton_3.Font = Enum.Font.SourceSans
TextButton_3.Text = "Soon"
TextButton_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_3.TextSize = 14.000
