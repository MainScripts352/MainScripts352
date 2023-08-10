local CoreGui = game:GetService("StarterGui")

CoreGui:SetCore("SendNotification", {
    Title = "Script Made By",
    Text = "Ghostplayer",
    Duration = 2,
})

local TimerGui = Instance.new("ScreenGui")
local TimerImage = Instance.new("ImageButton")
local TimerFrame = Instance.new("Frame")
local Timer = Instance.new("TextButton")
local Start = Instance.new("TextButton")
local Pause = Instance.new("TextButton")
local Stop = Instance.new("TextButton")
local Attach = Instance.new("TextButton")

TimerGui.Parent = game.CoreGui

TimerImage.Parent = TimerGui
TimerImage.BackgroundColor3 = Color3.new(1,1,1)
TimerImage.BackgroundTransparency = 1
TimerImage.Position = UDim2.new(0.8,0,0)
TimerImage.Image = "rbxassetid://14385954911"
TimerImage.Size = UDim2.new(0.23,0,0.5)
TimerImage.Draggable = false
TimerImage.Visible = false

TimerFrame.Parent = TimerImage
TimerFrame.BackgroundColor3 = Color3.new(1,1,1)
TimerFrame.BorderColor3 = Color3.new(0,0,0)
TimerFrame.BorderSizePixel = 2
TimerFrame.BackgroundTransparency = 0
TimerFrame.Position = UDim2.new(0.325,0,0.525)
TimerFrame.Size = UDim2.new(0.35,0,0.15)

Timer.Parent = TimerFrame
Timer.BackgroundColor3 = Color3.new(1,1,1)
Timer.BackgroundTransparency = 0
Timer.Position = UDim2.new(0,0,0)
Timer.TextColor3 = Color3.new(0,0,0)
Timer.Size = UDim2.new(1,0,1)
Timer.Text = "0"
Timer.TextScaled = true
Timer.TextSize = 8
Timer.TextWrapped = true

Start.Parent = TimerImage
Start.BackgroundColor3 = Color3.new(1,1,1)
Start.BackgroundTransparency = 0
Start.Position = UDim2.new(0.4,0,0.7375)
Start.TextColor3 = Color3.new(0,0,0)
Start.Size = UDim2.new(0.18,0,0.08)
Start.Text = "Start"
Start.TextScaled = true
Start.TextSize = 8
Start.TextWrapped = true

Pause.Parent = TimerImage
Pause.BackgroundColor3 = Color3.new(1,1,1)
Pause.BackgroundTransparency = 0
Pause.Position = UDim2.new(0.3,0,0.7375)
Pause.TextColor3 = Color3.new(0,0,0)
Pause.Size = UDim2.new(0.18,0,0.08)
Pause.Text = "Pause"
Pause.TextScaled = true
Pause.TextSize = 8
Pause.TextWrapped = true
Pause.Visible = false

Stop.Parent = TimerImage
Stop.BackgroundColor3 = Color3.new(1,1,1)
Stop.BackgroundTransparency = 0
Stop.Position = UDim2.new(0.515,0,0.7375)
Stop.TextColor3 = Color3.new(0,0,0)
Stop.Size = UDim2.new(0.18,0,0.08)
Stop.Text = "Stop"
Stop.TextScaled = true
Stop.TextSize = 8
Stop.TextWrapped = true
Stop.Visible = false

Attach.Parent = TimerImage
Attach.BackgroundColor3 = Color3.new(0,350,0)
Attach.BackgroundTransparency = 0
Attach.Position = UDim2.new(0.4,0,1.05)
Attach.TextColor3 = Color3.new(0,0,0)
Attach.Size = UDim2.new(0.18,0,0.08)
Attach.Text = "Attach"
Attach.TextScaled = true
Attach.TextSize = 8
Attach.TextWrapped = true




Time = 0
Min = 0
Start.MouseButton1Click:connect(function()
Start.Visible = false
Stop.Visible = true
Pause.Visible = true
wait(1)
getgenv().Timer = true
while getgenv().Timer == true do
Time += 1
if Min == 0 then
Timer.Text = ""..Time
else
Timer.Text = Min..":"..Time
end
if Time == 60 then
Time = 0
Min += 1
Timer.Text = Min..":"..Time
end
wait(1)
end
end)

Switch1 = false
Pause.MouseButton1Click:connect(function()
if Switch1 == false then
Switch1 = true
Pause.Text = "Play"
getgenv().Timer = false
else
Switch1 = false
Pause.Text = "Pause"
wait(1)
getgenv().Timer = true
while getgenv().Timer == true do
Time += 1
if Min == 0 then
Timer.Text = ""..Time
else
Timer.Text = Min..":"..Time
end
if Time == 60 then
Time = 0
Min += 1
Timer.Text = Min..":"..Time
end
wait(1)
end
end
end)


Stop.MouseButton1Click:connect(function()
Stop.Visible = false
Pause.Visible = false
Start.Visible = true
getgenv().Timer = false
Timer.Text = "0"
Switch1 = false
Pause.Text = "Pause"
Time = 0
Min = 0
end)


ActiveAttach = false
Switch2 = false
Attach.MouseButton1Click:connect(function()
if Switch2 == false then
Switch2 = true
Attach.BackgroundColor3 = Color3.new(8,0,0)
ActiveAttach = true
else
Switch2 = false
Attach.BackgroundColor3 = Color3.new(0,350,0)
ActiveAttach = false
if not workspace[game.Players.LocalPlayer.Character.HumanoidRootPart.Parent.Name]:FindFirstChild("Timer") then
TimerImage.Visible = false
end
end
end)




tool = Instance.new("Tool")
tool.RequiresHandle = false
tool.Name = ("Timer")
tool.TextureId = "http://www.roblox.com/asset/?id=14386855865"

tool.Equipped:Connect(function()
TimerImage.Visible = true
end)

tool.Unequipped:Connect(function()
if ActiveAttach == false then
TimerImage.Visible = false
end
end)

tool.Parent = game.Players.LocalPlayer.Backpack
