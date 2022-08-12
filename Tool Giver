local CoreGui = game:GetService("StarterGui")

CoreGui:SetCore("SendNotification", {
    Title = "Script Made By",
    Text = "GhostPlayer",
    Icon = "rbxassetid://29819383",
    Duration = 2.5,
})

local ScreenGui15 = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TextButton = Instance.new("TextButton")


ScreenGui15.Parent = game.CoreGui

Frame.Parent = ScreenGui15
Frame.BackgroundColor3 = Color3.new(0,0,0)
Frame.BorderColor3 = Color3.new(1,1,1)
Frame.Position = UDim2.new(0.00000005,1,0)
Frame.Size = UDim2.new(0.05,0.08,0.08)
Frame.Active = true
Frame.Draggable = false

TextButton.Parent = Frame
TextButton.BackgroundColor3 = Color3.new(0,0,0)
TextButton.BackgroundTransparency = 100
TextButton.Position = UDim2.new(0.103524067, 0, 0.200333327, 0)
TextButton.TextColor3 = Color3.new(1,1,1)
TextButton.Size = UDim2.new(0.8,1,0.6)
TextButton.Font = Enum.Font.SourceSansLight
TextButton.FontSize = Enum.FontSize.Size18
TextButton.Text = ">"
TextButton.TextScaled = true
TextButton.TextSize = 13
TextButton.TextWrapped = true

run = false
TextButton.MouseButton1Click:connect(function()
run = not run


---------------------------------------------------------

local ScreenGui16 = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TextButton = Instance.new("TextButton")


ScreenGui16.Parent = game.CoreGui

Frame.Parent = ScreenGui16
Frame.BackgroundColor3 = Color3.new(0,0,0)
Frame.BorderColor3 = Color3.new(1,1,1)
Frame.Position = UDim2.new(0.001,0,0.0)
Frame.Size = UDim2.new(0.3,0.2,0.2)
Frame.Active = true
Frame.Draggable = false

local ScreenGui18 = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TextButton = Instance.new("TextButton")


ScreenGui18.Parent = game.CoreGui

Frame.Parent = ScreenGui18
Frame.BackgroundColor3 = Color3.new(0,0,0)
Frame.BorderColor3 = Color3.new(0,0,0)
Frame.Position = UDim2.new(0.04,0,0.01)
Frame.Size = UDim2.new(0.2,0,0.09)
Frame.Active = true
Frame.Draggable = false

TextButton.Parent = Frame
TextButton.BackgroundColor3 = Color3.new(0,0,0)
TextButton.BackgroundTransparency = 100
TextButton.Position = UDim2.new(0.103524067, 0, 0.200333327, 0)
TextButton.TextColor3 = Color3.new(1,1,1)
TextButton.Size = UDim2.new(0.8,0.9,0.6)
TextButton.Font = Enum.Font.SourceSansLight
TextButton.FontSize = Enum.FontSize.Size14
TextButton.Text = "Tool Giver"
TextButton.TextScaled = true
TextButton.TextSize = 8
TextButton.TextWrapped = true

local ScreenGui19 = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TextButton = Instance.new("TextButton")


ScreenGui19.Parent = game.CoreGui

Frame.Parent = ScreenGui19
Frame.BackgroundColor3 = Color3.new(0,0,0)
Frame.BorderColor3 = Color3.new(1,1,1)
Frame.Position = UDim2.new(0.04,0,0.09)
Frame.Size = UDim2.new(0.2,0,0.09)
Frame.Active = true
Frame.Draggable = false

TextButton.Parent = Frame
TextButton.BackgroundColor3 = Color3.new(0,0,0)
TextButton.BackgroundTransparency = 100
TextButton.Position = UDim2.new(0.103524067, 0, 0.200333327, 0)
TextButton.TextColor3 = Color3.new(1,1,1)
TextButton.Size = UDim2.new(0.8,0.9,0.6)
TextButton.Font = Enum.Font.SourceSansLight
TextButton.FontSize = Enum.FontSize.Size14
TextButton.Text = "Give"
TextButton.TextScaled = true
TextButton.TextSize = 8
TextButton.TextWrapped = true

run = false
TextButton.MouseButton1Click:connect(function()
run = not run
game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 35
local lp = game:FindService("Players").LocalPlayer

local function gplr(String)
	local Found = {}
	local strl = String:lower()
	if strl == "all" then
		for i,v in pairs(game:FindService("Players"):GetPlayers()) do
			table.insert(Found,v)
		end
	elseif strl == "others" then
		for i,v in pairs(game:FindService("Players"):GetPlayers()) do
			if v.Name ~= lp.Name then
				table.insert(Found,v)
			end
		end 
	elseif strl == "me" then
		for i,v in pairs(game:FindService("Players"):GetPlayers()) do
			if v.Name == lp.Name then
				table.insert(Found,v)
			end
		end 
	else
		for i,v in pairs(game:FindService("Players"):GetPlayers()) do
			if v.Name:lower():sub(1, #String) == String:lower() then
				table.insert(Found,v)
			end
		end 
	end
	return Found 
end
		lp.Character.Humanoid:Clone().Parent = lp.Character
		lp.Character.Humanoid:Destroy()
		game.Workspace.CurrentCamera.CameraSubject = lp.Character.Head
	wait(0.01)
	for i,tools in pairs(game.Players.LocalPlayer.Backpack:GetDescendants()) do
		if tools:IsA("Tool") then
		end
	wait(0.1)
		repeat
			lp.Character.HumanoidRootPart.CFrame = Target.Character.HumanoidRootPart.CFrame
			Thrust.Location = Target.Character.HumanoidRootPart.Position
			game:FindService("RunService").Heartbeat:wait()
		until not Target.Character:FindFirstChild("Head")
	end

end)

--For Destroy dont clear this
local ScreenGui17 = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TextButton = Instance.new("TextButton")


ScreenGui17.Parent = game.CoreGui

Frame.Parent = ScreenGui17
Frame.BackgroundColor3 = Color3.new(0,0,0)
Frame.BorderColor3 = Color3.new(1,1,1)
Frame.Position = UDim2.new(0.3,0,0)
Frame.Size = UDim2.new(0.04,0.2,0.09)
Frame.Active = true
Frame.Draggable = false

TextButton.Parent = Frame
TextButton.BackgroundColor3 = Color3.new(0,0,0)
TextButton.BackgroundTransparency = 100
TextButton.Position = UDim2.new(0.103524067, 0, 0.200333327, 0)
TextButton.TextColor3 = Color3.new(1,1,1)
TextButton.Size = UDim2.new(0.8,0.9,0.6)
TextButton.Font = Enum.Font.SourceSansLight
TextButton.FontSize = Enum.FontSize.Size14
TextButton.Text = "<"
TextButton.TextScaled = true
TextButton.TextSize = 8
TextButton.TextWrapped = true

run = false
TextButton.MouseButton1Click:connect(function()
run = not run
ScreenGui16:Destroy()
ScreenGui17:Destroy()
ScreenGui18:Destroy()
ScreenGui19:Destroy()
ScreenGui20:Destroy()
ScreenGui21:Destroy()
end)
end)
