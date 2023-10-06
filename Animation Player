local CoreGui = game:GetService("StarterGui")

CoreGui:SetCore("SendNotification", {
    Title = "Script Made By",
    Text = "GhostPlayer",
    Duration = 2.5,
})

local AnimationGui = Instance.new("ScreenGui")
local MainFrame = Instance.new("Frame")
local Title = Instance.new("TextButton")
local AnimationID = Instance.new("TextBox")
local Play = Instance.new("TextButton")

AnimationGui.Parent = game.CoreGui

MainFrame.Parent = AnimationGui
MainFrame.BackgroundColor3 = Color3.new(0,0,0)
MainFrame.BorderColor3 = Color3.new(1,1,1)
MainFrame.Transparency = 0
MainFrame.Position = UDim2.new(0.3,0,0.2)
MainFrame.Size = UDim2.new(0.4,0,0.5)
MainFrame.Active = true
MainFrame.Draggable = false
MainFrame.Visible = false

Title.Parent = MainFrame
Title.BackgroundColor3 = Color3.new(0,0,0)
Title.BackgroundTransparency = 1
Title.BorderColor3 = Color3.new(1,1,1)
Title.BorderSizePixel = 1
Title.Position = UDim2.new(0.1,0,0.08,0)
Title.TextColor3 = Color3.new(1,1,1)
Title.Size = UDim2.new(0.8,0.9,0.18)
Title.Text = "Animation Player"
Title.TextScaled = true
Title.TextSize = 8
Title.TextWrapped = true

AnimationID.Parent = MainFrame
AnimationID.BackgroundColor3 = Color3.new(0,0,0)
AnimationID.BackgroundTransparency = 0
AnimationID.BorderColor3 = Color3.new(1,1,1)
AnimationID.BorderSizePixel = 1
AnimationID.Position = UDim2.new(0.103524067, 0, 0.300333327, 0)
AnimationID.TextColor3 = Color3.new(1,1,1)
AnimationID.Size = UDim2.new(0.8,0.9,0.2)
AnimationID.Font = Enum.Font.SourceSansLight
AnimationID.FontSize = Enum.FontSize.Size14
AnimationID.Text = "Animation ID Here"
AnimationID.TextScaled = true
AnimationID.TextSize = 8
AnimationID.TextWrapped = true

Play.Parent = MainFrame
Play.BackgroundColor3 = Color3.new(0,0,0)
Play.BackgroundTransparency = 0
Play.BorderColor3 = Color3.new(1,1,1)
Play.BorderSizePixel = 1
Play.Position = UDim2.new(0.3,0,0.6,0)
Play.TextColor3 = Color3.new(1,1,1)
Play.Size = UDim2.new(0.4,0.9,0.18)
Play.Font = Enum.Font.SourceSansLight
Play.FontSize = Enum.FontSize.Size14
Play.Text = "Play Animation"
Play.TextScaled = true
Play.TextSize = 8
Play.TextWrapped = true

StopAnim = false
Switch = false
Play.MouseButton1Click:connect(function()
if Switch == false then
Switch = true
Play.Text = "Stop Animation"
Animation = Instance.new("Animation")
Animation.AnimationId = "rbxassetid://"..AnimationID.Text

PlayAnim = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Animation)
PlayAnim:Play()
else
Switch = false
Play.Text = "Play Animation"
StopAnim = true
end
end)


--Stop Animation Operator
game:GetService('RunService').Heartbeat:connect(function()
if StopAnim == true then
StopAnim = false
PlayAnim:Stop()
end
end)
--




local OpenGui = Instance.new("ScreenGui")
local Open = Instance.new("ImageButton")

OpenGui.Parent = game.CoreGui

Open.Parent = OpenGui
Open.BackgroundColor3 = Color3.new(0,0,0)
Open.BackgroundTransparency = 0
Open.BorderColor3 = Color3.new(1,1,1)
Open.BorderSizePixel = 1
Open.Position = UDim2.new(0.897,0,0.3)
Open.Size = UDim2.new(0.1,0,0.2)
Open.Image = "http://www.roblox.com/asset/?id=10330155065"
Open.Draggable = false

OpenSwitch = false
Open.MouseButton1Click:connect(function()
if OpenSwitch == false then
OpenSwitch = true
MainFrame.Visible = true
else
OpenSwitch = false
MainFrame.Visible = false
end
end)
