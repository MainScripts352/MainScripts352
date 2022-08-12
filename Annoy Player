local CoreGui = game:GetService("StarterGui")

CoreGui:SetCore("SendNotification", {
    Title = "Script Made By",
    Text = "GhostPlayer",
    Icon = "rbxassetid://29819383",
    Duration = 2.5,
})

local lplayer = game:GetService('Players').LocalPlayer
 
local yeeting = false
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
function ahh(thing)
local asd = {'yeet','gui','yeet gui'}
local f = string.upper(asd[math.random(1,#asd)])
return f
end

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TextBox = Instance.new("TextBox")
local TextButton = Instance.new("TextButton")
local TextButton1 = Instance.new("TextButton")
local TextButton2 = Instance.new("TextButton")

ScreenGui.Parent = game.CoreGui

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.new(0,0,0)
Frame.BorderColor3 = Color3.new(1,1,1)
Frame.Position = UDim2.new(0.2,0,0.14)
Frame.Size = UDim2.new(0.6,0.5,0.6)
Frame.Active = true
Frame.Draggable = true

TextBox.Parent = Frame
TextBox.BackgroundColor3 = Color3.new(1,1,1)
TextBox.BackgroundTransparency = 0.80000001192093
TextBox.Position = UDim2.new(0.03,0,0.3)
TextBox.TextColor3 = Color3.new(1,1,1)
TextBox.Size = UDim2.new(0.94,0.9,0.6)
TextBox.Font = Enum.Font.SourceSansLight
TextBox.FontSize = Enum.FontSize.Size14
TextBox.Text = "Player Name Here"
TextBox.TextScaled = true
TextBox.TextSize = 8
TextBox.TextWrapped = true

TextButton.Parent = Frame
TextButton.BackgroundColor3 = Color3.new(1,1,1)
TextButton.BackgroundTransparency = 0
TextButton.Position = UDim2.new(0.03,0,0.08)
TextButton.Size = UDim2.new(0.3,0.2,0.15)
TextButton.Font = Enum.Font.SourceSansLight
TextButton.FontSize = Enum.FontSize.Size14
TextButton.Text = "Annoy"
TextButton.TextScaled = true
TextButton.TextSize = 8
TextButton.TextWrapped = true


TextButton1.Parent = Frame
TextButton1.BackgroundColor3 = Color3.new(1,1,1)
TextButton1.BackgroundTransparency = 0
TextButton1.Position = UDim2.new(0.35,0,0.08)
TextButton1.Size = UDim2.new(0.3,0.2,0.15)
TextButton1.Font = Enum.Font.SourceSansLight
TextButton1.FontSize = Enum.FontSize.Size14
TextButton1.Text = "UnAnnoy"
TextButton1.TextScaled = true
TextButton1.TextSize = 8
TextButton1.TextWrapped = true

TextButton2.Parent = Frame
TextButton2.BackgroundColor3 = Color3.new(1,1,1)
TextButton2.BackgroundTransparency = 0
TextButton2.Position = UDim2.new(0.67,0,0.08)
TextButton2.Size = UDim2.new(0.3,0.2,0.15)
TextButton2.Font = Enum.Font.SourceSansLight
TextButton2.FontSize = Enum.FontSize.Size14
TextButton2.Text = "Goto"
TextButton2.TextScaled = true
TextButton2.TextSize = 8
TextButton2.TextWrapped = true

TextButton1.MouseButton1Click:Connect(function()
getgenv().Annoy = false
ypcall(function()
game:GetService'Players'.LocalPlayer.Character.HumanoidRootPart.yeetforce:Destroy()
game:GetService'Players'.LocalPlayer.Character.Humanoid.PlatformStand = false
end)
yeeting = false
end)
TextButton.MouseButton1Click:Connect(function()
getgenv().Annoy = true
while getgenv().Annoy == true do
spawn(function()
local target = unpack(GetPlayer(TextBox.Text)).Character
 
yeeting = true
local coin = Instance.new('BodyThrust',game:GetService'Players'.LocalPlayer.Character.HumanoidRootPart)
coin.Name = "yeetforce"
repeat game:GetService'Players'.LocalPlayer.Character.HumanoidRootPart.CFrame = target.Head.CFrame;coin.Location = target.Head.Position game["Run Service"].Heartbeat:wait() until not target.Head or yeeting == false
end)
wait(0.1)
end;
end)

TextButton2.MouseButton1Click:Connect(function()
local target = unpack(GetPlayer(TextBox.Text)).Character
 
game:GetService'Players'.LocalPlayer.Character.HumanoidRootPart.CFrame = target.Head.CFrame;coin.Location = target.Head.Position game["Run Service"].Heartbeat:wait()
end)
