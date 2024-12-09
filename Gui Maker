local CoreGui = game:GetService("StarterGui")

CoreGui:SetCore("SendNotification", {
    Title = "Script Made By",
    Text = "GhostPlayer",
    Icon = "rbxassetid://29819383",
    Duration = 2.5,
})

--Admin Detector in Server
loadstring(game:HttpGet('https://raw.githubusercontent.com/MainScripts352/MainScripts352/main/Admin'))()
--

local UIButtonName = nil --(The UIButton name was clicked)
local RequestTextBoxText = nil --(The Text Of the Request Textbox)
local ColoringType = nil --(Coloring UI by type textcolor,bgcolor,etc)
local RequestPositionText = nil --(The Position of the Request Position function)


---Source Code Gui
local SourceCodeGui = Instance.new("ScreenGui")
local SourceCodeScrolling = Instance.new("ScrollingFrame")
local SourceCode = Instance.new("TextBox")

SourceCodeGui.Parent = game.CoreGui

SourceCodeScrolling.Parent = SourceCodeGui
SourceCodeScrolling.BackgroundColor3 = Color3.new(0,0,0)
SourceCodeScrolling.BorderSizePixel = 0
SourceCodeScrolling.Position = UDim2.new(0, 0, 0, 0)
SourceCodeScrolling.Size = UDim2.new(0.25, 0, 0.99, 0)
SourceCodeScrolling.CanvasSize = UDim2.new(10, 0, 100, 0)
SourceCodeScrolling.ScrollBarThickness = 3
SourceCodeScrolling.Draggable = true
SourceCodeScrolling.Visible = false

SourceCode.Parent = SourceCodeScrolling
SourceCode.BackgroundColor3 = Color3.new(1,1,1)
SourceCode.BackgroundTransparency = 0
SourceCode.BorderColor3 = Color3.new(0,0,0)
SourceCode.Position = UDim2.new(0, 0, 0, 0)
SourceCode.TextColor3 = Color3.new(0,0,0)
SourceCode.Size = UDim2.new(1,0,1,0)
SourceCode.Font = Enum.Font.SourceSansBold
SourceCode.FontSize = Enum.FontSize.Size14
SourceCode.Text = ""
SourceCode.TextScaled = false
SourceCode.TextSize = 14.00
SourceCode.TextWrapped = false
SourceCode.MultiLine = true
SourceCode.ClearTextOnFocus = false
SourceCode.TextXAlignment = Enum.TextXAlignment.Left
SourceCode.TextYAlignment = Enum.TextYAlignment.Top
SourceCode.Draggable = false
---








--UIColor Gui
local UIColorGui = Instance.new("ScreenGui")
local UIColorFrame = Instance.new("ScrollingFrame")

UIColorGui.Parent = game.CoreGui

UIColorFrame.Parent = UIColorGui
UIColorFrame.BackgroundColor3 = Color3.new(1,1,1)
UIColorFrame.BorderColor3 = Color3.new(0,0,0)
UIColorFrame.Position = UDim2.new(0.6,0,0)
UIColorFrame.Size = UDim2.new(0.377,0,0.2)
UIColorFrame.CanvasSize = UDim2.new(1000,0,0,0)
UIColorFrame.ScrollBarThickness = 0
UIColorFrame.Draggable = false
UIColorFrame.BackgroundTransparency = 1
UIColorFrame.Visible = false
---


--Add UIColor Button function
function AddUIColorButton(pos,name,bgcolor,textcolor,color)
 local UIColorButton = Instance.new("TextButton")
 UIColorButton.Parent = UIColorFrame
 UIColorButton.BackgroundColor3 = bgcolor
 UIColorButton.BackgroundTransparency = 0
 UIColorButton.BorderColor3 = Color3.new(0,0,0)
 UIColorButton.Position = UDim2.new(pos,0,0)
 UIColorButton.TextColor3 = textcolor
 UIColorButton.Size = UDim2.new(0.0001,0,1.1,0)
 UIColorButton.Font = Enum.Font.SourceSansBold
 UIColorButton.FontSize = Enum.FontSize.Size14
 UIColorButton.Text = name
 UIColorButton.TextScaled = false
 UIColorButton.TextSize = 14.00
 UIColorButton.TextWrapped = true
 UIColorButton.Draggable = false

 UIColorButton.MouseButton1Click:Connect(function()
 UIColorFrame.Visible = false
SourceCode.Text = SourceCode.Text..""..UIButtonName..""..ColoringType..""..color.."\
"
 end)
end
---



