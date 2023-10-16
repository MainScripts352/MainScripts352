local CoreGui = game:GetService("StarterGui")

CoreGui:SetCore("SendNotification", {
    Title = "Script Made By",
    Text = "GhostPlayer",
    Icon = "rbxassetid://29819383",
    Duration = 2.5,
})

local ToolActivatorGui = Instance.new("ScreenGui")
local Activator = Instance.new("TextButton")

ToolActivatorGui.Parent = game.CoreGui

Activator.Parent = ToolActivatorGui
Activator.BackgroundColor3 = Color3.new(0,250,0)
Activator.BackgroundTransparency = 0
Activator.Position = UDim2.new(0.91, 0, 0.4, 0)
Activator.TextColor3 = Color3.new(0,0,0)
Activator.Size = UDim2.new(0.08,0.9,0.09)
Activator.Font = Enum.Font.SourceSansLight
Activator.FontSize = Enum.FontSize.Size14
Activator.Text = "Active"
Activator.TextScaled = false
Activator.TextSize = 13
Activator.TextWrapped = true
Activator.Draggable = true

Active = false
Activator.MouseButton1Click:connect(function()
if Active == false then
Active = true
Activator.BackgroundColor3 = Color3.new(8,0,0)
getgenv().AutoUseTool = true
while getgenv().AutoUseTool == true do
spawn(function()
    local p = game.Players:GetPlayers()
    for i = 2, #p do local v = p[i].Character
        if v and v:FindFirstChild("Humanoid") and v.Humanoid.Health > 0 and v:FindFirstChild("HumanoidRootPart") and game.Players.LocalPlayer:DistanceFromCharacter(v.HumanoidRootPart.Position) <= 100000 then
            local tool = game.Players.LocalPlayer.Character and game.Players.LocalPlayer.Character:FindFirstChildOfClass("Tool")
            if tool and tool:FindFirstChild("Handle") then
                tool:Activate()
                for i,v in next, v:GetChildren() do
                    if v:IsA("BasePart") then
                        firetouchinterest(tool.Handle,v,0)
                        firetouchinterest(tool.Handle,v,1)
                    end
                end
            end
        end
    end
end)
wait(0.1)
end
else
Active = false
Activator.BackgroundColor3 = Color3.new(0,250,0)
getgenv().AutoUseTool = false
end
end)
