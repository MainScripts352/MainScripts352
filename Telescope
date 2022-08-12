local CoreGui = game:GetService("StarterGui")

CoreGui:SetCore("SendNotification", {
    Title = "Script Made By",
    Text = "GhostPlayer",
    Icon = "rbxassetid://29819383",
    Duration = 2.5,
})

mouse = game.Players.LocalPlayer:GetMouse()
tool = Instance.new("Tool")
tool.RequiresHandle = false
tool.Name = ("Telescope 🔭")
tool.Activated:Connect(function()
game.Players.LocalPlayer.Character.Humanoid.MaxHealth = math.huge
game.Players.LocalPlayer.Character.Humanoid.Health = math.huge
do wait()
game.Players.LocalPlayer.Character.Humanoid.RootPart.Anchored = true

local player = game.Players.LocalPlayer
 
player.CameraMaxZoomDistance = 0
player.CameraMinZoomDistance = -1

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TextButton = Instance.new("TextLabel")
local TextButton1 = Instance.new("TextLabel")
local TextButton2 = Instance.new("TextLabel")
local TextButton3 = Instance.new("TextBox")
local TextButton4 = Instance.new("TextButton")
local TextButto = Instance.new("TextLabel")
local TextButton5 = Instance.new("TextButton")
ScreenGui.Parent = game.CoreGui

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.new(0,0,0)
Frame.BorderColor3 = Color3.new(0,0,0)
Frame.BorderSizePixel = 1
Frame.Position = UDim2.new(0.0001,0,0)
Frame.Size = UDim2.new(1,0.2,0.1)
Frame.Active = true
Frame.Draggable = false

TextButto.Parent = Frame
TextButto.BackgroundColor3 = Color3.new(0,0,0)
TextButto.BackgroundTransparency = 0
TextButto.BorderSizePixel = 0
TextButto.Position = UDim2.new(0.0001,0,-1.3)
TextButto.TextColor3 = Color3.new(0,0,0)
TextButto.Size = UDim2.new(1,0,1.3)
TextButto.Font = Enum.Font.SourceSansLight
TextButto.FontSize = Enum.FontSize.Size14
TextButto.Text = ""
TextButto.TextScaled = true
TextButto.TextSize = 8
TextButto.TextWrapped = true

TextButton.Parent = Frame
TextButton.BackgroundColor3 = Color3.new(0,0,0)
TextButton.BorderSizePixel = 1
TextButton.BorderColor3 = Color3.new(0,0,0)
TextButton.BackgroundTransparency = 0
TextButton.Position = UDim2.new(0,0,1)
TextButton.TextColor3 = Color3.new(0,0,0)
TextButton.Size = UDim2.new(0.2,0.9,9)
TextButton.Font = Enum.Font.SourceSansLight
TextButton.FontSize = Enum.FontSize.Size14
TextButton.Text = ""
TextButton.TextScaled = true
TextButton.TextSize = 8
TextButton.TextWrapped = true

TextButton1.Parent = Frame
TextButton1.BackgroundColor3 = Color3.new(0,0,0)
TextButton1.BorderSizePixel = 1
TextButton1.BorderColor3 = Color3.new(0,0,0)
TextButton1.BackgroundTransparency = 0
TextButton1.Position = UDim2.new(0.75,0,1)
TextButton1.TextColor3 = Color3.new(0,0,0)
TextButton1.Size = UDim2.new(0.3,0.9,9)
TextButton1.Font = Enum.Font.SourceSansLight
TextButton1.FontSize = Enum.FontSize.Size14
TextButton1.Text = ""
TextButton1.TextScaled = true
TextButton1.TextSize = 8
TextButton1.TextWrapped = true

TextButton2.Parent = Frame
TextButton2.BackgroundColor3 = Color3.new(0,0,0)
TextButton2.BorderSizePixel = 1
TextButton2.BorderColor3 = Color3.new(0,0,0)
TextButton2.BackgroundTransparency = 0
TextButton2.Position = UDim2.new(0.1,0,8)
TextButton2.TextColor3 = Color3.new(0,0,0)
TextButton2.Size = UDim2.new(1,0.9,2)
TextButton2.Font = Enum.Font.SourceSansLight
TextButton2.FontSize = Enum.FontSize.Size14
TextButton2.Text = ""
TextButton2.TextScaled = true
TextButton2.TextSize = 8
TextButton2.TextWrapped = true

TextButton3.Parent = TextButton1
TextButton3.BackgroundColor3 = Color3.new(1,1,1)
TextButton3.BackgroundTransparency = 0
TextButton3.Position = UDim2.new(0.2,0,0.4)
TextButton3.TextColor3 = Color3.new(0,0,0)
TextButton3.Size = UDim2.new(0.5,0,0.1)
TextButton3.Font = Enum.Font.SourceSansLight
TextButton3.FontSize = Enum.FontSize.Size14
TextButton3.Text = "FieldOfView"
TextButton3.TextScaled = true
TextButton3.TextSize = 8
TextButton3.TextWrapped = true

TextButton4.Parent = TextButton1
TextButton4.BackgroundColor3 = Color3.new(1,1,1)
TextButton4.BackgroundTransparency = 0
TextButton4.Position = UDim2.new(0.3,0,0.52)
TextButton4.TextColor3 = Color3.new(0,0,0)
TextButton4.Size = UDim2.new(0.3,0,0.1)
TextButton4.Font = Enum.Font.SourceSansLight
TextButton4.FontSize = Enum.FontSize.Size14
TextButton4.Text = "Set"
TextButton4.TextScaled = true
TextButton4.TextSize = 8
TextButton4.TextWrapped = true

TextButton4.MouseButton1Click:connect(function()
workspace.CurrentCamera.FieldOfView = TextButton3.text
end)

TextButton5.Parent = TextButton2
TextButton5.BackgroundColor3 = Color3.new(8,0,0)
TextButton5.BackgroundTransparency = 0
TextButton5.Position = UDim2.new(0.1,0,0.2)
TextButton5.TextColor3 = Color3.new(0,0,0)
TextButton5.Size = UDim2.new(0.08,0,0.5)
TextButton5.Font = Enum.Font.SourceSansLight
TextButton5.FontSize = Enum.FontSize.Size14
TextButton5.Text = "Exit"
TextButton5.TextScaled = true
TextButton5.TextSize = 8
TextButton5.TextWrapped = true

TextButton5.MouseButton1Click:connect(function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.Anchored = false
local player = game.Players.LocalPlayer
player.CameraMaxZoomDistance = 1000
player.CameraMinZoomDistance = -1
workspace.CurrentCamera.FieldOfView = 70
ScreenGui:Destroy()
end)
wait()
game.Players.LocalPlayer.Character.Humanoid:UnequipTools()
end
end)		
tool.Parent = game.Players.LocalPlayer.Backpack