---Add UIColor Button
AddUIColorButton("0","Black",Color3.fromRGB(17,17,17),Color3.fromRGB(242,243,243),"Color3.fromRGB(17,17,17)")
AddUIColorButton("0.0001","White",Color3.fromRGB(242,243,243),Color3.fromRGB(17,17,17),"Color3.fromRGB(242,243,243)")
AddUIColorButton("0.0002","Grey",Color3.fromRGB(161,165,162),Color3.fromRGB(17,17,17),"Color3.fromRGB(161,165,162)")
AddUIColorButton("0.0003","Really Red",Color3.fromRGB(255,0,0),Color3.fromRGB(17,17,17),"Color3.fromRGB(255,0,0)")
AddUIColorButton("0.0004","Really Blue",Color3.fromRGB(0,0,255),Color3.fromRGB(17,17,17),"Color3.fromRGB(0,0,255)")
AddUIColorButton("0.0005","New Yeller",Color3.fromRGB(255,255,0),Color3.fromRGB(17,17,17),"Color3.fromRGB(255,255,0)")
AddUIColorButton("0.0006","Lime Green",Color3.fromRGB(0,255,0),Color3.fromRGB(17,17,17),"Color3.fromRGB(0,255,0)")
AddUIColorButton("0.0007","Hot Pink",Color3.fromRGB(255,0,191),Color3.fromRGB(17,17,17),"Color3.fromRGB(255,0,191)")
AddUIColorButton("0.0008","Royal Purple",Color3.fromRGB(98,37,209),Color3.fromRGB(17,17,17),"Color3.fromRGB(98,37,209)")
AddUIColorButton("0.0009","Tootpaste",Color3.fromRGB(0,255,255),Color3.fromRGB(17,17,17),"Color3.fromRGB(0,255,255)")
AddUIColorButton("0.0010","Deep orange",Color3.fromRGB(255,175,0),Color3.fromRGB(17,17,17),"Color3.fromRGB(255,175,0)")
AddUIColorButton("0.0011","Pink",Color3.fromRGB(255,102,204),Color3.fromRGB(17,17,17),"Color3.fromRGB(255,102,204)")
AddUIColorButton("0.0012","Magenta",Color3.fromRGB(170,0,170),Color3.fromRGB(17,17,17),"Color3.fromRGB(170,0,170)")
AddUIColorButton("0.0013","CGA Brown",Color3.fromRGB(170,85,0),Color3.fromRGB(17,17,17),"Color3.fromRGB(170,85,0)")
AddUIColorButton("0.0014","Cyan",Color3.fromRGB(4,175,236),Color3.fromRGB(17,17,17),"Color3.fromRGB(4,175,236)")
AddUIColorButton("0.0015","Deep blue",Color3.fromRGB(33,84,185),Color3.fromRGB(17,17,17),"Color3.fromRGB(33,84,185)")
AddUIColorButton("0.0016","Navy Blue",Color3.fromRGB(0,32,96),Color3.fromRGB(17,17,17),"Color3.fromRGB(0,32,96)")
AddUIColorButton("0.0017","Teal",Color3.fromRGB(18,238,212),Color3.fromRGB(17,17,17),"Color3.fromRGB(18,238,212)")
AddUIColorButton("0.0018","Camo",Color3.fromRGB(58,125,21),Color3.fromRGB(17,17,17),"Color3.fromRGB(58,125,21)")
AddUIColorButton("0.0019","Lavender",Color3.fromRGB(140,91,159),Color3.fromRGB(17,17,17),"Color3.fromRGB(140,91,159)")
AddUIColorButton("0.0020","Pastel light blue",Color3.fromRGB(175,221,255),Color3.fromRGB(17,17,17),"Color3.fromRGB(175,221,255)")
AddUIColorButton("0.0021","Pastel orange",Color3.fromRGB(255,201,201),Color3.fromRGB(17,17,17),"Color3.fromRGB(255,201,201)")
AddUIColorButton("0.0022","Pastel violet",Color3.fromRGB(177,167,255),Color3.fromRGB(17,17,17),"Color3.fromRGB(177,167,255)")
AddUIColorButton("0.0023","Pastel blue-green",Color3.fromRGB(159,243,233),Color3.fromRGB(17,17,17),"Color3.fromRGB(159,243,233)")
AddUIColorButton("0.0024","Pastel yellow",Color3.fromRGB(255,255,204),Color3.fromRGB(17,17,17),"Color3.fromRGB(255,255,204)")
AddUIColorButton("0.0025","Pastel brown",Color3.fromRGB(255,204,153),Color3.fromRGB(17,17,17),"Color3.fromRGB(255,204,153)")
AddUIColorButton("0.0026","Olive",Color3.fromRGB(193,190,66),Color3.fromRGB(17,17,17),"Color3.fromRGB(193,190,66)")
AddUIColorButton("0.0027","Dusty rose",Color3.fromRGB(163,75,75),Color3.fromRGB(17,17,17),"Color3.fromRGB(163,75,75)")
AddUIColorButton("0.0028","Mid gray",Color3.fromRGB(205,205,205),Color3.fromRGB(17,17,17),"Color3.fromRGB(205,205,205)")
AddUIColorButton("0.0029","Institutional white",Color3.fromRGB(248,248,248),Color3.fromRGB(17,17,17),"Color3.fromRGB(248,248,248)")
AddUIColorButton("0.0030","Burnt Sienna",Color3.fromRGB(106,57,9),Color3.fromRGB(17,17,17),"Color3.fromRGB(106,57,9)")
AddUIColorButton("0.0031","Dark taupe",Color3.fromRGB(90,76,66),Color3.fromRGB(17,17,17),"Color3.fromRGB(90,76,66)")
AddUIColorButton("0.0032","Flint",Color3.fromRGB(105,102,92),Color3.fromRGB(17,17,17),"Color3.fromRGB(105,102,92)")
AddUIColorButton("0.0033","Bronze",Color3.fromRGB(126,104,63),Color3.fromRGB(17,17,17),"Color3.fromRGB(126,104,63)")
AddUIColorButton("0.0034","Dirt brown",Color3.fromRGB(86,66,54),Color3.fromRGB(17,17,17),"Color3.fromRGB(86,66,54)")
AddUIColorButton("0.0035","Copper",Color3.fromRGB(150,103,102),Color3.fromRGB(17,17,17),"Color3.fromRGB(150,103,102)")
AddUIColorButton("0.0036","Linen",Color3.fromRGB(175,148,131),Color3.fromRGB(17,17,17),"Color3.fromRGB(175,148,131)")
AddUIColorButton("0.0037","Cloudy grey",Color3.fromRGB(171,168,158),Color3.fromRGB(17,17,17),"Color3.fromRGB(171,168,158)")
AddUIColorButton("0.0038","Oyster",Color3.fromRGB(187,179,178),Color3.fromRGB(17,17,17),"Color3.fromRGB(187,179,178)")
AddUIColorButton("0.0039","Beige",Color3.fromRGB(202,191,163),Color3.fromRGB(17,17,17),"Color3.fromRGB(202,191,163)")
AddUIColorButton("0.0040","Burlap",Color3.fromRGB(199,172,120),Color3.fromRGB(17,17,17),"Color3.fromRGB(199,172,120)")
AddUIColorButton("0.0041","Cork",Color3.fromRGB(188,155,93),Color3.fromRGB(17,17,17),"Color3.fromRGB(188,155,93)")
AddUIColorButton("0.0042","Burgundy",Color3.fromRGB(136,62,62),Color3.fromRGB(17,17,17),"Color3.fromRGB(136,62,62)")
AddUIColorButton("0.0043","Seashell",Color3.fromRGB(233,218,218),Color3.fromRGB(17,17,17),"Color3.fromRGB(233,218,218)")
AddUIColorButton("0.0044","Sunrise",Color3.fromRGB(212,144,189),Color3.fromRGB(17,17,17),"Color3.fromRGB(212,144,189)")
AddUIColorButton("0.0045","Buttermilk",Color3.fromRGB(254,243,187),Color3.fromRGB(17,17,17),"Color3.fromRGB(254,243,187)")
AddUIColorButton("0.0046","Cocoa",Color3.fromRGB(86,36,36),Color3.fromRGB(17,17,17),"Color3.fromRGB(86,36,36)")
AddUIColorButton("0.0047","Terra Cotta",Color3.fromRGB(190,104,98),Color3.fromRGB(17,17,17),"Color3.fromRGB(190,104,98)")
AddUIColorButton("0.0048","Salmon",Color3.fromRGB(255,148,148),Color3.fromRGB(17,17,17),"Color3.fromRGB(255,148,148)")
AddUIColorButton("0.0049","Presimmon",Color3.fromRGB(255,89,89),Color3.fromRGB(17,17,17),"Color3.fromRGB(255,89,89)")
AddUIColorButton("0.0050","Crimson",Color3.fromRGB(151,0,0),Color3.fromRGB(17,17,17),"Color3.fromRGB(151,0,0)")
AddUIColorButton("0.0051","Electric blue",Color3.fromRGB(9,137,207),Color3.fromRGB(17,17,17),"Color3.fromRGB(9,137,207)")
AddUIColorButton("0.0052","Forrest green",Color3.fromRGB(31,128,29),Color3.fromRGB(17,17,17),"Color3.fromRGB(31,128,29)")
AddUIColorButton("0.0053","Dark indigo",Color3.fromRGB(61,21,133),Color3.fromRGB(17,17,17),"Color3.fromRGB(61,21,133)")
AddUIColorButton("0.0054","Lapis",Color3.fromRGB(16,42,220),Color3.fromRGB(17,17,17),"Color3.fromRGB(16,42,220)")
AddUIColorButton("0.0055","Strom blue",Color3.fromRGB(51,88,130),Color3.fromRGB(17,17,17),"Color3.fromRGB(51,88,130)")
AddUIColorButton("0.0056","Steel blue",Color3.fromRGB(82,124,174),Color3.fromRGB(17,17,17),"Color3.fromRGB(82,124,174)")
AddUIColorButton("0.0057","Dark blue",Color3.fromRGB(0,16,176),Color3.fromRGB(17,17,17),"Color3.fromRGB(0,16,176)")
AddUIColorButton("0.0058","Smoky grey",Color3.fromRGB(91,93,105),Color3.fromRGB(17,17,17),"Color3.fromRGB(91,93,105)")
AddUIColorButton("0.0059","Medium lilac",Color3.fromRGB(52,43,117),Color3.fromRGB(17,17,17),"Color3.fromRGB(52,43,117)")
AddUIColorButton("0.0060","Dove blue",Color3.fromRGB(125,187,221),Color3.fromRGB(17,17,17),"Color3.fromRGB(125,187,221)")
AddUIColorButton("0.0061","Medium Royal blue",Color3.fromRGB(108,129,183),Color3.fromRGB(17,17,17),"Color3.fromRGB(108,129,183)")
AddUIColorButton("0.0062","Light Royal blue",Color3.fromRGB(159,195,233),Color3.fromRGB(17,17,17),"Color3.fromRGB(159,195,233)")
AddUIColorButton("0.0063","Turquoise",Color3.fromRGB(121,181,181),Color3.fromRGB(17,17,17),"Color3.fromRGB(121,181,181)")
AddUIColorButton("0.0064","Light stone grey",Color3.fromRGB(229,228,223),Color3.fromRGB(17,17,17),"Color3.fromRGB(229,228,223)")
AddUIColorButton("0.0065","Dark stone grey",Color3.fromRGB(99,95,98),Color3.fromRGB(17,17,17),"Color3.fromRGB(99,95,98)")
AddUIColorButton("0.0066","Medium stone grey",Color3.fromRGB(163,162,165),Color3.fromRGB(17,17,17),"Color3.fromRGB(163,162,165)")
AddUIColorButton("0.0067","Flame reddish orange",Color3.fromRGB(207,96,36),Color3.fromRGB(17,17,17),"Color3.fromRGB(207,96,36)")
AddUIColorButton("0.0068","Reddish brown",Color3.fromRGB(105,64,40),Color3.fromRGB(17,17,17),"Color3.fromRGB(105,64,40)")
AddUIColorButton("0.0069","Flame yellowish orange",Color3.fromRGB(232,171,45),Color3.fromRGB(17,17,17),"Color3.fromRGB(232,171,45)")
AddUIColorButton("0.0070","Fire yellow",Color3.fromRGB(249,214,46),Color3.fromRGB(17,17,17),"Color3.fromRGB(249,214,46)")
AddUIColorButton("0.0071","Black metallic",Color3.fromRGB(22,29,50),Color3.fromRGB(17,17,17),"Color3.fromRGB(22,29,50)")
AddUIColorButton("0.0072","Brick yellow",Color3.fromRGB(215,197,154),Color3.fromRGB(17,17,17),"Color3.fromRGB(215,197,154)")
AddUIColorButton("0.0073","Light reddish violet",Color3.fromRGB(232,186,200),Color3.fromRGB(17,17,17),"Color3.fromRGB(232,186,200)")
AddUIColorButton("0.0074","Light bluish violet",Color3.fromRGB(193,202,222),Color3.fromRGB(17,17,17),"Color3.fromRGB(193,202,222)")
AddUIColorButton("0.0075","Transparent",Color3.fromRGB(236,236,236),Color3.fromRGB(17,17,17),"Color3.fromRGB(236,236,236)")
---












---Font Gui
local FontGui = Instance.new("ScreenGui")
local FontFrame = Instance.new("ScrollingFrame")

FontGui.Parent = game.CoreGui

FontFrame.Parent = FontGui
FontFrame.BackgroundColor3 = Color3.new(1,1,1)
FontFrame.BorderColor3 = Color3.new(0,0,0)
FontFrame.Position = UDim2.new(0.6,0,0.2)
FontFrame.Size = UDim2.new(0.377,0,0.1)
FontFrame.CanvasSize = UDim2.new(1000,0,0,0)
FontFrame.ScrollBarThickness = 0
FontFrame.Draggable = false
FontFrame.BackgroundTransparency = 1
FontFrame.Visible = false
---


--Add Font Button function
function AddFontButton(pos,name,font)
 local FontButton = Instance.new("TextButton")
 FontButton.Parent = FontFrame
 FontButton.BackgroundColor3 = Color3.new(1,1,1)
 FontButton.BackgroundTransparency = 0
 FontButton.BorderColor3 = Color3.new(0,0,0)
 FontButton.Position = UDim2.new(pos,0,0)
 FontButton.TextColor3 = Color3.new(0,0,0)
 FontButton.Size = UDim2.new(0.0002,0,1.1,0)
 FontButton.Font = font
 FontButton.FontSize = Enum.FontSize.Size14
 FontButton.Text = name
 FontButton.TextScaled = false
 FontButton.TextSize = 16.00
 FontButton.TextWrapped = true
 FontButton.Draggable = false

 FontButton.MouseButton1Click:Connect(function()
 FontFrame.Visible = false
SourceCode.Text = SourceCode.Text..""..UIButtonName..".Font = Enum.Font."..name.."\
"
 end)
end
---



