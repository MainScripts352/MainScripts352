local CoreGui = game:GetService("StarterGui")

CoreGui:SetCore("SendNotification", {
    Title = "Script Made By",
    Text = "GhostPlayer",
    Icon = "rbxassetid://29819383",
    Duration = 10,
})

setting = settings().Network
local Effect = Instance.new("ColorCorrectionEffect")
Effect.Parent = game.Lighting
Effect.Saturation = -1
Effect.Brightness = 0
Effect.Contrast = 0
toggle = false

Effect.Enabled = false
function onKeyPress(inputObject, gameProcessedEvent)
	if inputObject.KeyCode == Enum.KeyCode.E then	
		if toggle == false then
			setting.IncomingReplicationLag = 1000
			Effect.Enabled = true
			toggle = true
		else
			setting.IncomingReplicationLag = 0
			Effect.Enabled = false
			toggle = false
		end

	end
end

game:GetService("UserInputService").InputBegan:connect(onKeyPress)

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TextButton = Instance.new("TextButton")


ScreenGui.Parent = game.CoreGui

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.new(255,250,0)
Frame.BorderColor3 = Color3.new(255,250,0)
Frame.Position = UDim2.new(0.001,0,0.2)
Frame.Size = UDim2.new(0.08,0.08,0.08)
Frame.Active = true
Frame.Draggable = true

TextButton.Parent = Frame
TextButton.BackgroundColor3 = Color3.new(0,0,0)
TextButton.BackgroundTransparency = 0.0000000001
TextButton.Position = UDim2.new(0.103524067, 0, 0.200333327, 0)
TextButton.TextColor3 = Color3.new(1,1,1)
TextButton.Size = UDim2.new(0.8,0.9,0.6)
TextButton.Font = Enum.Font.SourceSansLight
TextButton.FontSize = Enum.FontSize.Size14
TextButton.Text = "Time Stop"
TextButton.TextScaled = true
TextButton.TextSize = 8
TextButton.TextWrapped = true

run = false
TextButton.MouseButton1Click:connect(function()
run = not run
local vim = game:service("VirtualInputManager")
vim:SendKeyEvent(true, "E", false, game)
wait()
local vim = game:service("VirtualInputManager")
vim:SendKeyEvent(false, "E", false, game)
end)
