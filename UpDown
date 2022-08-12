--UpDown Script Created By GhostPlayer
--Create Date Jun 6 2022 PM5:04

local CoreGui = game:GetService("StarterGui")

CoreGui:SetCore("SendNotification", {
    Title = "Script Made By",
    Text = "GhostPlayer",
    Icon = "rbxassetid://29819383",
    Duration = 2.5,
})

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TextButton = Instance.new("TextBox")
local TextButton1 = Instance.new("TextButton")

ScreenGui.Parent = game.CoreGui

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.new(0,0,0)
Frame.BorderColor3 = Color3.new(1,1,1)
Frame.Position = UDim2.new(0.293040276, 0, 0.491666675, 0)
Frame.Size = UDim2.new(0.18,0.2,0.4)
Frame.Active = true
Frame.Draggable = true

TextButton.Parent = Frame
TextButton.BackgroundColor3 = Color3.new(1,1,1)
TextButton.BackgroundTransparency = 0
TextButton.Position = UDim2.new(0.103524067, 0, 0.200333327, 0)
TextButton.TextColor3 = Color3.new(0,0,0)
TextButton.Size = UDim2.new(0.8,0.9,0.3)
TextButton.Font = Enum.Font.SourceSansLight
TextButton.FontSize = Enum.FontSize.Size14
TextButton.Text = "Number Here"
TextButton.TextScaled = true
TextButton.TextSize = 8
TextButton.TextWrapped = true

TextButton1.Parent = Frame
TextButton1.BackgroundColor3 = Color3.new(1,1,1)
TextButton1.BackgroundTransparency = 0
TextButton1.Position = UDim2.new(0.2,0,0.6)
TextButton1.TextColor3 = Color3.new(0,0,0)
TextButton1.Size = UDim2.new(0.6,0.9,0.2)
TextButton1.Font = Enum.Font.SourceSansLight
TextButton1.FontSize = Enum.FontSize.Size14
TextButton1.Text = "Setup"
TextButton1.TextScaled = true
TextButton1.TextSize = 8
TextButton1.TextWrapped = true

TextButton1.MouseButton1Click:connect(function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,TextButton.text,0)
end)