---Add Font Button
AddFontButton("0","SourceSans",Enum.Font.SourceSans)
AddFontButton("0.0002","SourceSansLight",Enum.Font.SourceSansLight)
AddFontButton("0.0004","SourceSansBold",Enum.Font.SourceSansBold)
AddFontButton("0.0006","SourceSansItalic",Enum.Font.SourceSansItalic)
AddFontButton("0.0008","Legacy",Enum.Font.Legacy)
AddFontButton("0.0010","Bodoni",Enum.Font.Bodoni)
AddFontButton("0.0012","Garamond",Enum.Font.Garamond)
AddFontButton("0.0014","Cartoon",Enum.Font.Cartoon)
AddFontButton("0.0016","Code",Enum.Font.Code)
AddFontButton("0.0018","Highway",Enum.Font.Highway)
AddFontButton("0.0020","SciFi",Enum.Font.SciFi)
AddFontButton("0.0022","Arcade",Enum.Font.Arcade)
AddFontButton("0.0024","Fantasy",Enum.Font.Fantasy)
AddFontButton("0.0026","Antique",Enum.Font.Antique)
AddFontButton("0.0028","SourceSansSemibold",Enum.Font.SourceSansSemibold)
AddFontButton("0.0030","AmaticSC",Enum.Font.AmaticSC)
AddFontButton("0.0032","Bangers",Enum.Font.Bangers)
AddFontButton("0.0034","Creepster",Enum.Font.Creepster)
AddFontButton("0.0036","DenkOne",Enum.Font.DenkOne)
AddFontButton("0.0038","Fondamento",Enum.Font.Fondamento)
AddFontButton("0.0040","FredokaOne",Enum.Font.FredokaOne)
AddFontButton("0.0042","GrenzeGotisch",Enum.Font.GrenzeGotisch)
AddFontButton("0.0044","IndieFlower",Enum.Font.IndieFlower)
AddFontButton("0.0046","JosefinSans",Enum.Font.JosefinSans)
AddFontButton("0.0048","Jura",Enum.Font.Jura)
AddFontButton("0.0050","Kalam",Enum.Font.Kalam)
AddFontButton("0.0052","LuckiestGuy",Enum.Font.LuckiestGuy)
AddFontButton("0.0054","Merriweather",Enum.Font.Merriweather)
AddFontButton("0.0056","Michroma",Enum.Font.Michroma)
AddFontButton("0.0058","Nunito",Enum.Font.Nunito)
AddFontButton("0.0060","Oswald",Enum.Font.Oswald)
AddFontButton("0.0062","PatrickHand",Enum.Font.PatrickHand)
AddFontButton("0.0064","PermanentMarker",Enum.Font.PermanentMarker)
AddFontButton("0.0066","Roboto",Enum.Font.Roboto)
AddFontButton("0.0068","RobotoCondensed",Enum.Font.RobotoCondensed)
AddFontButton("0.0070","RobotoMono",Enum.Font.RobotoMono)
AddFontButton("0.0072","Sarpanch",Enum.Font.Sarpanch)
AddFontButton("0.0074","SpecialElite",Enum.Font.SpecialElite)
AddFontButton("0.0076","TitilliumWeb",Enum.Font.TitilliumWeb)
AddFontButton("0.0078","Ubuntu",Enum.Font.Ubuntu)
AddFontButton("0.0080","BuilderSans",Enum.Font.BuilderSans)
AddFontButton("0.0082","BuilderSansMedium",Enum.Font.BuilderSansMedium)
AddFontButton("0.0084","BuilderSansBold",Enum.Font.BuilderSansBold)
AddFontButton("0.0086","BuilderSansExtraBold",Enum.Font.BuilderSansExtraBold)
AddFontButton("0.0088","Arimo",Enum.Font.Arimo)
AddFontButton("0.0090","ArimoBold",Enum.Font.ArimoBold)
AddFontButton("0.0092","Unknown",Enum.Font.Unknown)
---












---Request ToastMessage Notification function
function RequestToastMessage(message)
 local ToastMessage = message
 local ToastDisappearTime = 2


 if string.len(ToastMessage) <= 8 then
    ToastSizeOperator = 1
 elseif string.len(ToastMessage) <= 16 then
    ToastSizeOperator = 2
 elseif string.len(ToastMessage) <= 24 then
    ToastSizeOperator = 3
 elseif string.len(ToastMessage) <= 32 then
    ToastSizeOperator = 4
 elseif string.len(ToastMessage) <= 40 then
    ToastSizeOperator = 5
 elseif string.len(ToastMessage) <= 48 then
    ToastSizeOperator = 6
 elseif string.len(ToastMessage) <= 56 then
    ToastSizeOperator = 7
 elseif string.len(ToastMessage) <= 72 then
    ToastSizeOperator = 8
elseif string.len(ToastMessage) >= 80 then
    ToastSizeOperator = 9
 end
 ToastSizeOperator = ToastSizeOperator..""..string.len(ToastMessage)

 local ToastSize = "0."..ToastSizeOperator
 ToastSize = ToastSize..""..string.len(ToastMessage)

 local ToastGui = Instance.new("ScreenGui")
 local ToastText = Instance.new("TextLabel")
 local ToastUICorner = Instance.new("UICorner")

 ToastGui.Parent = game.CoreGui

 ToastText.Parent = ToastGui
 ToastText.BackgroundColor3 = Color3.new(1,1,1)
 ToastText.BackgroundTransparency = 0
 ToastText.Position = UDim2.new(0.5 - ToastSize / 2, 1, 0.775, 1)
 ToastText.TextColor3 = Color3.new(0,0,0)
 ToastText.Size = UDim2.new(ToastSize,1,0.15)
 ToastText.Font = Enum.Font.SourceSansSemibold
 ToastText.FontSize = Enum.FontSize.Size14
 ToastText.Text = ToastMessage
 ToastText.TextScaled = false
 ToastText.TextSize = 20
 ToastText.TextWrapped = true
 ToastText.Transparency = 1

 ToastUICorner.CornerRadius = UDim.new(10, 0)
 ToastUICorner.Parent = ToastText

 while ToastText.Transparency >= 0 do
  wait(.000000001)
  ToastText.Transparency -= .1
 end

 wait(ToastDisappearTime)
 while ToastText.Transparency <= 1.1 do
  wait(.000000001)
  ToastText.Transparency += .1
  if ToastText.Transparency == 1.1 or ToastText.Transparency >= 1.1 then
     ToastGui:Destroy()
  end
 end
end
---









---Request Position function
function RequestPosition(name,posX,posY,posZ,script)
 local PositionGui = Instance.new("ScreenGui")
 local PositionFrame = Instance.new("Frame")
 local PositionFrame2 = Instance.new("Frame")
 local PositionLine = Instance.new("Frame")
 local PositionTitle = Instance.new("TextLabel")
 local PositionButton1 = Instance.new("TextButton")
 local PositionButton2 = Instance.new("TextButton")
 PositionTextBox = Instance.new("TextBox")
 PositionTextBox2 = Instance.new("TextBox")
 PositionTextBox3 = Instance.new("TextBox")
 local PositionUICorner = Instance.new("UICorner")

 PositionGui.Parent = game.CoreGui

 PositionFrame.Parent = PositionGui
 PositionFrame.BackgroundColor3 = Color3.new(0,0,0)
 PositionFrame.Transparency = 0.5
 PositionFrame.BorderColor3 = Color3.new(1,1,1)
 PositionFrame.BorderSizePixel = 0
 PositionFrame.Position = UDim2.new(0,0,-0.2)
 PositionFrame.Size = UDim2.new(1,0,1.2)
 PositionFrame.Active = true
 PositionFrame.Draggable = false

 PositionFrame2.Parent = PositionFrame
 PositionFrame2.BackgroundColor3 = Color3.fromRGB(35,35,35)
 PositionFrame2.BorderColor3 = Color3.new(1,1,1)
 PositionFrame2.BorderSizePixel = 0
 PositionFrame2.Position = UDim2.new(0.3,0,0.35)
 PositionFrame2.Size = UDim2.new(0.4,0,0.4)
 PositionFrame2.Active = true
 PositionFrame2.Draggable = false

 PositionUICorner.CornerRadius = UDim.new(0.1, 0)
 PositionUICorner.Parent = PositionFrame2

 PositionLine.Parent = PositionFrame2
 PositionLine.BackgroundColor3 = Color3.new(0,0,0)
 PositionLine.BorderColor3 = Color3.new(1,1,1)
 PositionLine.BorderSizePixel = 2
 PositionLine.Position = UDim2.new(0.1,0,0.26)
 PositionLine.Size = UDim2.new(0.78,0,0.0000001)
 PositionLine.Active = true

 PositionTitle.Parent = PositionFrame2
 PositionTitle.BackgroundColor3 = Color3.fromRGB(35,35,35)
 PositionTitle.BackgroundTransparency = 1
 PositionTitle.Position = UDim2.new(0.1,0,0.05)
 PositionTitle.Text = ""..name
 PositionTitle.TextColor3 = Color3.new(1,1,1)
 PositionTitle.Size = UDim2.new(0.8,0,0.15)
 PositionTitle.FontSize = Enum.FontSize.Size14
 PositionTitle.TextScaled = false
 PositionTitle.TextSize = 16
 PositionTitle.TextWrapped = true
 
 PositionTextBox.Parent = PositionFrame2
 PositionTextBox.BackgroundColor3 = Color3.new(1,1,1)
 PositionTextBox.BackgroundTransparency = 0
 PositionTextBox.Position = UDim2.new(0.1,0,0.37)
 PositionTextBox.Text = ""..posX
 PositionTextBox.TextColor3 = Color3.new(0,0,0)
 PositionTextBox.Size = UDim2.new(0.22,0,0.25)
 PositionTextBox.FontSize = Enum.FontSize.Size14
 PositionTextBox.TextScaled = true
 PositionTextBox.TextSize = 8
 PositionTextBox.TextWrapped = true

 PositionTextBox2.Parent = PositionFrame2
 PositionTextBox2.BackgroundColor3 = Color3.new(1,1,1)
 PositionTextBox2.BackgroundTransparency = 0
 PositionTextBox2.Position = UDim2.new(0.38,0,0.37)
 PositionTextBox2.Text = ""..posY
 PositionTextBox2.TextColor3 = Color3.new(0,0,0)
 PositionTextBox2.Size = UDim2.new(0.22,0,0.25)
 PositionTextBox2.FontSize = Enum.FontSize.Size14
 PositionTextBox2.TextScaled = true
 PositionTextBox2.TextSize = 8
 PositionTextBox2.TextWrapped = true

 PositionTextBox3.Parent = PositionFrame2
 PositionTextBox3.BackgroundColor3 = Color3.new(1,1,1)
 PositionTextBox3.BackgroundTransparency = 0
 PositionTextBox3.Position = UDim2.new(0.67,0,0.37)
 PositionTextBox3.Text = ""..posZ
 PositionTextBox3.TextColor3 = Color3.new(0,0,0)
 PositionTextBox3.Size = UDim2.new(0.22,0,0.25)
 PositionTextBox3.FontSize = Enum.FontSize.Size14
 PositionTextBox3.TextScaled = true
 PositionTextBox3.TextSize = 8
 PositionTextBox3.TextWrapped = true

 PositionButton1.Parent = PositionFrame2
 PositionButton1.BackgroundColor3 = Color3.new(1,1,1)
 PositionButton1.BackgroundTransparency = 0
 PositionButton1.Position = UDim2.new(0.1,0,0.7)
 PositionButton1.Text = "Cancel"
 PositionButton1.TextColor3 = Color3.new(0,0,0)
 PositionButton1.Size = UDim2.new(0.37,0,0.2)
 PositionButton1.FontSize = Enum.FontSize.Size14
 PositionButton1.TextScaled = true
 PositionButton1.TextSize = 8
 PositionButton1.TextWrapped = true

 PositionButton2.Parent = PositionFrame2
 PositionButton2.BackgroundColor3 = Color3.new(1,1,1)
 PositionButton2.BackgroundTransparency = 0
 PositionButton2.Position = UDim2.new(0.52,0,0.7)
 PositionButton2.Text = "Save"
 PositionButton2.TextColor3 = Color3.new(0,0,0)
 PositionButton2.Size = UDim2.new(0.37,0,0.2)
 PositionButton2.FontSize = Enum.FontSize.Size14
 PositionButton2.TextScaled = true
 PositionButton2.TextSize = 8
 PositionButton2.TextWrapped = true

 PositionButton1.MouseButton1Click:Connect(function()
 PositionGui:Destroy()
 end)

 PositionButton2.MouseButton1Click:Connect(function()
 PositionGui:Destroy()
 RequestPositionText = PositionTextBox.Text..","..PositionTextBox2.Text..","..PositionTextBox3.Text
 loadstring(script)()
 end)
