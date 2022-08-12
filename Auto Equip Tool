local CoreGui = game:GetService("StarterGui")

CoreGui:SetCore("SendNotification", {
    Title = "Script Made By",
    Text = "GhostPlayer",
    Icon = "rbxassetid://29819383",
    Duration = 2.5,
})
local DropGUI = Instance.new("ScreenGui")
local main = Instance.new("Frame")
local DropTool = Instance.new("TextButton")
local Equip = Instance.new("TextButton")
local Version = Instance.new("TextButton")
local Cred = Instance.new("TextButton")
local TextButton = Instance.new("TextBox")

DropGUI.Name = "Drop GUI"
DropGUI.Parent = game.CoreGui
DropGUI.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

main.Name = "main"
main.Parent = DropGUI
main.BackgroundColor3 = Color3.fromRGB(205,0,0)
main.Position = UDim2.new(0.0809101239, 0, 0.203790441, 0)
main.Size = UDim2.new(0, 150, 0, 128)
main.Active = true
main.Draggable = true

DropTool.Name = "Drop Tool"
DropTool.Parent = main
DropTool.BackgroundColor3 = Color3.fromRGB(300,300,300)
DropTool.Position = UDim2.new(0.0597826242, 0, 0.5, 0)
DropTool.Size = UDim2.new(0, 55, 0, 50)
DropTool.Font = Enum.Font.SourceSans
DropTool.Text = "Enable Auto Equip"
DropTool.TextColor3 = Color3.fromRGB(0, 0, 0)
DropTool.TextScaled = true
DropTool.TextSize = 14.000
DropTool.TextWrapped = true
DropTool.MouseButton1Down:Connect(function()
getgenv().autokill = true
 
if getgenv().autokill then
task.spawn(function()
while getgenv().autokill do
for I, V in pairs(game.Players:GetChildren()) do
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game:GetService("Players").LocalPlayer.Backpack:FindFirstChild(TextButton.Text))
wait()
end
end
end)
end
end)

Equip.Name = "Equip"
Equip.Parent = main
Equip.BackgroundColor3 = Color3.fromRGB(300,300,300)
Equip.Position = UDim2.new(0.55251956, 0, 0.5, 0)
Equip.Size = UDim2.new(0, 58, 0, 50)
Equip.Font = Enum.Font.SourceSans
Equip.Text = "Disable Auto Equip"
Equip.TextColor3 = Color3.fromRGB(0, 0, 0)
Equip.TextScaled = true
Equip.TextSize = 14.000
Equip.TextWrapped = true
Equip.MouseButton1Down:Connect(function()
getgenv().autokill = false
getgenv().autokill = false
getgenv().autokill = false
getgenv().autokill = false
getgenv().autokill = false
getgenv().autokill = false
getgenv().autokill = false
getgenv().autokill = false
getgenv().autokill = false
end)



Version.Name = "Version"
Version.Parent = main
Version.BackgroundColor3 = Color3.fromRGB(250,255,0)
Version.Position = UDim2.new(0, 0, 0.999885917, 0)
Version.Size = UDim2.new(0, 151, 0, 34)
Version.Font = Enum.Font.SourceSans
Version.Text = ""
Version.TextColor3 = Color3.fromRGB(0, 0, 0)
Version.TextScaled = true
Version.TextSize = 14.000
Version.TextWrapped = true

Cred.Name = "Cred"
Cred.Parent = main
Cred.BackgroundColor3 = Color3.fromRGB(250,255,0)
Cred.Position = UDim2.new(0, 0, -0.266169071, 0)
Cred.Size = UDim2.new(0, 151, 0, 34)
Cred.Font = Enum.Font.SourceSans
Cred.Text = "Auto Equip Tool"
Cred.TextColor3 = Color3.fromRGB(0, 0, 0)
Cred.TextSize = 14.000
Cred.TextWrapped = true

TextButton.Parent = main
TextButton.BackgroundColor3 = Color3.new(1,1,1)
TextButton.BackgroundTransparency = 0
TextButton.Position = UDim2.new(0.1, 0, 0.1, 0)
TextButton.TextColor3 = Color3.new(0,0,0)
TextButton.Size = UDim2.new(0.8,0.2,0.3)
TextButton.Font = Enum.Font.SourceSansLight
TextButton.FontSize = Enum.FontSize.Size14
TextButton.Text = "Name Of Tool Here"
TextButton.TextScaled = true
TextButton.TextSize = 8
TextButton.TextWrapped = true
