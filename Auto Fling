local ScreenGui0 = Instance.new("ScreenGui")
local Frame0 = Instance.new("Frame")
local TextButton0 = Instance.new("TextButton")
local TextButton01 = Instance.new("TextButton")

ScreenGui0.Parent = game.CoreGui

Frame0.Parent = ScreenGui0
Frame0.BackgroundColor3 = Color3.new(8,0,0)
Frame0.BorderColor3 = Color3.new(0,0,0)
Frame0.BorderSizePixel = 1
Frame0.Position = UDim2.new(0.3,0,0.25)
Frame0.Size = UDim2.new(0.4,0.2,0.4)
Frame0.Active = true
Frame0.Draggable = false
Frame0.Visible = false

TextButton01.Parent = Frame0
TextButton01.BackgroundColor3 = Color3.new(8,0,0)
TextButton01.BackgroundTransparency = 0
TextButton01.Position = UDim2.new(0.103524067, 0, 0.200333327, 0)
TextButton01.TextColor3 = Color3.new(0,0,0)
TextButton01.Size = UDim2.new(0.8,0.9,0.6)
TextButton01.Font = Enum.Font.SourceSansLight
TextButton01.FontSize = Enum.FontSize.Size14
TextButton01.Text = "UnAuto Fling"
TextButton01.TextScaled = true
TextButton01.TextSize = 8
TextButton01.TextWrapped = true
TextButton01.Visible = false

TextButton01.MouseButton1Click:connect(function()
TextButton01.Visible = false
TextButton0.Visible = true
getgenv().Fling = false
game.Players.LocalPlayer.Character:Destroy()
end)

TextButton0.Parent = Frame0
TextButton0.BackgroundColor3 = Color3.new(8,0,0)
TextButton0.BackgroundTransparency = 0
TextButton0.Position = UDim2.new(0.103524067, 0, 0.200333327, 0)
TextButton0.TextColor3 = Color3.new(0,0,0)
TextButton0.Size = UDim2.new(0.8,0.9,0.6)
TextButton0.Font = Enum.Font.SourceSansLight
TextButton0.FontSize = Enum.FontSize.Size14
TextButton0.Text = "Auto Fling"
TextButton0.TextScaled = true
TextButton0.TextSize = 8
TextButton0.TextWrapped = true