end
---










--Request TextBox UIScriptButton function
function RequestTextBox(textbox,script)
 local EdittextGui = Instance.new("ScreenGui")
 local EdittextFrame = Instance.new("Frame")
 local EdittextFrame2 = Instance.new("Frame")
 local EdittextLine = Instance.new("Frame")
 local EdittextTitle = Instance.new("TextLabel")
 local EdittextButton1 = Instance.new("TextButton")
 local EdittextButton2 = Instance.new("TextButton")
 local EdittextTextBox = Instance.new("TextBox")
 local EdittextUICorner = Instance.new("UICorner")

 EdittextGui.Parent = game.CoreGui

 EdittextFrame.Parent = EdittextGui
 EdittextFrame.BackgroundColor3 = Color3.new(0,0,0)
 EdittextFrame.Transparency = 0.5
 EdittextFrame.BorderColor3 = Color3.new(1,1,1)
 EdittextFrame.BorderSizePixel = 0
 EdittextFrame.Position = UDim2.new(0,0,-0.2)
 EdittextFrame.Size = UDim2.new(1,0,1.2)
 EdittextFrame.Active = true
 EdittextFrame.Draggable = false

 EdittextFrame2.Parent = EdittextFrame
 EdittextFrame2.BackgroundColor3 = Color3.fromRGB(35,35,35)
 EdittextFrame2.BorderColor3 = Color3.new(1,1,1)
 EdittextFrame2.BorderSizePixel = 0
 EdittextFrame2.Position = UDim2.new(0.3,0,0.35)
 EdittextFrame2.Size = UDim2.new(0.4,0,0.4)
 EdittextFrame2.Active = true
 EdittextFrame2.Draggable = false

 EdittextUICorner.CornerRadius = UDim.new(0.1, 0)
 EdittextUICorner.Parent = EdittextFrame2

 EdittextLine.Parent = EdittextFrame2
 EdittextLine.BackgroundColor3 = Color3.new(0,0,0)
 EdittextLine.BorderColor3 = Color3.new(1,1,1)
 EdittextLine.BorderSizePixel = 2
 EdittextLine.Position = UDim2.new(0.1,0,0.26)
 EdittextLine.Size = UDim2.new(0.78,0,0.0000001)
 EdittextLine.Active = true

 EdittextTitle.Parent = EdittextFrame2
 EdittextTitle.BackgroundColor3 = Color3.fromRGB(35,35,35)
 EdittextTitle.BackgroundTransparency = 1
 EdittextTitle.Position = UDim2.new(0.1,0,0.05)
 EdittextTitle.Text = "Script"
 EdittextTitle.TextColor3 = Color3.new(1,1,1)
 EdittextTitle.Size = UDim2.new(0.8,0,0.15)
 EdittextTitle.FontSize = Enum.FontSize.Size14
 EdittextTitle.TextScaled = false
 EdittextTitle.TextSize = 16
 EdittextTitle.TextWrapped = true
 
 EdittextTextBox.Parent = EdittextFrame2
 EdittextTextBox.BackgroundColor3 = Color3.new(1,1,1)
 EdittextTextBox.BackgroundTransparency = 0
 EdittextTextBox.Position = UDim2.new(0.1,0,0.37)
 EdittextTextBox.Text = ""..textbox
 EdittextTextBox.TextColor3 = Color3.new(0,0,0)
 EdittextTextBox.Size = UDim2.new(0.79,0,0.25)
 EdittextTextBox.FontSize = Enum.FontSize.Size14
 EdittextTextBox.TextScaled = true
 EdittextTextBox.TextSize = 8
 EdittextTextBox.TextWrapped = true

 EdittextButton1.Parent = EdittextFrame2
 EdittextButton1.BackgroundColor3 = Color3.new(1,1,1)
 EdittextButton1.BackgroundTransparency = 0
 EdittextButton1.Position = UDim2.new(0.1,0,0.7)
 EdittextButton1.Text = "Cancel"
 EdittextButton1.TextColor3 = Color3.new(0,0,0)
 EdittextButton1.Size = UDim2.new(0.37,0,0.2)
 EdittextButton1.FontSize = Enum.FontSize.Size14
 EdittextButton1.TextScaled = true
 EdittextButton1.TextSize = 8
 EdittextButton1.TextWrapped = true

 EdittextButton2.Parent = EdittextFrame2
 EdittextButton2.BackgroundColor3 = Color3.new(1,1,1)
 EdittextButton2.BackgroundTransparency = 0
 EdittextButton2.Position = UDim2.new(0.52,0,0.7)
 EdittextButton2.Text = "Save"
 EdittextButton2.TextColor3 = Color3.new(0,0,0)
 EdittextButton2.Size = UDim2.new(0.37,0,0.2)
 EdittextButton2.FontSize = Enum.FontSize.Size14
 EdittextButton2.TextScaled = true
 EdittextButton2.TextSize = 8
 EdittextButton2.TextWrapped = true

 EdittextButton1.MouseButton1Click:connect(function()
 EdittextGui:Destroy()
 end)

 EdittextButton2.MouseButton1Click:connect(function()
 EdittextGui:Destroy()
 RequestTextBoxText = EdittextTextBox.Text
 loadstring(script)()
 end)
end
---




---Request True False Gui function
function RequestTrueFalse(title,button1,button2,script1,script2)
 local TrueFalseGui = Instance.new("ScreenGui")
 local TrueFalseFrame = Instance.new("Frame")
 local TrueFalseFrame2 = Instance.new("Frame")
 local TrueFalseLine = Instance.new("Frame")
 local TrueFalseTitle = Instance.new("TextLabel")
 local TrueFalseButton1 = Instance.new("TextButton")
 local TrueFalseButton2 = Instance.new("TextButton")
 local TrueFalseButton3 = Instance.new("TextButton")
 local TrueFalseUICorner = Instance.new("UICorner")

 TrueFalseGui.Parent = game.CoreGui

 TrueFalseFrame.Parent = TrueFalseGui
 TrueFalseFrame.BackgroundColor3 = Color3.new(0,0,0)
 TrueFalseFrame.Transparency = 0.5
 TrueFalseFrame.BorderColor3 = Color3.new(1,1,1)
 TrueFalseFrame.BorderSizePixel = 0
 TrueFalseFrame.Position = UDim2.new(0,0,-0.2)
 TrueFalseFrame.Size = UDim2.new(1,0,1.2)
 TrueFalseFrame.Active = true
 TrueFalseFrame.Draggable = false

 TrueFalseFrame2.Parent = TrueFalseFrame
 TrueFalseFrame2.BackgroundColor3 = Color3.fromRGB(35,35,35)
 TrueFalseFrame2.BorderColor3 = Color3.new(1,1,1)
 TrueFalseFrame2.BorderSizePixel = 0
 TrueFalseFrame2.Position = UDim2.new(0.35,0,0.35)
 TrueFalseFrame2.Size = UDim2.new(0.33,0,0.35)
 TrueFalseFrame2.Active = true
 TrueFalseFrame2.Draggable = false

 TrueFalseUICorner.CornerRadius = UDim.new(0.1, 0)
 TrueFalseUICorner.Parent = TrueFalseFrame2

 TrueFalseLine.Parent = TrueFalseFrame2
 TrueFalseLine.BackgroundColor3 = Color3.new(0,0,0)
 TrueFalseLine.BorderColor3 = Color3.new(1,1,1)
 TrueFalseLine.BorderSizePixel = 2
 TrueFalseLine.Position = UDim2.new(0.1,0,0.3)
 TrueFalseLine.Size = UDim2.new(0.78,0,0.0000001)
 TrueFalseLine.Active = true

 TrueFalseTitle.Parent = TrueFalseFrame2
 TrueFalseTitle.BackgroundColor3 = Color3.fromRGB(35,35,35)
 TrueFalseTitle.BackgroundTransparency = 1
 TrueFalseTitle.Position = UDim2.new(0.1,0,0.08)
 TrueFalseTitle.Text = "Script"
 TrueFalseTitle.TextColor3 = Color3.new(1,1,1)
 TrueFalseTitle.Size = UDim2.new(0.8,0,0.15)
 TrueFalseTitle.FontSize = Enum.FontSize.Size14
 TrueFalseTitle.TextScaled = false
 TrueFalseTitle.TextSize = 16
 TrueFalseTitle.TextWrapped = true

 TrueFalseButton1.Parent = TrueFalseFrame2
 TrueFalseButton1.BackgroundColor3 = Color3.new(1,1,1)
 TrueFalseButton1.BackgroundTransparency = 0
 TrueFalseButton1.Position = UDim2.new(0.1,0,0.42)
 TrueFalseButton1.Text = "true"
 TrueFalseButton1.TextColor3 = Color3.new(0,0,0)
 TrueFalseButton1.Size = UDim2.new(0.37,0,0.2)
 TrueFalseButton1.FontSize = Enum.FontSize.Size14
 TrueFalseButton1.TextScaled = true
 TrueFalseButton1.TextSize = 8
 TrueFalseButton1.TextWrapped = true

 TrueFalseButton2.Parent = TrueFalseFrame2
 TrueFalseButton2.BackgroundColor3 = Color3.new(1,1,1)
 TrueFalseButton2.BackgroundTransparency = 0
 TrueFalseButton2.Position = UDim2.new(0.52,0,0.42)
 TrueFalseButton2.Text = "false"
 TrueFalseButton2.TextColor3 = Color3.new(0,0,0)
 TrueFalseButton2.Size = UDim2.new(0.37,0,0.2)
 TrueFalseButton2.FontSize = Enum.FontSize.Size14
 TrueFalseButton2.TextScaled = true
 TrueFalseButton2.TextSize = 8
 TrueFalseButton2.TextWrapped = true

 TrueFalseButton3.Parent = TrueFalseFrame2
 TrueFalseButton3.BackgroundColor3 = Color3.new(1,1,1)
 TrueFalseButton3.BackgroundTransparency = 0
 TrueFalseButton3.Position = UDim2.new(0.1,0,0.7)
 TrueFalseButton3.Text = "Cancel"
 TrueFalseButton3.TextColor3 = Color3.new(0,0,0)
 TrueFalseButton3.Size = UDim2.new(0.79,0,0.2)
 TrueFalseButton3.FontSize = Enum.FontSize.Size14
 TrueFalseButton3.TextScaled = true
 TrueFalseButton3.TextSize = 8
 TrueFalseButton3.TextWrapped = true

 TrueFalseButton1.MouseButton1Click:connect(function()
 TrueFalseGui:Destroy()
 loadstring(script1)()
 end)

 TrueFalseButton2.MouseButton1Click:connect(function()
 TrueFalseGui:Destroy()
 loadstring(script2)()
 end)

 TrueFalseButton3.MouseButton1Click:connect(function()
 TrueFalseGui:Destroy()
 end)
 
 if title then
   TrueFalseTitle.Text = ""..title
 end
 if button1 then
   TrueFalseButton1.Text = ""..button1
 end
 if button2 then
   TrueFalseButton2.Text = ""..button2
 end
