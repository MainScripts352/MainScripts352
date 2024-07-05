local CoreGui = game:GetService("StarterGui")

CoreGui:SetCore("SendNotification", {
    Title = "Script Made By",
    Text = "GhostPlayer",
    Icon = "rbxassetid://29819383",
    Duration = 2.5,
})

--Admin Detector in Server
loadstring(game:HttpGet('https://raw.githubusercontent.com/MainScripts352/MainScripts352/main/Admin'))()
--

local ScreenGui = Instance.new("ScreenGui")
local MainFrame = Instance.new("Frame")
local Open = Instance.new("TextButton")
local Title = Instance.new("TextLabel")
local Frame = Instance.new("Frame")
local UIGradient = Instance.new("UIGradient")
local SpeedTextBox = Instance.new("TextBox")
local Decrease = Instance.new("TextButton")
local Increase = Instance.new("TextButton")
local FlyButton = Instance.new("TextButton")
local UICorner = Instance.new("UICorner")

ScreenGui.Parent = game:WaitForChild("CoreGui")
ScreenGui.ResetOnSpawn = false

MainFrame.Parent = ScreenGui
MainFrame.Active = true
MainFrame.BackgroundColor3 = Color3.fromRGB(125, 125, 125)
MainFrame.BorderColor3 = Color3.fromRGB(226, 226, 226)
MainFrame.Position = UDim2.new(0.3, -76, 0.6, -150)
MainFrame.Size = UDim2.new(0, 200, 0, 33)
MainFrame.Draggable = true

Open.Parent = MainFrame
Open.Active = true
Open.BackgroundColor3 = Color3.fromRGB(125, 125, 125)
Open.BackgroundTransparency = 1
Open.BorderColor3 = Color3.fromRGB(226, 226, 226)
Open.Position = UDim2.new(0, 160, 0, 0)
Open.Text = ">"
Open.TextColor3 = Color3.fromRGB(187, 255, 253)
Open.TextSize = 20
Open.Size = UDim2.new(0, 40, 0, 33)

Title.Parent = MainFrame
Title.Active = true
Title.BackgroundColor3 = Color3.fromRGB(119, 124, 127)
Title.BackgroundTransparency = 1
Title.BorderColor3 = Color3.fromRGB(119, 124, 127)
Title.Position = UDim2.new(0.5, 0, 0.5, 0)
Title.Size = UDim2.new(0, 0, 0, 0)
Title.Font = Enum.Font.SourceSans
Title.Text = "Vehicle Fly Gui"
Title.TextColor3 = Color3.fromRGB(187, 255, 253)
Title.TextSize = 16
Title.TextStrokeColor3 = Color3.fromRGB(187, 255, 253)
Title.TextWrapped = false

Frame.Parent = MainFrame
Frame.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
Frame.BackgroundTransparency = 0.500
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(-0.00086286955, 0, 0.999025285, 0)
Frame.Size = UDim2.new(0, 200, 0, 150)
Frame.Visible = false

SpeedTextBox.Name = "TextBox"
SpeedTextBox.Parent = Frame
SpeedTextBox.BackgroundColor3 = Color3.fromRGB(125, 125, 125)
SpeedTextBox.Position = UDim2.new(0.375, 0, 0.115, 0)
SpeedTextBox.Size = UDim2.new(0, 52, 0, 45)
SpeedTextBox.Font = Enum.Font.SourceSans
SpeedTextBox.Text = "1"
SpeedTextBox.TextColor3 = Color3.fromRGB(187, 255, 253)
SpeedTextBox.TextSize = 30
SpeedTextBox.TextWrapped = true

Decrease.Name = "Decrease"
Decrease.Parent = Frame
Decrease.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Decrease.Position = UDim2.new(0.13, 0, 0.1, 0)
Decrease.Size = UDim2.new(0, 50, 0, 50)
Decrease.Style = Enum.ButtonStyle.RobloxRoundButton
Decrease.Font = Enum.Font.SourceSans
Decrease.Text = "-"
Decrease.TextColor3 = Color3.fromRGB(187, 255, 253)
Decrease.TextSize = 30
Decrease.TextWrapped = true

Increase.Name = "Increase"
Increase.Parent = Frame
Increase.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Increase.Position = UDim2.new(0.63, 0, 0.1, 0)
Increase.Size = UDim2.new(0, 50, 0, 50)
Increase.Style = Enum.ButtonStyle.RobloxRoundButton
Increase.Font = Enum.Font.SourceSans
Increase.Text = "+"
Increase.TextColor3 = Color3.fromRGB(187, 255, 253)
Increase.TextSize = 30
Increase.TextWrapped = true

FlyButton.Name = "Fly"
FlyButton.Parent = Frame
FlyButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
FlyButton.Position = UDim2.new(0.13, 0, 0.5, 0)
FlyButton.Size = UDim2.new(0, 150, 0, 50)
FlyButton.Style = Enum.ButtonStyle.RobloxRoundButton
FlyButton.Font = Enum.Font.SourceSans
FlyButton.Text = "Fly"
FlyButton.TextColor3 = Color3.fromRGB(187, 255, 253)
FlyButton.TextSize = 30
FlyButton.TextWrapped = true

UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(125, 125, 125)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(125, 125, 125))}
UIGradient.Parent = MainFrame

UICorner.CornerRadius = UDim.new(0.15, 0)
UICorner.Parent = SpeedTextBox

Open.MouseButton1Click:Connect(function()
if Frame.Visible == false then
   Frame.Visible = true
   Open.Text = "V"
   Open.TextSize = 14
else
   Frame.Visible = false
   Open.Text = ">"
   Open.TextSize = 20
end
end)






-----Script Buttons Function

Decrease.MouseButton1Down:connect(function()
SpeedTextBox.Text = SpeedTextBox.Text - 1
end)

Increase.MouseButton1Down:connect(function()
SpeedTextBox.Text = SpeedTextBox.Text + 1
end)


--Enable Fly Function
local function EnableFly()
velocityHandlerName = 32
gyroHandlerName = 64
camera = workspace.CurrentCamera
v3none = Vector3.new()
v3zero = Vector3.new(0, 0, 0)
v3inf = Vector3.new(9e9, 9e9, 9e9)
controlModule = require(game.Players.LocalPlayer.PlayerScripts:WaitForChild("PlayerModule"):WaitForChild("ControlModule"))

bv = Instance.new("BodyVelocity")
bv.Name = velocityHandlerName
bv.Parent = game.Players.LocalPlayer.Character.HumanoidRootPart
bv.MaxForce = v3zero
bv.Velocity = v3zero

bg = Instance.new("BodyGyro")
bg.Name = gyroHandlerName
bg.Parent = game.Players.LocalPlayer.Character.HumanoidRootPart
bg.MaxTorque = v3inf
bg.P = 1000
bg.D = 50

mfly1 = game.Players.LocalPlayer.CharacterAdded:Connect(function()
 local bv = Instance.new("BodyVelocity")
 bv.Name = velocityHandlerName
 bv.Parent = game.Players.LocalPlayer.Character.HumanoidRootPart
 bv.MaxForce = v3zero
 bv.Velocity = v3zero

 bg = Instance.new("BodyGyro")
 bg.Name = gyroHandlerName
 bg.Parent = game.Players.LocalPlayer.Character.HumanoidRootPart
 bg.MaxTorque = v3inf
 bg.P = 1000
 bg.D = 50
end)

mfly2 = game:GetService('RunService').RenderStepped:connect(function()
 camera = workspace.CurrentCamera
 if game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Humanoid") and game.Players.LocalPlayer.Character.HumanoidRootPart and game.Players.LocalPlayer.Character.HumanoidRootPart:FindFirstChild(velocityHandlerName) and game.Players.LocalPlayer.Character.HumanoidRootPart:FindFirstChild(gyroHandlerName) then
    humanoid = game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Humanoid")
    VelocityHandler = game.Players.LocalPlayer.Character.HumanoidRootPart:FindFirstChild(velocityHandlerName)
    GyroHandler = game.Players.LocalPlayer.Character.HumanoidRootPart:FindFirstChild(gyroHandlerName)

    VelocityHandler.MaxForce = v3inf
    GyroHandler.MaxTorque = v3inf
    GyroHandler.CFrame = camera.CoordinateFrame
    VelocityHandler.Velocity = v3none

    direction = controlModule:GetMoveVector()
    if direction.X > 0 then
       VelocityHandler.Velocity = VelocityHandler.Velocity + camera.CFrame.RightVector * (direction.X * ((SpeedTextBox.Text) * 50))
    end
    if direction.X < 0 then
       VelocityHandler.Velocity = VelocityHandler.Velocity + camera.CFrame.RightVector * (direction.X * ((SpeedTextBox.Text) * 50))
    end
    if direction.Z > 0 then
       VelocityHandler.Velocity = VelocityHandler.Velocity - camera.CFrame.LookVector * (direction.Z * ((SpeedTextBox.Text) * 50))
    end
    if direction.Z < 0 then
       VelocityHandler.Velocity = VelocityHandler.Velocity - camera.CFrame.LookVector * (direction.Z * ((SpeedTextBox.Text) * 50))
   end
end
end)
end
--


--Disable Fly Function
local function DisableFly()
game.Players.LocalPlayer.Character.HumanoidRootPart:FindFirstChild(velocityHandlerName):Destroy()
game.Players.LocalPlayer.Character.HumanoidRootPart:FindFirstChild(gyroHandlerName):Destroy()
game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Humanoid").PlatformStand = false
mfly1:Disconnect()
mfly2:Disconnect()
end
--


FlyButton.MouseButton1Down:connect(function()
if FlyButton.Text == "Fly" then
   FlyButton.Text = "UnFly"
   EnableFly()
else
   FlyButton.Text = "Fly"
   DisableFly()
end
end)
