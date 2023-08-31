local CoreGui = game:GetService("StarterGui")

CoreGui:SetCore("SendNotification", {
    Title = "Script Made By",
    Text = "GhostPlayer",
    Icon = "rbxassetid://29819383",
    Duration = 2.5,
})


RightAngle = 0
AroundAngle = 0
UpAngle = 0



---Attach Tool
AttachTool = Instance.new("Tool")
AttachTool.RequiresHandle = false
AttachTool.Name = "Attach"
AttachTool.TextureId = ""

Switch = false
AttachTool.Activated:Connect(function()
if Switch == false then
   Switch = true
AttachTool.Name = "UnAttach"
Attach = true
else
Switch = false
AttachTool.Name = "Attach"
Attach = false
end
end)

AttachTool.Parent = game.Players.LocalPlayer.Backpack


--Attach Operator
game:GetService('RunService').Heartbeat:connect(function()
if Attach == true then
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").FramePart.CFrame * CFrame.Angles(UpAngle,AroundAngle,RightAngle)
end
end)
--








---Set Position Tool
mouse = game.Players.LocalPlayer:GetMouse()
toolsps = Instance.new("Tool")
toolsps.RequiresHandle = false
toolsps.Name = "Set      Position"

toolsps.Activated:connect(function()
local pos = mouse.Hit+Vector3.new(0,1,0)
pos = CFrame.new(pos.X,pos.Y,pos.Z)
game:GetService("Workspace").FramePart.CFrame = pos
end)

toolsps.Equipped:Connect(function()
game:GetService("Workspace").FramePart.Transparency = 0.5
end)

toolsps.Unequipped:Connect(function()
game:GetService("Workspace").FramePart.Transparency = 1
end)

toolsps.Parent = game.Players.LocalPlayer.Backpack


---⬅️ Up Angle Setting
toolangle3 = Instance.new("Tool")
toolangle3.RequiresHandle = false
toolangle3.Name = ("⬆️                 0")

toolangle3.Activated:Connect(function()
UpAngle += 0.5
toolangle3.Name = "⬆️                  "..UpAngle
end)

toolangle3.Parent = game.Players.LocalPlayer.Backpack




---↪️ Turn Around Angle Setting
toolangle2 = Instance.new("Tool")
toolangle2.RequiresHandle = false
toolangle2.Name = ("↪️                 0")

toolangle2.Activated:Connect(function()
AroundAngle += 0.5
toolangle2.Name = "↪️                  "..AroundAngle
end)

toolangle2.Parent = game.Players.LocalPlayer.Backpack





---⬅️ RightAngle Setting Tool
toolangle1 = Instance.new("Tool")
toolangle1.RequiresHandle = false
toolangle1.Name = ("⬅️                 0")

toolangle1.Activated:Connect(function()
RightAngle += 0.5
toolangle1.Name = "⬅️                  "..RightAngle
end)

toolangle1.Parent = game.Players.LocalPlayer.Backpack



---Spawn Part
local part = Instance.new("Part")

local position = Vector3.new(0,100000,0)
part.Name = "FramePart"
part.Color = Color3.new(1,1,1)
part.Material = Enum.Material.Plastic
part.Transparency = 0.7
part.Position = position
part.Size = Vector3.new(2,2,1)
part.CastShadow = false
part.Anchored = true
part.CanCollide = false
part.Parent = workspace
workspace:FindFirstChild("FramePart").CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame


---Death Detector
getgenv().DeathDetector = true
while getgenv().DeathDetector == true do
spawn(function()
if game.Players.LocalPlayer.Character.Humanoid.Health <= 0 then
Attach = false
getgenv().DeathDetector = false
game:GetService("Workspace").FramePart:Destroy()
end
end)
wait(0.1)
end
