local CoreGui = game:GetService("StarterGui")

CoreGui:SetCore("SendNotification", {
    Title = "Script Made By",
    Text = "GhostPlayer",
    Icon = "rbxassetid://29819383",
    Duration = 2.5,
})

local AgeGui = Instance.new("ScreenGui")
local AgeFrame = Instance.new("Frame")
local Scrolling = Instance.new("ScrollingFrame")
local Ages = Instance.new("TextButton")
local Title = Instance.new("TextButton")

AgeGui.Parent = game.CoreGui

AgeFrame.Parent = AgeGui
AgeFrame.BackgroundColor3 = Color3.new(0,0,0)
AgeFrame.BorderColor3 = Color3.new(1,1,1)
AgeFrame.Position = UDim2.new(0.25,0,0)
AgeFrame.Size = UDim2.new(0.3,0,0.8)
AgeFrame.Active = true
AgeFrame.Draggable = true
AgeFrame.Transparency = 0.3

Title.Parent = AgeFrame
Title.Position = UDim2.new(0,0,0.03)
Title.BackgroundTransparency = 1
Title.TextColor3 = Color3.new(1,1,1)
Title.Size = UDim2.new(1,0,0.0)
Title.Font = Enum.Font.SourceSansLight
Title.FontSize = Enum.FontSize.Size14
Title.Text = "Account Age Detector"
Title.TextScaled = false
Title.TextSize = 18
Title.TextWrapped = true

Scrolling.Parent = AgeFrame
Scrolling.BackgroundColor3 = Color3.new(0,0,0)
Scrolling.BackgroundTransparency = 0
Scrolling.BorderColor3 = Color3.new(1,1,1)
Scrolling.BorderSizePixel = 1
Scrolling.Position = UDim2.new(0.05,0,0.07)
Scrolling.Size = UDim2.new(0.9,0,0.87)
Scrolling.ScrollBarThickness = 1
Scrolling.Transparency = 1

Ages.Parent = Scrolling
Ages.BackgroundColor3 = Color3.new(0,0,0)
Ages.BackgroundTransparency = 0
Ages.BorderColor3 = Color3.new(1,1,1)
Ages.BorderSizePixel = 1
Ages.Transparency = 0
Ages.Position = UDim2.new(0,0,0)
Ages.TextColor3 = Color3.new(1,1,1)
Ages.Size = UDim2.new(1,0,1)
Ages.Font = Enum.Font.SourceSansLight
Ages.FontSize = Enum.FontSize.Size14
Ages.Text = "Message Here"
Ages.TextScaled = false
Ages.TextSize = 18
Ages.TextWrapped = true
Ages.TextXAlignment = Enum.TextXAlignment.Left
Ages.TextYAlignment = Enum.TextYAlignment.Top

String = ""
for _, v in next, (game.Players:GetChildren()) do
 Ages.Text = String..""..v.Name.." = ["..v.AccountAge.." Days]                                                                       "
 String = ""..Ages.Text
end
