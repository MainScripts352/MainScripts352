local CoreGui = game:GetService("StarterGui")

CoreGui:SetCore("SendNotification", {
    Title = "Script Made By",
    Text = "GhostPlayer",
    Icon = "rbxassetid://29819383",
    Duration = 2.5,
})

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local title = Instance.new("TextLabel")
local copy = Instance.new("TextButton")
local pos = Instance.new("TextBox")
local find = Instance.new("TextButton")
local tp = Instance.new("TextButton")
--Properties:

ScreenGui.Parent = game.CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(0,0,0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.32,0,0.08)
Frame.Size = UDim2.new(0, 280, 0.3, 100)
Frame.Active = true

title.Name = "title"
title.Parent = Frame
title.BackgroundColor3 = Color3.fromRGB(255,0,0)
title.BorderSizePixel = 0
title.Size = UDim2.new(0, 280, 0, 50)
title.Font = Enum.Font.GothamBold
title.Text = "Position Reader"
title.TextColor3 = Color3.fromRGB(255, 255, 255)
title.TextSize = 30.000
title.TextWrapped = true

copy.Name = "copy"
copy.Parent = Frame
copy.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
copy.BorderSizePixel = 0
copy.Position = UDim2.new(0.66,0,0.635)
copy.Size = UDim2.new(0,70,0,47)
copy.Font = Enum.Font.GothamSemibold
copy.Text = "Copy"
copy.TextColor3 = Color3.fromRGB(255, 255, 255)
copy.TextSize = 20.000

pos.Name = "pos"
pos.Parent = Frame
pos.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
pos.BorderSizePixel = 0
pos.Position = UDim2.new(0.0904392749, 0, 0.305825233, 0)
pos.Size = UDim2.new(0, 230, 0, 50)
pos.Font = Enum.Font.GothamSemibold
pos.Text = ""
pos.TextColor3 = Color3.fromRGB(255, 255, 255)
pos.TextSize = 14.000
pos.TextWrapped = true

tp.Name = "copy"
tp.Parent = Frame
tp.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
tp.BorderSizePixel = 0
tp.Position = UDim2.new(0.37,0,0.635)
tp.Size = UDim2.new(0,70,0,47)
tp.Font = Enum.Font.GothamSemibold
tp.Text = "Notify"
tp.TextColor3 = Color3.fromRGB(255, 255, 255)
tp.TextSize = 20.000

tp.MouseButton1Click:Connect(function()
    game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(pos.text)
end)

find.Name = "find"
find.Parent = Frame
find.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
find.BorderSizePixel = 0
find.Position = UDim2.new(0.0904392898, 0, 0.635922313, 0)
find.Size = UDim2.new(0, 70, 0, 47)
find.Font = Enum.Font.GothamSemibold
find.Text = "Read"
find.TextColor3 = Color3.fromRGB(255, 255, 255)
find.TextSize = 20.000

-- Scripts:

local function UMTQ_fake_script() -- copy.LocalScript 
	local script = Instance.new('LocalScript', copy)

	script.Parent.MouseButton1Click:Connect(function()
		setclipboard(script.Parent.Parent.pos.Text)
	end)
end
coroutine.wrap(UMTQ_fake_script)()
local function KJAYG_fake_script() -- Frame.Dragify 
	local script = Instance.new('LocalScript', Frame)

	local UIS = game:GetService("UserInputService")
	function dragify(Frame)
	    dragToggle = nil
	    local dragSpeed = 0
	    dragInput = nil
	    dragStart = nil
	    local dragPos = nil
	    function updateInput(input)
	        local Delta = input.Position - dragStart
	        local Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + Delta.X, startPos.Y.Scale, startPos.Y.Offset + Delta.Y)
	        game:GetService("TweenService"):Create(Frame, TweenInfo.new(0.25), {Position = Position}):Play()
	    end
	    Frame.InputBegan:Connect(function(input)
	        if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) and UIS:GetFocusedTextBox() == nil then
	            dragToggle = true
	            dragStart = input.Position
	            startPos = Frame.Position
	            input.Changed:Connect(function()
	                if input.UserInputState == Enum.UserInputState.End then
	                    dragToggle = false
	                end
	            end)
	        end
	    end)
	    Frame.InputChanged:Connect(function(input)
	        if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
	            dragInput = input
	        end
	    end)
	    game:GetService("UserInputService").InputChanged:Connect(function(input)
	        if input == dragInput and dragToggle then
	            updateInput(input)
	        end
	    end)
	end
	
	dragify(script.Parent)
end
coroutine.wrap(KJAYG_fake_script)()

local function EKBNYI_fake_script() -- find.LocalScript 
	local script = Instance.new('LocalScript', find)

	script.Parent.MouseButton1Down:Connect(function()
		script.Parent.Parent.pos.Text = tostring(game.Players.LocalPlayer.Character.HumanoidRootPart.Position)
		end)
end
coroutine.wrap(EKBNYI_fake_script)()

tp.MouseButton1Click:Connect(function()
local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local Text = Instance.new("TextButton")


ScreenGui.Parent = game.CoreGui

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.new(0,0,0)
Frame.BorderColor3 = Color3.new(0,0,0)
Frame.Position = UDim2.new(0.00001,0.0009,0)
Frame.Size = UDim2.new(2,0.2,0.08)
Frame.Active = true
Frame.Draggable = false

Text.Parent = Frame
Text.BackgroundColor3 = Color3.new(0,0,0)
Text.BackgroundTransparency = 100
Text.Position = UDim2.new(0,0,0.1)
Text.Size = UDim2.new(0.5,0.9,0.6)
Text.TextColor3 = Color3.new(1,1,1)
Text.Text = tostring(game.Players.LocalPlayer.Character.HumanoidRootPart.Position)
Text.TextScaled = true
Text.TextSize = 8
Text.TextWrapped = true
wait(5)
ScreenGui:Destroy()
end)