end
---










---UIScript Gui
local UIScriptGui = Instance.new("ScreenGui")
local UIScriptScrolling = Instance.new("ScrollingFrame")

UIScriptGui.Parent = game.CoreGui

UIScriptScrolling.Parent = UIScriptGui
UIScriptScrolling.BackgroundColor3 = Color3.new(0,0,0)
UIScriptScrolling.BackgroundTransparency = 0.8
UIScriptScrolling.Position = UDim2.new(0, 0, 0)
UIScriptScrolling.Size = UDim2.new(1,0,1)
UIScriptScrolling.CanvasSize = UDim2.new(10, 0, 0, 0)
UIScriptScrolling.ScrollBarThickness = 10
UIScriptScrolling.Visible = false

local UIScriptButtonPosition = 0.005

local function AddUIScriptButton(name,script)
 local UIScript = Instance.new("TextButton")
 UIScript.Parent = UIScriptScrolling
 UIScript.BackgroundColor3 = Color3.new(1,1,1)
 UIScript.BackgroundTransparency = 0
 UIScript.Position = UDim2.new(UIScriptButtonPosition, 0, 0.4, 0)
 UIScript.TextColor3 = Color3.new(0,0,0)
 UIScript.Size = UDim2.new(0.025,0,0.25)
 UIScript.Font = Enum.Font.SourceSansBold
 UIScript.FontSize = Enum.FontSize.Size14
 UIScript.Text = ""..name
 UIScript.TextScaled = false
 UIScript.TextSize = 18.00
 UIScript.TextWrapped = true
 UIScriptButtonPosition += 0.03

 UIScript.MouseButton1Click:Connect(function()
 UIScriptScrolling.Visible = false
 loadstring(script)()
 end)
end
---








---Bonus Functions
function Execute1()
SourceCode.Text = SourceCode.Text..""..UIButtonName..".Parent = game.CoreGui\
"
end

function Execute2()
SourceCode.Text = SourceCode.Text..""..UIButtonName..".Parent = game.Players.LocalPlayer.PlayerGui\
"
end

function Execute3()
SourceCode.Text = SourceCode.Text..""..UIButtonName..".Parent = "..RequestTextBoxText.."\
"
end

function Execute4()
SourceCode.Text = SourceCode.Text..""..UIButtonName..".Visible = true\
"
end

function Execute5()
SourceCode.Text = SourceCode.Text..""..UIButtonName..".Visible = false\
"
end

function Execute6()
 if UIColorFrame.Visible == false then
    UIColorFrame.Visible = true
    ColoringType = ".BackgroundColor3 = "
 else
    UIColorFrame.Visible = false
 end
end

function Execute7()
SourceCode.Text = SourceCode.Text..""..UIButtonName..".BackgroundTransparency = "..RequestTextBoxText.."\
"
end

function Execute8()
SourceCode.Text = SourceCode.Text..""..UIButtonName..".BorderSizePixel = "..RequestTextBoxText.."\
"
end

function Execute9()
 if UIColorFrame.Visible == false then
    UIColorFrame.Visible = true
    ColoringType = ".BorderColor3 = "
 else
    UIColorFrame.Visible = false
 end
end

function Execute10()
SourceCode.Text = SourceCode.Text..""..UIButtonName..".Position = UDim2.new("..RequestPositionText..")\
"
end

function Execute11()
SourceCode.Text = SourceCode.Text..""..UIButtonName..".Size = UDim2.new("..RequestPositionText..")\
"
end

function Execute12()
SourceCode.Text = SourceCode.Text..""..UIButtonName..".Active = true\
"
end

function Execute13()
SourceCode.Text = SourceCode.Text..""..UIButtonName..".Active = false\
"
end

function Execute14()
SourceCode.Text = SourceCode.Text..""..UIButtonName..".Draggable = true\
"
end

function Execute15()
SourceCode.Text = SourceCode.Text..""..UIButtonName..".Draggable = false\
"
end

function Execute16()
SourceCode.Text = SourceCode.Text..''..UIButtonName..'.Text = "'..RequestTextBoxText..'"\
'
end

function Execute17()
 if FontFrame.Visible == false then
    FontFrame.Visible = true
 else
    FontFrame.Visible = false
 end
end

function Execute18()
SourceCode.Text = SourceCode.Text..""..UIButtonName..".TextScaled = true\
"
end

function Execute19()
SourceCode.Text = SourceCode.Text..""..UIButtonName..".TextScaled = false\
"
end

function Execute20()
SourceCode.Text = SourceCode.Text..''..UIButtonName..'.TextSize = '..RequestTextBoxText..'\
'
end

function Execute21()
SourceCode.Text = SourceCode.Text..""..UIButtonName..".TextWrapped = true\
"
end

function Execute22()
SourceCode.Text = SourceCode.Text..""..UIButtonName..".TextWrapped = false\
"
end

function Execute23()
SourceCode.Text = SourceCode.Text.."\
"..UIButtonName..".MouseButton1Click:Connect(function() \
--add your script here\
end)\
"
end

function Execute24()
SourceCode.Text = SourceCode.Text..""..UIButtonName..".ClearTextOnFocus = true\
"
end

function Execute25()
SourceCode.Text = SourceCode.Text..""..UIButtonName..".ClearTextOnFocus = false\
"
end

function Execute26()
SourceCode.Text = SourceCode.Text..""..UIButtonName..".TextXAlignment = Enum.TextXAlignment.Left\
"
end

function Execute27()
SourceCode.Text = SourceCode.Text..""..UIButtonName..".TextXAlignment = Enum.TextXAlignment.Right\
"
end

function Execute28()
SourceCode.Text = SourceCode.Text..""..UIButtonName..".TextYAlignment = Enum.TextYAlignment.Top\
"
end

function Execute29()
SourceCode.Text = SourceCode.Text..""..UIButtonName..".TextYAlignment = Enum.TextYAlignment.Bottom\
"
end

function Execute30()
SourceCode.Text = SourceCode.Text..''..UIButtonName..'.Name = "'..RequestTextBoxText..'"\
'
end

function Execute31()
SourceCode.Text = SourceCode.Text.."\
"..UIButtonName..".FocusLost:Connect(function() \
--script here need clear--\
end)\
"
end

function Execute32()
SourceCode.Text = SourceCode.Text..''..UIButtonName..'.PlaceholderText = "'..RequestTextBoxText..'"\
'
end

function Execute33()
SourceCode.Text = SourceCode.Text..""..UIButtonName..".MultiLine = true\
"
end

function Execute34()
SourceCode.Text = SourceCode.Text..""..UIButtonName..".MultiLine = false\
"
end

function Execute35()
SourceCode.Text = SourceCode.Text..''..UIButtonName..'.Image = "rbxassetid://'..RequestTextBoxText..'"\
'
end

function Execute36()
SourceCode.Text = SourceCode.Text..""..UIButtonName..".CanvaSize = UDim2.new("..RequestPositionText..")\
"
end

function Execute37()
SourceCode.Text = SourceCode.Text..""..UIButtonName..".ScrollBarThickness = "..RequestTextBoxText.."\
"
end

function Execute38()
 if UIColorFrame.Visible == false then
    UIColorFrame.Visible = true
    ColoringType = ".TextColor3 = "
 else
    UIColorFrame.Visible = false
 end
end

function Execute39()
RequestPositionText = PositionTextBox.Text..","..PositionTextBox2.Text
SourceCode.Text = SourceCode.Text..""..UIButtonName..".CornerRadius = UDim.new("..RequestPositionText..")\
"
end

function Execute40()
 RequestPosition("CornerRadius","0.1","0","","Execute39()")
 PositionTextBox.Position = UDim2.new(0.25,0,0.37)
 PositionTextBox2.Position = UDim2.new(0.52,0,0.37)
 PositionTextBox3.Visible = false
