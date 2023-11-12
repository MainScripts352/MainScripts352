local CoreGui = game:GetService("StarterGui")

CoreGui:SetCore("SendNotification", {
    Title = "Script Made By",
    Text = "GhostPlayer",
    Icon = "rbxassetid://29819383",
    Duration = 2.5,
})

local OriginalCharacter = game.Players.LocalPlayer.Character
OriginalCharacter.Archivable = true

local Clone = OriginalCharacter:Clone()
Clone.Parent = workspace
Clone.HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,1000000,0)
Clone.HumanoidRootPart.Anchored = true
OriginalCharacter = game.Players.LocalPlayer.Character
Clone.RightUpperArm:Destroy()
Clone.LeftUpperArm:Destroy()
Clone.Head:Destroy()

for i, v in pairs(OriginalCharacter:GetChildren()) do
  if v:IsA("LocalScript") then
      local clone = v:Clone()
      clone.Disabled = true
      clone.Parent = Clone
  end
end

for i, v in pairs(Clone:GetDescendants()) do
  if v:IsA("BasePart") then
     v.Transparency = 1
  end
end

local function Active()
local StarterGui = game:GetService('StarterGui')
StarterGui:SetCore("ResetButtonCallback",false)
Clone.HumanoidRootPart.CFrame = OriginalCharacter.HumanoidRootPart.CFrame
ActiveMode = true
Camera = workspace.CurrentCamera
Camera.CameraType = "Fixed"
Clone.HumanoidRootPart.Anchored = false
workspace.CurrentCamera.CameraSubject = Clone.Humanoid
OriginalCharacter.Humanoid:UnequipTools()
game.Players.LocalPlayer.Character = Clone
for i, v in pairs(Clone:GetChildren()) do
 if v:IsA("LocalScript") then
   v.Disabled = false
 end
end
game.Players.LocalPlayer:ClearCharacterAppearance()
local Camera = workspace.CurrentCamera
Camera.CameraType = "Follow"
end

local function Deactive()
ActiveMode = false
local StarterGui = game:GetService('StarterGui')
StarterGui:SetCore("ResetButtonCallback",true)
OriginalCharacter.HumanoidRootPart.CFrame = Clone.LowerTorso.CFrame * CFrame.Angles(math.rad(0),math.rad(0),math.rad(360))
Camera = workspace.CurrentCamera
Camera.CameraType = "Fixed"
Clone.HumanoidRootPart.Anchored = true
workspace.CurrentCamera.CameraSubject = OriginalCharacter.Humanoid
for i, v in pairs(Clone:GetChildren()) do
  if v:IsA("LocalScript") then
    v.Disabled = true
  end
end
game.Players.LocalPlayer.Character = OriginalCharacter
local Camera = workspace.CurrentCamera
Camera.CameraType = "Follow"
end

ActiveMode = false
game:GetService('RunService').RenderStepped:connect(function()
if ActiveMode == true then
OriginalCharacter.HumanoidRootPart.CFrame = Clone.LowerTorso.CFrame * CFrame.Angles(math.rad(0),math.rad(0),math.rad(180))
OriginalCharacter.Head.CanCollide = false
OriginalCharacter.UpperTorso.CanCollide = false
OriginalCharacter.LowerTorso.CanCollide = false
OriginalCharacter.HumanoidRootPart.CanCollide = false
end
if OriginalCharacter.Humanoid.Health <= 0 or not OriginalCharacter:FindFirstChild("HumanoidRootPart") then
Clone:Destroy()
end
end)

NameHotkey = Enum.KeyCode.U
local uis = game:GetService("UserInputService")

KeySwitch = false
uis.InputBegan:Connect(function(inp, processed)
if inp.KeyCode == NameHotkey then
if KeySwitch == false then
KeySwitch = true
Active()
else
KeySwitch = false
Deactive()
end
end
end)

wait(1)
local CoreGui = game:GetService("StarterGui")

CoreGui:SetCore("SendNotification", {
    Title = "Script",
    Text = "Press 'U' to Active!",
    Duration = 1.5,
})
