local CoreGui = game:GetService("StarterGui") 
      CoreGui:SetCore("SendNotification", {    
      Title = "Script Made By",
      Text = "GhostPlayer",
      Icon = "rbxassetid://29819383",
      Duration = 2.5,
})


local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TextButton = Instance.new("TextButton")
local TextButton1 = Instance.new("TextButton")

ScreenGui.Parent = game.CoreGui

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.new(0,0,0)
Frame.BorderColor3 = Color3.new(8,0,0)
Frame.Position = UDim2.new(0.293040276, 0, 0.491666675, 0)
Frame.Size = UDim2.new(0.13,0.2,0.12)
Frame.Active = true
Frame.Draggable = true

TextButton.Parent = Frame
TextButton.BackgroundColor3 = Color3.new(8,0,0)
TextButton.BackgroundTransparency = 0
TextButton.Position = UDim2.new(0.08, 0, 0.200333327, 0)
TextButton.TextColor3 = Color3.new(0,0,0)
TextButton.Size = UDim2.new(0.4,0.9,0.45)
TextButton.Font = Enum.Font.SourceSansLight
TextButton.FontSize = Enum.FontSize.Size14
TextButton.Text = "Set"
TextButton.TextScaled = true
TextButton.TextSize = 8
TextButton.TextWrapped = true

TextButton.MouseButton1Click:connect(function()
local old = game.Players.LocalPlayer.Character:getChildren()

for i=1,#old do 
if old[i].Name == "HumanoidRootPart" then
lastPos = old[i].CFrame
end
end
end)

TextButton1.Parent = Frame
TextButton1.BackgroundColor3 = Color3.new(8,0,0)
TextButton1.BackgroundTransparency = 0
TextButton1.Position = UDim2.new(0.55,0,0.2)
TextButton1.TextColor3 = Color3.new(0,0,0)
TextButton1.Size = UDim2.new(0.4,0.9,0.45)
TextButton1.Font = Enum.Font.SourceSansLight
TextButton1.FontSize = Enum.FontSize.Size14
TextButton1.Text = "TP"
TextButton1.TextScaled = true
TextButton1.TextSize = 8
TextButton1.TextWrapped = true

TextButton1.MouseButton1Click:connect(function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = lastPos
end)