end

function Execute41()
SourceCode.Text = SourceCode.Text..""..UIButtonName..".Transparency = "..RequestTextBoxText.."\
"
end

function Execute42()
 if UIColorFrame.Visible == false then
    UIColorFrame.Visible = true
    ColoringType = ".Color = "
 else
    UIColorFrame.Visible = false
 end
end

function Execute43()
SourceCode.Text = SourceCode.Text..""..UIButtonName..".Thickness = "..RequestTextBoxText.."\
"
end

function Execute44()
SourceCode.Text = SourceCode.Text..""..UIButtonName..".BackgroundTransparency = "..RequestTextBoxText.."\
"
end

function Execute45()
SourceCode.Text = SourceCode.Text..""..UIButtonName..".Transparency = "..RequestTextBoxText.."\
"
end
---







---UI List Gui
local UIListGui = Instance.new("ScreenGui")
local UIFrame = Instance.new("ScrollingFrame")

UIListGui.Parent = game.CoreGui

UIFrame.Parent = UIListGui
UIFrame.BackgroundColor3 = Color3.new(1,1,1)
UIFrame.BorderColor3 = Color3.new(0,0,0)
UIFrame.Position = UDim2.new(0.6,0,-0.11)
UIFrame.Size = UDim2.new(0.3,0,0.1)
UIFrame.CanvasSize = UDim2.new(1000, 0, 0, 0)
UIFrame.ScrollBarThickness = 0
UIFrame.Draggable = false
UIFrame.Visible = false

local UIPosition = 0
local UIType = nil

local function AddUI(name,type)
 local UI = Instance.new("TextButton")
 UI.Parent = UIFrame
 UI.BackgroundColor3 = Color3.new(1,1,1)
 UI.BackgroundTransparency = 0
 UI.BorderColor3 = Color3.new(0,0,0)
 UI.Position = UDim2.new(UIPosition, 0, 0, 0)
 UI.TextColor3 = Color3.new(0,0,0)
 UI.Size = UDim2.new(0.0001,0,1,0)
 UI.Font = Enum.Font.SourceSansBold
 UI.FontSize = Enum.FontSize.Size14
 UI.Text = name
 UI.TextScaled = false
 UI.TextSize = 14.00
 UI.TextWrapped = true
 UI.Draggable = false
 UIPosition += 0.0001
 
 UI.MouseButton1Click:Connect(function()
 if UIScriptScrolling.Visible == false then
    UIScriptScrolling.Visible = true
 else
    UIScriptScrolling.Visible = false
 end
 UIScriptScrolling:ClearAllChildren()
 UIScriptButtonPosition = 0.005
 end)
 
 --Type
 if type == "ScreenGui" then
    UI.MouseButton1Click:Connect(function()
    wait()
    UIButtonName = name
    UIType = "ScreenGui"
    AddUIScriptButton("Parent",'RequestTrueFalse("Script","CoreGui","PlayerGui","Execute1()","Execute2()")')
    AddUIScriptButton("Name",'RequestTextBox("","Execute30()")')
    end)
 end
 if type == "Frame" then
    UI.MouseButton1Click:Connect(function()
    wait()
    UIButtonName = name
    UIType = "Frame"
    AddUIScriptButton("Parent",'RequestTextBox("ScreenGui"..ScreenGuiNumber,"Execute3()")')
    AddUIScriptButton("Name",'RequestTextBox("","Execute30()")')
    AddUIScriptButton("BackgroundColor3","Execute6()")
    AddUIScriptButton("BackgroundTransparency",'RequestTextBox("0","Execute7()")')
    AddUIScriptButton("BorderSizePixel",'RequestTextBox("1","Execute8()")')
    AddUIScriptButton("BorderColor3","Execute9()")
    AddUIScriptButton("Position",'RequestPosition("Position","0","0","0","Execute10()")')
    AddUIScriptButton("Size",'RequestPosition("Size","0.08","0","0.1","Execute11()")')
    AddUIScriptButton("Visible",'RequestTrueFalse("Visible","true","false","Execute4()","Execute5()")')
    AddUIScriptButton("Active",'RequestTrueFalse("Active","true","false","Execute12()","Execute13()")')
    AddUIScriptButton("Draggable",'RequestTrueFalse("Draggable","true","false","Execute14()","Execute15()")')
    end)
 end
 if type == "TextLabel" or type == "TextButton" then
    UI.MouseButton1Click:Connect(function()
    wait()
    UIButtonName = name
    UIType = "TextLabel"
    AddUIScriptButton("Parent",'RequestTextBox("ScreenGui"..ScreenGuiNumber,"Execute3()")')
    AddUIScriptButton("Name",'RequestTextBox("","Execute30()")')
    AddUIScriptButton("BackgroundColor3","Execute6()")
    AddUIScriptButton("BackgroundTransparency",'RequestTextBox("0","Execute7()")')
    AddUIScriptButton("BorderSizePixel",'RequestTextBox("1","Execute8()")')
    AddUIScriptButton("BorderColor3","Execute9()")
    AddUIScriptButton("Position",'RequestPosition("Position","0","0","0","Execute10()")')
    AddUIScriptButton("Size",'RequestPosition("Size","0.08","0","0.1","Execute11()")')
    AddUIScriptButton("Font","Execute17()")
    AddUIScriptButton("TextColor3","Execute38()")
    AddUIScriptButton("Text",'RequestTextBox("Text","Execute16()")')
    AddUIScriptButton("TextSize",'RequestTextBox("18","Execute20()")')
    AddUIScriptButton("TextScaled",'RequestTrueFalse("TextScaled","true","false","Execute18()","Execute19()")')
    AddUIScriptButton("TextWrapped",'RequestTrueFalse("TextWrapped","true","false","Execute21()","Execute22()")')
    AddUIScriptButton("TextXAlignment",'RequestTrueFalse("TextXAlignment","Left","Right","Execute26()","Execute27()")')
    AddUIScriptButton("TextYAlignment",'RequestTrueFalse("TextYAlignment","Top","Bottom","Execute28()","Execute29()")')
    AddUIScriptButton("Visible",'RequestTrueFalse("Visible","true","false","Execute4()","Execute5()")')
    AddUIScriptButton("Active",'RequestTrueFalse("Active","true","false","Execute12()","Execute13()")')
    AddUIScriptButton("Draggable",'RequestTrueFalse("Draggable","true","false","Execute14()","Execute15()")')
    if type == "TextButton" then
       AddUIScriptButton("OnClick Function","Execute23()")
    end
    end)
 end
 if type == "TextBox" then
    UI.MouseButton1Click:Connect(function()
    wait()
    UIButtonName = name
    UIType = "TextBox"
    AddUIScriptButton("Parent",'RequestTextBox("ScreenGui"..ScreenGuiNumber,"Execute3()")')
    AddUIScriptButton("Name",'RequestTextBox("","Execute30()")')
    AddUIScriptButton("BackgroundColor3","Execute6()")
    AddUIScriptButton("BackgroundTransparency",'RequestTextBox("0","Execute7()")')
    AddUIScriptButton("BorderSizePixel",'RequestTextBox("1","Execute8()")')
    AddUIScriptButton("BorderColor3","Execute9()")
    AddUIScriptButton("Position",'RequestPosition("Position","0","0","0","Execute10()")')
    AddUIScriptButton("Size",'RequestPosition("Size","0.08","0","0.1","Execute11()")')
    AddUIScriptButton("Font","Execute17()")
    AddUIScriptButton("TextColor3","Execute38()")
    AddUIScriptButton("Text",'RequestTextBox("Text","Execute16()")')
    AddUIScriptButton("PlaceholderText",'RequestTextBox("PlaceholderText","Execute32()")')
    AddUIScriptButton("TextScaled",'RequestTrueFalse("TextScaled","true","false","Execute18()","Execute19()")')
    AddUIScriptButton("TextWrapped",'RequestTrueFalse("TextWrapped","true","false","Execute21()","Execute22()")')
    AddUIScriptButton("TextSize",'RequestTextBox("18","Execute20()")')
    AddUIScriptButton("MultiLine",'RequestTrueFalse("MultiLine","true","false","Execute33()","Execute34()")')
    AddUIScriptButton("ClearTextOnFocus",'RequestTrueFalse("ClearTextOnFocus","true","false","Execute24()","Execute25()")')
    AddUIScriptButton("TextXAlignment",'RequestTrueFalse("TextXAlignment","Left","Right","Execute26()","Execute27()")')
    AddUIScriptButton("TextYAlignment",'RequestTrueFalse("TextYAlignment","Top","Bottom","Execute28()","Execute29()")')
    AddUIScriptButton("Visible",'RequestTrueFalse("Visible","true","false","Execute4()","Execute5()")')
    AddUIScriptButton("Active",'RequestTrueFalse("Active","true","false","Execute12()","Execute13()")')
    AddUIScriptButton("Draggable",'RequestTrueFalse("Draggable","true","false","Execute14()","Execute15()")')
    AddUIScriptButton("On FocusLost Function","Execute31()")
    end)
 end
 if type == "ImageButton" then
    UI.MouseButton1Click:Connect(function()
    wait()
    UIButtonName = name
    UIType = "ImageButton"
    AddUIScriptButton("Parent",'RequestTextBox("ScreenGui"..ScreenGuiNumber,"Execute3()")')
    AddUIScriptButton("Name",'RequestTextBox("","Execute30()")')
    AddUIScriptButton("BackgroundTransparency",'RequestTextBox("0","Execute44()")')
    AddUIScriptButton("Position",'RequestPosition("Position","0","0","0","Execute10()")')
    AddUIScriptButton("Size",'RequestPosition("Size","0.05","0","0.1","Execute11()")')
    AddUIScriptButton("Image",'RequestTextBox("17611933870","Execute35()")')
    AddUIScriptButton("Draggable",'RequestTrueFalse("Draggable","true","false","Execute14()","Execute15()")')
    AddUIScriptButton("Visible",'RequestTrueFalse("Visible","true","false","Execute4()","Execute5()")')
    AddUIScriptButton("OnClick Function","Execute23()")
    end)
 end
 if type == "ScrollingFrame" then
    UI.MouseButton1Click:Connect(function()
    wait()
    UIButtonName = name
    UIType = "ScrollingFrame"
    AddUIScriptButton("Parent",'RequestTextBox("ScreenGui"..ScreenGuiNumber,"Execute3()")')
    AddUIScriptButton("Name",'RequestTextBox("","Execute30()")')
    AddUIScriptButton("BackgroundColor3","Execute6()")
    AddUIScriptButton("BackgroundTransparency",'RequestTextBox("0","Execute7()")')
    AddUIScriptButton("BorderSizePixel",'RequestTextBox("1","Execute8()")')
    AddUIScriptButton("BorderColor3","Execute9()")
    AddUIScriptButton("Position",'RequestPosition("Position","0","0","0","Execute10()")')
    AddUIScriptButton("Size",'RequestPosition("Size","0.08","0","0.1","Execute11()")')
    AddUIScriptButton("CanvaSize",'RequestPosition("CanvaSize","1","0","10","Execute36()")')
    AddUIScriptButton("ScrollBarThickness",'RequestTextBox("1","Execute37()")')
    AddUIScriptButton("Visible",'RequestTrueFalse("Visible","true","false","Execute4()","Execute5()")')
    AddUIScriptButton("Active",'RequestTrueFalse("Active","true","false","Execute12()","Execute13()")')
    AddUIScriptButton("Draggable",'RequestTrueFalse("Draggable","true","false","Execute14()","Execute15()")')
    end)
 end
 if type == "UICorner" then
    UI.MouseButton1Click:Connect(function()
    wait()
    UIButtonName = name
    UIType = "ScrollingFrame"
    AddUIScriptButton("Parent",'RequestTextBox("Frame"..FrameNumber,"Execute3()")')
    AddUIScriptButton("CornerRadius","Execute40()")
    end)
 end
 if type == "UIStroke" then
    UI.MouseButton1Click:Connect(function()
    wait()
    UIButtonName = name
    UIType = "UIStroke"
    AddUIScriptButton("Parent",'RequestTextBox("Frame"..FrameNumber,"Execute3()")')
    AddUIScriptButton("Transparency",'RequestTextBox("0","Execute41()")')
    AddUIScriptButton("Color","Execute42()")
    AddUIScriptButton("Thickness",'RequestTextBox("1","Execute43()")')
    end)
 end
