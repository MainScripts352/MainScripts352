local CoreGui = game:GetService("StarterGui")

CoreGui:SetCore("SendNotification", {
    Title = "Script Made By",
    Text = "GhostPlayer",
    Icon = "rbxassetid://29819383",
    Duration = 4,
})

--Speed
local ScreenTextSpeed = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TextButton = Instance.new("TextButton")
local TextBoxSpeed = Instance.new("TextBox")


ScreenTextSpeed.Parent = game.CoreGui

Frame.Parent = ScreenTextSpeed
Frame.BackgroundColor3 = Color3.new(0,0,0)
Frame.BorderColor3 = Color3.new(1,1,1)
Frame.Position = UDim2.new(0.55,0,0.03)
Frame.Size = UDim2.new(0.08,0.2,0.1)
Frame.Active = true
Frame.Draggable = false

TextBoxSpeed.Parent = Frame
TextBoxSpeed.BackgroundColor3 = Color3.new(1,1,1)
TextBoxSpeed.BackgroundTransparency = 0
TextBoxSpeed.Position = UDim2.new(0.103524067, 0, 0.200333327, 0)
TextBoxSpeed.Size = UDim2.new(0.8,0.9,0.6)
TextBoxSpeed.Font = Enum.Font.SourceSansLight
TextBoxSpeed.FontSize = Enum.FontSize.Size14
TextBoxSpeed.Text = "Speed Click"
TextBoxSpeed.TextScaled = true
TextBoxSpeed.TextSize = 8
TextBoxSpeed.TextWrapped = true

TextButton.MouseButton1Click:connect(function()
end)

--Letter
local ScreenTextLetter = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TextButton = Instance.new("TextButton")
local TextBoxLetter = Instance.new("TextBox")


ScreenTextLetter.Parent = game.CoreGui

Frame.Parent = ScreenTextLetter
Frame.BackgroundColor3 = Color3.new(0,0,0)
Frame.BorderColor3 = Color3.new(1,1,1)
Frame.Position = UDim2.new(0.47,0,0.03)
Frame.Size = UDim2.new(0.08,0.2,0.1)
Frame.Active = true
Frame.Draggable = false

TextBoxLetter.Parent = Frame
TextBoxLetter.BackgroundColor3 = Color3.new(1,1,1)
TextBoxLetter.BackgroundTransparency = 0
TextBoxLetter.Position = UDim2.new(0.103524067, 0, 0.200333327, 0)
TextBoxLetter.Size = UDim2.new(0.8,0.9,0.6)
TextBoxLetter.Font = Enum.Font.SourceSansLight
TextBoxLetter.FontSize = Enum.FontSize.Size14
TextBoxLetter.Text = "Letter Here"
TextBoxLetter.TextScaled = true
TextBoxLetter.TextSize = 8
TextBoxLetter.TextWrapped = true

TextButton.MouseButton1Click:connect(function()
end)

local CoreGui = game:GetService("StarterGui")

local Library =
   loadstring(game:HttpGet("https://raw.githubusercontent.com/preztel/AzureLibrary/master/uilib.lua", true))()

local AutoTab = Library:CreateTab("Auto Press")

AutoTab:CreateToggle(
   "Press",
   function(ssse1)
       _G.s1s1 = ssse1 or false
       while _G.s1s1 and wait(TextBoxSpeed.Text) do
           local vim = game:service("VirtualInputManager")
           vim:SendKeyEvent(true, ""..TextBoxLetter.Text, false, game)
   wait(0.1)
   local vim = game:service("VirtualInputManager")
vim:SendKeyEvent(false, ""..TextBoxLetter.Text, false, game)
end
end)
