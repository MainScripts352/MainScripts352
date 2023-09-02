local CoreGui = game:GetService("StarterGui")

CoreGui:SetCore("SendNotification", {
    Title = "Script Made By",
    Text = "GhostPlayer",
    Icon = "rbxassetid://29819383",
    Duration = 2,
})

local lplayer = game:GetService('Players').LocalPlayer

function GetPlayer(String)
local Found = {}
local strl = String:lower()
if strl == "all" then
for i,v in pairs(game:GetService("Players"):GetPlayers()) do
table.insert(Found,v)
end
elseif strl == "others" then
for i,v in pairs(game:GetService("Players"):GetPlayers()) do
if v.Name ~= lplayer.Name then
table.insert(Found,v)
end
end 
elseif strl == "me" then
for i,v in pairs(game:GetService("Players"):GetPlayers()) do
if v.Name == lplayer.Name then
table.insert(Found,v)
end
end 
else
for i,v in pairs(game:GetService("Players"):GetPlayers()) do
if v.Name:lower():sub(1, #String) == String:lower() then
table.insert(Found,v)
end
end 
end
return Found 
end


local ControlGui = Instance.new("ScreenGui")
local ControlFrame = Instance.new("Frame")
local TextBox = Instance.new("TextBox")
local TextButton = Instance.new("TextButton")

ControlGui.Parent = game.CoreGui

ControlFrame.Parent = ControlGui
ControlFrame.BackgroundColor3 = Color3.fromRGB(205, 84, 75)
ControlFrame.BorderColor3 = Color3.new(1,1,1)
ControlFrame.BorderSizePixel = 2
ControlFrame.Position = UDim2.new(0.63040276, 0, 0.1, 0)
ControlFrame.Size = UDim2.new(0.16,0.2,0.4)
ControlFrame.Active = true
ControlFrame.Draggable = true

TextBox.Parent = ControlFrame
TextBox.BackgroundColor3 = Color3.fromRGB(196, 40, 28)
TextBox.BackgroundTransparency = 0
TextBox.BorderColor3 = Color3.new(1,1,1)
TextBox.BorderSizePixel = 1
TextBox.Position = UDim2.new(0.103524067, 0, 0.25, 0)
TextBox.Size = UDim2.new(0.8,0.9,0.2)
TextBox.TextColor3 = Color3.new(1,1,1)
TextBox.Font = Enum.Font.SourceSansLight
TextBox.FontSize = Enum.FontSize.Size14
TextBox.Text = "Player Name"
TextBox.TextScaled = true
TextBox.TextSize = 8
TextBox.TextWrapped = true

TextButton.Parent = ControlFrame
TextButton.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
TextButton.BackgroundTransparency = 0
TextButton.BorderColor3 = Color3.new(1,1,1)
TextButton.BorderSizePixel = 1
TextButton.Position = UDim2.new(0.2,0,0.6)
TextButton.Size = UDim2.new(0.6,0.9,0.2)
TextButton.TextColor3 = Color3.new(1,1,1)
TextButton.Text = "Get Animation"
TextButton.TextScaled = true
TextButton.TextScaled = 22
TextButton.TextWrapped = false



--Clone Self
local Self = game:GetService("Players").LocalPlayer
local OriginalCharacter = Self.Character or Self.CharacterAdded:Wait()

OriginalCharacter.Archivable = true
Double = OriginalCharacter:Clone()
Double.Parent = workspace
Double.HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,10000000,0)
Double.HumanoidRootPart.Anchored = true
--




Switch = false
TextButton.MouseButton1Click:connect(function()
TextBox.Text = ""..unpack(GetPlayer(TextBox.Text)).Name
if TextBox.Text == String then
String = nil
game.Players.LocalPlayer.Character.Animate:ClearAllChildren()
for i,v in pairs(Double.Animate:GetChildren()) do
   v:Clone().Parent = game.Players.LocalPlayer.Character.Animate
end
else
String = TextBox.Text
if TextBox.Text == ""..game.Players.LocalPlayer.Name then
TextBox.Text = "Dont Put Yourself"
wait(0.7)
TextBox.Text = "Player Name"
else
PlayerTarget = unpack(GetPlayer(TextBox.Text))

local user = PlayerTarget.Name
local victim = game.Players[user]
local plr = game.Players.LocalPlayer

plr.Character.Animate:ClearAllChildren()
for i,v in pairs(victim.Character.Animate:GetChildren()) do
   v:Clone().Parent = plr.Character.Animate
end
end
end
end)