end
---







local function Reset()
 UIButtonName = nil
 ColoringType = nil
 RequestTextBoxText = nil
 RequestPositionText = nil
 SourceCode.Text = ""
 UIPosition = 0
 UIFrame:ClearAllChildren()
 ScreenGuiNumber = 0
 FrameNumber = 0
 TextLabelNumber = 0
 TextButtonNumber = 0
 TextBoxNumber = 0
 ImageButtonNumber = 0
 ScrollingFrameNumber = 0
 UICornerNumber = 0
 UIStrokeNumber = 0
end
Reset()









---Add Gui
local AddGui = Instance.new("ScreenGui")
local AddScrolling = Instance.new("ScrollingFrame")
local AddButton1 = Instance.new("TextButton")
local AddButton2 = Instance.new("TextButton")
local AddButton3 = Instance.new("TextButton")
local AddButton4 = Instance.new("TextButton")
local AddButton5 = Instance.new("TextButton")
local AddButton6 = Instance.new("TextButton")
local AddButton7 = Instance.new("TextButton")
local AddButton8 = Instance.new("TextButton")
local AddButton9 = Instance.new("TextButton")

AddGui.Parent = game.CoreGui

AddScrolling.Parent = AddGui
AddScrolling.BackgroundColor3 = Color3.new(0,0,0)
AddScrolling.BackgroundTransparency = 0.8
AddScrolling.Position = UDim2.new(0, 0, 0)
AddScrolling.Size = UDim2.new(1,0,1)
AddScrolling.CanvasSize = UDim2.new(5, 0, 0, 0)
AddScrolling.ScrollBarThickness = 10
AddScrolling.Visible = false

AddButton1.Parent = AddScrolling
AddButton1.BackgroundColor3 = Color3.new(1,1,1)
AddButton1.BackgroundTransparency = 0
AddButton1.Position = UDim2.new(0.01, 0, 0.4, 0)
AddButton1.TextColor3 = Color3.new(0,0,0)
AddButton1.Size = UDim2.new(0.05,0,0.25)
AddButton1.Font = Enum.Font.SourceSansBold
AddButton1.FontSize = Enum.FontSize.Size14
AddButton1.Text = "ScreenGui"
AddButton1.TextScaled = false
AddButton1.TextSize = 26.00
AddButton1.TextWrapped = true

AddButton2.Parent = AddScrolling
AddButton2.BackgroundColor3 = Color3.new(1,1,1)
AddButton2.BackgroundTransparency = 0
AddButton2.Position = UDim2.new(0.07, 0, 0.4, 0)
AddButton2.TextColor3 = Color3.new(0,0,0)
AddButton2.Size = UDim2.new(0.05,0,0.25)
AddButton2.Font = Enum.Font.SourceSansBold
AddButton2.FontSize = Enum.FontSize.Size14
AddButton2.Text = "Frame"
AddButton2.TextScaled = false
AddButton2.TextSize = 26.00
AddButton2.TextWrapped = true

AddButton3.Parent = AddScrolling
AddButton3.BackgroundColor3 = Color3.new(1,1,1)
AddButton3.BackgroundTransparency = 0
AddButton3.Position = UDim2.new(0.13, 0, 0.4, 0)
AddButton3.TextColor3 = Color3.new(0,0,0)
AddButton3.Size = UDim2.new(0.05,0,0.25)
AddButton3.Font = Enum.Font.SourceSansBold
AddButton3.FontSize = Enum.FontSize.Size14
AddButton3.Text = "TextLabel"
AddButton3.TextScaled = false
AddButton3.TextSize = 26.00
AddButton3.TextWrapped = true

AddButton4.Parent = AddScrolling
AddButton4.BackgroundColor3 = Color3.new(1,1,1)
AddButton4.BackgroundTransparency = 0
AddButton4.Position = UDim2.new(0.19, 0, 0.4, 0)
AddButton4.TextColor3 = Color3.new(0,0,0)
AddButton4.Size = UDim2.new(0.05,0,0.25)
AddButton4.Font = Enum.Font.SourceSansBold
AddButton4.FontSize = Enum.FontSize.Size14
AddButton4.Text = "TextButton"
AddButton4.TextScaled = false
AddButton4.TextSize = 26.00
AddButton4.TextWrapped = true

AddButton5.Parent = AddScrolling
AddButton5.BackgroundColor3 = Color3.new(1,1,1)
AddButton5.BackgroundTransparency = 0
AddButton5.Position = UDim2.new(0.25, 0, 0.4, 0)
AddButton5.TextColor3 = Color3.new(0,0,0)
AddButton5.Size = UDim2.new(0.05,0,0.25)
AddButton5.Font = Enum.Font.SourceSansBold
AddButton5.FontSize = Enum.FontSize.Size14
AddButton5.Text = "TextBox"
AddButton5.TextScaled = false
AddButton5.TextSize = 26.00
AddButton5.TextWrapped = true

AddButton6.Parent = AddScrolling
AddButton6.BackgroundColor3 = Color3.new(1,1,1)
AddButton6.BackgroundTransparency = 0
AddButton6.Position = UDim2.new(0.31, 0, 0.4, 0)
AddButton6.TextColor3 = Color3.new(0,0,0)
AddButton6.Size = UDim2.new(0.05,0,0.25)
AddButton6.Font = Enum.Font.SourceSansBold
AddButton6.FontSize = Enum.FontSize.Size14
AddButton6.Text = "ImageButton"
AddButton6.TextScaled = false
AddButton6.TextSize = 26.00
AddButton6.TextWrapped = true

AddButton7.Parent = AddScrolling
AddButton7.BackgroundColor3 = Color3.new(1,1,1)
AddButton7.BackgroundTransparency = 0
AddButton7.Position = UDim2.new(0.37, 0, 0.4, 0)
AddButton7.TextColor3 = Color3.new(0,0,0)
AddButton7.Size = UDim2.new(0.05,0,0.25)
AddButton7.Font = Enum.Font.SourceSansBold
AddButton7.FontSize = Enum.FontSize.Size14
AddButton7.Text = "ScrollingFrame"
AddButton7.TextScaled = false
AddButton7.TextSize = 26.00
AddButton7.TextWrapped = true

AddButton8.Parent = AddScrolling
AddButton8.BackgroundColor3 = Color3.new(1,1,1)
AddButton8.BackgroundTransparency = 0
AddButton8.Position = UDim2.new(0.43, 0, 0.4, 0)
AddButton8.TextColor3 = Color3.new(0,0,0)
AddButton8.Size = UDim2.new(0.05,0,0.25)
AddButton8.Font = Enum.Font.SourceSansBold
AddButton8.FontSize = Enum.FontSize.Size14
AddButton8.Text = "UICorner"
AddButton8.TextScaled = false
AddButton8.TextSize = 26.00
AddButton8.TextWrapped = true

AddButton9.Parent = AddScrolling
AddButton9.BackgroundColor3 = Color3.new(1,1,1)
AddButton9.BackgroundTransparency = 0
AddButton9.Position = UDim2.new(0.49, 0, 0.4, 0)
AddButton9.TextColor3 = Color3.new(0,0,0)
AddButton9.Size = UDim2.new(0.05,0,0.25)
AddButton9.Font = Enum.Font.SourceSansBold
AddButton9.FontSize = Enum.FontSize.Size14
AddButton9.Text = "UIStroke"
AddButton9.TextScaled = false
AddButton9.TextSize = 26.00
AddButton9.TextWrapped = true

AddButton1.MouseButton1Click:Connect(function()
ScreenGuiNumber += 1
SourceCode.Text = SourceCode.Text..'local ScreenGui'..ScreenGuiNumber..' = Instance.new("ScreenGui") \
'
AddScrolling.Visible = false
AddUI("ScreenGui"..ScreenGuiNumber,"ScreenGui")
end)

AddButton2.MouseButton1Click:Connect(function()
FrameNumber += 1
SourceCode.Text = SourceCode.Text..'\
local Frame'..FrameNumber..' = Instance.new("Frame") \
'
AddScrolling.Visible = false
AddUI("Frame"..FrameNumber,"Frame")
end)

