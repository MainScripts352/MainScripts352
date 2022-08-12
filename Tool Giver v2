local CoreGui = game:GetService("StarterGui")

CoreGui:SetCore("SendNotification", {
    Title = "Script Made By",
    Text = "GhostPlayer",
    Icon = "rbxassetid://29819383",
    Duration = 2,
})

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TextBox = Instance.new("TextBox")
local TextButton1 = Instance.new("TextButton")
local TextBox1 = Instance.new("TextBox")
ScreenGui.Parent = game.CoreGui

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.new(0,0,0)
Frame.BorderColor3 = Color3.new(1,1,1)
Frame.Position = UDim2.new(0.293040276, 0, 0.491666675, 0)
Frame.Size = UDim2.new(0.2,0.2,0.5)
Frame.Active = true
Frame.Draggable = true

TextBox.Parent = Frame
TextBox.BackgroundColor3 = Color3.new(1,1,1)
TextBox.BackgroundTransparency = 0
TextBox.Position = UDim2.new(0.103524067, 0, 0.200333327, 0)
TextBox.Size = UDim2.new(0.8,0.9,0.2)
TextBox.Font = Enum.Font.SourceSansLight
TextBox.FontSize = Enum.FontSize.Size14
TextBox.Text = "Player Name"
TextBox.TextScaled = true
TextBox.TextSize = 8
TextBox.TextWrapped = true

TextBox1.Parent = Frame
TextBox1.BackgroundColor3 = Color3.new(1,1,1)
TextBox1.BackgroundTransparency = 0
TextBox1.Position = UDim2.new(0.17, 0,0.45)
TextBox1.Size = UDim2.new(0.65,0.9,0.15)
TextBox1.Font = Enum.Font.SourceSansLight
TextBox1.FontSize = Enum.FontSize.Size14
TextBox1.Text = "Tool Name"
TextBox1.TextScaled = true
TextBox1.TextSize = 8
TextBox1.TextWrapped = true

TextButton1.Parent = Frame
TextButton1.BackgroundColor3 = Color3.new(5,5,5)
TextButton1.BackgroundTransparency = 0
TextButton1.Position = UDim2.new(0.33,0,0.7)
TextButton1.Size = UDim2.new(0.33,0.9,0.12)
TextButton1.Font = Enum.Font.SourceSansLight
TextButton1.FontSize = Enum.FontSize.Size14
TextButton1.Text = "Give Tool"
TextButton1.TextScaled = true
TextButton1.TextScaled = 8
TextButton1.TextWrapped = true

TextButton1.MouseButton1Click:connect(function()
local lplayer = game:GetService('Players').LocalPlayer
 
local yeeting = false
function GetPlayer(String)
local Found = {}
local strl = String:lower()
if strl == "all" then
for i,v in pairs(game:GetService("Players"):GetPlayers()) do
table.insert(Found,v)
end
elseif strl == "others" then
for i,v in pairs(game:GetService("Players"):GetPlayers()) do
if v.Name ~= lplayer.Name then
table.insert(Found,v)
end
end 
elseif strl == "me" then
for i,v in pairs(game:GetService("Players"):GetPlayers()) do
if v.Name == lplayer.Name then
table.insert(Found,v)
end
end 
else
for i,v in pairs(game:GetService("Players"):GetPlayers()) do
if v.Name:lower():sub(1, #String) == String:lower() then
table.insert(Found,v)
end
end 
end
return Found 
end
function ahh(thing)
local asd = {'yeet','gui','yeet gui'}
local f = string.upper(asd[math.random(1,#asd)])
return f
end

local target = unpack(GetPlayer(TextBox.text)).Character
 
game:GetService'Players'.LocalPlayer.Character.HumanoidRootPart.CFrame = target.Head.CFrame;coin.Location = target.Head.Position game["Run Service"].Heartbeat:wait()
end)

TextButton1.MouseButton1Click:connect(function()
    wait(0.5)
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

local Target = gplr(TextBox.text)
	if Target[1] then
		Target = Target[1]
		Target.Character.HumanoidRootPart.CFrame = lp.Character.HumanoidRootPart.CFrame
		lp.Character.Humanoid:Clone().Parent = lp.Character
		lp.Character.Humanoid:Destroy()
		game.Workspace.CurrentCamera.CameraSubject = lp.Character.Head
	wait()
	local Target = gplr(TextBox.text)
	if Target[1] then
		Target = Target[1]
		Target.Character.HumanoidRootPart.CFrame = lp.Character.HumanoidRootPart.CFrame
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game:GetService("Players").LocalPlayer.Backpack:FindFirstChild(TextBox1.text))
local Target = gplr(TextBox.text)
	if Target[1] then
		Target = Target[1]
		Target.Character.HumanoidRootPart.CFrame = lp.Character.HumanoidRootPart.CFrame
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game:GetService("Players").LocalPlayer.Backpack:FindFirstChild(TextBox1.text))
local Target = gplr(TextBox.text)
	if Target[1] then
		Target = Target[1]
		Target.Character.HumanoidRootPart.CFrame = lp.Character.HumanoidRootPart.CFrame
		wait(0.3)
		local Target = gplr(TextBox.text)
	if Target[1] then
		Target = Target[1]
		Target.Character.HumanoidRootPart.CFrame = lp.Character.HumanoidRootPart.CFrame
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game:GetService("Players").LocalPlayer.Backpack:FindFirstChild(TextBox1.text))
end
end
end
end
end
end)