TextButton0.MouseButton1Click:connect(function()
TextButton0.Visible = false
TextButton01.Visible = true
local ch = game.Players.LocalPlayer.Character
local prt=Instance.new("Model", workspace)
local z1 =  Instance.new("Part", prt)
z1.Name="Torso"
z1.CanCollide = false
z1.Anchored = true
local z2  =Instance.new("Part", prt)
z2.Name="Head"
z2.Anchored = true
z2.CanCollide = false
local z3 =Instance.new("Humanoid", prt)
z3.Name="Humanoid"
z1.Position = Vector3.new(0,9999,0)
z2.Position = Vector3.new(0,9991,0)
 game.Players.LocalPlayer.Character=prt
wait(3)
game.Players.LocalPlayer.Character=ch
wait(4)


local plr = game.Players.LocalPlayer
mouse = plr:GetMouse()

local Hum = Instance.new("Humanoid")
Hum.Parent = game.Players.LocalPlayer.Character


local root =  game.Players.LocalPlayer.Character.HumanoidRootPart


for i,v in pairs(plr.Character:GetChildren()) do
	
	if v ~= root and  v.Name ~= "Humanoid" then
		
		v:Destroy()
		
	end
end
workspace.CurrentCamera.CameraSubject = root

local se = Instance.new("SelectionBox",root)
se.Adornee = root


game:GetService('RunService').Stepped:connect(function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CanCollide = false
end)
game:GetService('RunService').RenderStepped:connect(function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CanCollide = false
end)


power = 999999

power = power*10

wait(.1)
local bambam = Instance.new("BodyThrust")
bambam.Parent = game.Players.LocalPlayer.Character.HumanoidRootPart
bambam.Force = Vector3.new(power,0,power)
bambam.Location = game.Players.LocalPlayer.Character.HumanoidRootPart.Position 

local plr = game.Players.LocalPlayer
local torso = root
local flying = true
local deb = true
local ctrl = {f = 0, b = 0, l = 0, r = 0}
local lastctrl = {f = 0, b = 0, l = 0, r = 0}
local maxspeed = 120
local speed = 15
groot = root
 
function Fly()
local bg = Instance.new("BodyGyro", torso)
bg.P = 9e4
bg.maxTorque = Vector3.new(0, 0, 0)
bg.cframe = torso.CFrame
local bv = Instance.new("BodyVelocity", torso)
bv.velocity = Vector3.new(0,0,0)
bv.maxForce = Vector3.new(9e9, 9e9, 9e9)
repeat wait()

if ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0 then
speed = speed+.2
if speed > maxspeed then
speed = maxspeed
end
elseif not (ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0) and speed ~= 0 then
speed = speed-1
if speed < 0 then
speed = 0
end
end
if (ctrl.l + ctrl.r) ~= 0 or (ctrl.f + ctrl.b) ~= 0 then
bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (ctrl.f+ctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(ctrl.l+ctrl.r,(ctrl.f+ctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
lastctrl = {f = ctrl.f, b = ctrl.b, l = ctrl.l, r = ctrl.r}
elseif (ctrl.l + ctrl.r) == 0 and (ctrl.f + ctrl.b) == 0 and speed ~= 0 then
bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (lastctrl.f+lastctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(lastctrl.l+lastctrl.r,(lastctrl.f+lastctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
else
bv.velocity = Vector3.new(0,0.1,0)
end

until not flying
ctrl = {f = 0, b = 0, l = 0, r = 0}
lastctrl = {f = 0, b = 0, l = 0, r = 0}
speed = 0
bg:Destroy()
bv:Destroy()

end
mouse.KeyDown:connect(function(key)
if key:lower() == "e" then
if flying then flying = false
else
flying = true
Fly()
end
elseif key:lower() == "w" then
ctrl.f = 1
elseif key:lower() == "s" then
ctrl.b = -1
elseif key:lower() == "a" then
ctrl.l = -1
elseif key:lower() == "d" then
ctrl.r = 1
end
end)
mouse.KeyUp:connect(function(key)
if key:lower() == "w" then
ctrl.f = 0
elseif key:lower() == "s" then
ctrl.b = 0
elseif key:lower() == "a" then
ctrl.l = 0
elseif key:lower() == "d" then
ctrl.r = 0
elseif key:lower() == "r" then

end
end)
Fly()
end)

TextButton0.MouseButton1Click:connect(function()
wait(10)
getgenv().fling = true
while getgenv().fling == true do
if game.Players.LocalPlayer.Character.Humanoid.Health - 0 then
for _,v in next, Workspace:GetDescendants() do 
    if v.Name == "HumanoidRootPart" then 
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.CFrame
       wait(1)
       end
end
end
wait(0.1)
end
end)


local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TextButton = Instance.new("TextButton")
local TextButton1 = Instance.new("TextButton")

ScreenGui.Parent = game.CoreGui

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.new(8,0,0)
Frame.BorderColor3 = Color3.new(0,0,0)
Frame.BorderSizePixel = 1
Frame.Position = UDim2.new(0,0,0.8)
Frame.Size = UDim2.new(0.1,0,0.1)
Frame.Active = true
Frame.Draggable = false

TextButton1.Parent = Frame
TextButton1.BackgroundColor3 = Color3.new(8,0,0)
TextButton1.BackgroundTransparency = 1
TextButton1.Position = UDim2.new(0,0,0.1)
TextButton1.TextColor3 = Color3.new(0,0,0)
TextButton1.Size = UDim2.new(0.99,0,0.8)
TextButton1.Font = Enum.Font.SourceSansLight
TextButton1.FontSize = Enum.FontSize.Size14
TextButton1.Text = "Close"
TextButton1.TextScaled = true
TextButton1.TextSize = 8
TextButton1.TextWrapped = true
TextButton1.Visible = false

TextButton1.MouseButton1Click:connect(function()
TextButton1.Visible = false
TextButton.Visible = true
Frame0.Visible = false
end)

TextButton.Parent = Frame
TextButton.BackgroundColor3 = Color3.new(8,0,0)
TextButton.BackgroundTransparency = 1
TextButton.Position = UDim2.new(0,0,0.1)
TextButton.TextColor3 = Color3.new(0,0,0)
TextButton.Size = UDim2.new(0.99,0,0.8)
TextButton.Font = Enum.Font.SourceSansLight
TextButton.FontSize = Enum.FontSize.Size14
TextButton.Text = "Open"
TextButton.TextScaled = true
TextButton.TextSize = 8
TextButton.TextWrapped = true

TextButton.MouseButton1Click:connect(function()
TextButton.Visible = false
TextButton1.Visible = true
Frame0.Visible = true
end)