AddButton3.MouseButton1Click:Connect(function()
TextLabelNumber += 1
SourceCode.Text = SourceCode.Text..'\
local TextLabel'..TextLabelNumber..' = Instance.new("TextLabel") \
'
AddScrolling.Visible = false
AddUI("TextLabel"..TextLabelNumber,"TextLabel")
end)

AddButton4.MouseButton1Click:Connect(function()
TextButtonNumber += 1
SourceCode.Text = SourceCode.Text..'\
local TextButton'..TextButtonNumber..' = Instance.new("TextButton") \
'
AddScrolling.Visible = false
AddUI("TextButton"..TextButtonNumber,"TextButton")
end)

AddButton5.MouseButton1Click:Connect(function()
TextBoxNumber += 1
SourceCode.Text = SourceCode.Text..'\
local TextBox'..TextBoxNumber..' = Instance.new("TextBox") \
'
AddScrolling.Visible = false
AddUI("TextBox"..TextBoxNumber,"TextBox")
end)

AddButton6.MouseButton1Click:Connect(function()
ImageButtonNumber += 1
SourceCode.Text = SourceCode.Text..'\
local ImageButton'..ImageButtonNumber..' = Instance.new("ImageButton") \
'
AddScrolling.Visible = false
AddUI("ImageButton"..ImageButtonNumber,"ImageButton")
end)

AddButton7.MouseButton1Click:Connect(function()
ScrollingFrameNumber += 1
SourceCode.Text = SourceCode.Text..'\
local ScrollingFrame'..ScrollingFrameNumber..' = Instance.new("ScrollingFrame") \
'
AddScrolling.Visible = false
AddUI("ScrollingFrame"..ScrollingFrameNumber,"ScrollingFrame")
end)

AddButton8.MouseButton1Click:Connect(function()
UICornerNumber += 1
SourceCode.Text = SourceCode.Text..'\
local UICorner'..UICornerNumber..' = Instance.new("UICorner") \
'
AddScrolling.Visible = false
AddUI("UICorner"..UICornerNumber,"UICorner")
end)

AddButton9.MouseButton1Click:Connect(function()
UIStrokeNumber += 1
SourceCode.Text = SourceCode.Text..'\
local UIStroke'..UIStrokeNumber..' = Instance.new("UIStroke") \
'
AddScrolling.Visible = false
AddUI("UIStroke"..UIStrokeNumber,"UIStroke")
end)
---







local MainFrameGui = Instance.new("ScreenGui")
local MainFrame = Instance.new("Frame")
local CodeButton = Instance.new("TextButton")
local AddButton = Instance.new("TextButton")
local ClearButton = Instance.new("TextButton")
local ListButton = Instance.new("TextButton")
local ExecuteButton = Instance.new("TextButton")
local CopyButton = Instance.new("TextButton")

MainFrameGui.Parent = game.CoreGui

MainFrame.Parent = MainFrameGui
MainFrame.BackgroundColor3 = Color3.new(1,1,1)
MainFrame.BorderColor3 = Color3.new(0,0,0)
MainFrame.Position = UDim2.new(0.26,0,-0.11)
MainFrame.Size = UDim2.new(0.3,0,0.1)
MainFrame.Active = true
MainFrame.Draggable = false
MainFrame.Visible = false

CodeButton.Parent = MainFrame
CodeButton.BackgroundColor3 = Color3.new(1,1,1)
CodeButton.BackgroundTransparency = 0
CodeButton.BorderColor3 = Color3.new(0,0,0)
CodeButton.Position = UDim2.new(0, 0, 0, 0)
CodeButton.TextColor3 = Color3.new(0,0,0)
CodeButton.Size = UDim2.new(0.17,0,1,0)
CodeButton.Font = Enum.Font.SourceSansBold
CodeButton.FontSize = Enum.FontSize.Size14
CodeButton.Text = "Source Code"
CodeButton.TextScaled = false
CodeButton.TextSize = 14.00
CodeButton.TextWrapped = true
CodeButton.Draggable = false

AddButton.Parent = MainFrame
AddButton.BackgroundColor3 = Color3.new(1,1,1)
AddButton.BackgroundTransparency = 0
AddButton.BorderColor3 = Color3.new(0,0,0)
AddButton.Position = UDim2.new(0.18, 0, 0, 0)
AddButton.TextColor3 = Color3.new(0,0,0)
AddButton.Size = UDim2.new(0.17,0,1,0)
AddButton.Font = Enum.Font.SourceSansBold
AddButton.FontSize = Enum.FontSize.Size14
AddButton.Text = "+"
AddButton.TextScaled = false
AddButton.TextSize = 18.00
AddButton.TextWrapped = true
AddButton.Draggable = false

ClearButton.Parent = MainFrame
ClearButton.BackgroundColor3 = Color3.new(1,1,1)
ClearButton.BackgroundTransparency = 0
ClearButton.BorderColor3 = Color3.new(0,0,0)
ClearButton.Position = UDim2.new(0.358, 0, 0, 0)
ClearButton.TextColor3 = Color3.new(0,0,0)
ClearButton.Size = UDim2.new(0.17,0,1,0)
ClearButton.Font = Enum.Font.SourceSansBold
ClearButton.FontSize = Enum.FontSize.Size14
ClearButton.Text = "Reset"
ClearButton.TextScaled = false
ClearButton.TextSize = 14.00
ClearButton.TextWrapped = true
ClearButton.Draggable = false

ListButton.Parent = MainFrame
ListButton.BackgroundColor3 = Color3.new(1,1,1)
ListButton.BackgroundTransparency = 0
ListButton.BorderColor3 = Color3.new(0,0,0)
ListButton.Position = UDim2.new(0.538, 0, 0, 0)
ListButton.TextColor3 = Color3.new(0,0,0)
ListButton.Size = UDim2.new(0.17,0,1,0)
ListButton.Font = Enum.Font.SourceSansBold
ListButton.FontSize = Enum.FontSize.Size14
ListButton.Text = "UI List"
ListButton.TextScaled = false
ListButton.TextSize = 14.00
ListButton.TextWrapped = true
ListButton.Draggable = false

ExecuteButton.Parent = MainFrame
ExecuteButton.BackgroundColor3 = Color3.new(1,1,1)
ExecuteButton.BackgroundTransparency = 0
ExecuteButton.BorderColor3 = Color3.new(0,0,0)
ExecuteButton.Position = UDim2.new(0.716, 0, 0, 0)
ExecuteButton.TextColor3 = Color3.new(0,0,0)
ExecuteButton.Size = UDim2.new(0.17,0,1,0)
ExecuteButton.Font = Enum.Font.SourceSansBold
ExecuteButton.FontSize = Enum.FontSize.Size14
ExecuteButton.Text = "Execute"
ExecuteButton.TextScaled = false
ExecuteButton.TextSize = 12.00
ExecuteButton.TextWrapped = true
ExecuteButton.Draggable = false

CopyButton.Parent = MainFrame
CopyButton.BackgroundColor3 = Color3.new(1,1,1)
CopyButton.BackgroundTransparency = 0
CopyButton.BorderColor3 = Color3.new(0,0,0)
CopyButton.Position = UDim2.new(0.894, 0, 0, 0)
CopyButton.TextColor3 = Color3.new(0,0,0)
CopyButton.Size = UDim2.new(0.17,0,1,0)
CopyButton.Font = Enum.Font.SourceSansBold
CopyButton.FontSize = Enum.FontSize.Size14
CopyButton.Text = "Copy"
CopyButton.TextScaled = false
CopyButton.TextSize = 14.00
CopyButton.TextWrapped = true
CopyButton.Draggable = false

CodeButton.MouseButton1Click:Connect(function()
if SourceCodeScrolling.Visible == false then
   SourceCodeScrolling.Visible = true
else
   SourceCodeScrolling.Visible = false
end
end)

AddButton.MouseButton1Click:Connect(function()
if AddScrolling.Visible == false then
   AddScrolling.Visible = true
else
   AddScrolling.Visible = false
end
end)

ClearButton.MouseButton1Click:Connect(function()
function Callback(answer)
    if answer == "Reset" then
       Reset()
    end
end

Bindable = Instance.new("BindableFunction")
Bindable.OnInvoke = Callback

game.StarterGui:SetCore("SendNotification", {
    Title = "Script";
    Text = "Do you want to Reset the Source Code?";
    Duration = "2.5";
    Button1 = "Reset";
    Button2 = "Cancel";
    Callback = Bindable
})
end)

ListButton.MouseButton1Click:Connect(function()
if UIFrame.Visible == false then
   UIFrame.Visible = true
else
   UIFrame.Visible = false
end
end)

CopyButton.MouseButton1Click:Connect(function()
setclipboard(SourceCode.Text)
RequestToastMessage("Copy Successful!")
end)

ExecuteButton.MouseButton1Click:Connect(function()
loadstring(SourceCode.Text)()
end)






---Open Gui
local OpenScreenGui = Instance.new("ScreenGui")
local OpenGui = Instance.new("TextButton")

OpenScreenGui.Parent = game.CoreGui

OpenGui.Parent = OpenScreenGui
OpenGui.BackgroundColor3 = Color3.new(1,1,1)
OpenGui.BackgroundTransparency = 0.0000000001
OpenGui.Position = UDim2.new(0.2, 0, -0.11, 0)
OpenGui.TextColor3 = Color3.new(0,0,0)
OpenGui.Size = UDim2.new(0.05,0,0.1,0)
OpenGui.Font = Enum.Font.SourceSansBold
OpenGui.FontSize = Enum.FontSize.Size14
OpenGui.Text = "Open"
OpenGui.TextScaled = false
OpenGui.TextSize = 14.00
OpenGui.TextWrapped = true
OpenGui.Draggable = false

OpenGui.MouseButton1Click:connect(function()
if OpenGui.Text == "Open" then
   OpenGui.Text = "Close"
   MainFrame.Visible = true
else
   OpenGui.Text = "Open"
   MainFrame.Visible = false
   SourceCodeScrolling.Visible = false
   AddScrolling.Visible = false
   UIFrame.Visible = false
   UIScriptScrolling.Visible = false
   UIColorFrame.Visible = false
end
end)
