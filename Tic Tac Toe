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

local ScreenGui1 = Instance.new("ScreenGui") 
ScreenGui1.Parent = game.CoreGui

local Frame = Instance.new("ImageButton") 
Frame.Parent = ScreenGui1
Frame.Position = UDim2.new(0.35,0,0.125)
Frame.BackgroundColor3 = Color3.new(0,0,0)
Frame.Transparency = 0.9
Frame.Size = UDim2.new(0.3,0,0.6)
Frame.Image = "rbxassetid://130457386356523"
Frame.Draggable = true
Frame.Visible = true

local ImageButton1 = Instance.new("ImageButton") 
ImageButton1.Parent = Frame
ImageButton1.BackgroundTransparency = 0.4
ImageButton1.BackgroundColor3 = Color3.new(0,0,0)
ImageButton1.Position = UDim2.new(0,0,0)
ImageButton1.Size = UDim2.new(0.3,0,0.3)
ImageButton1.Image = "rbxassetid://113602635747658"

local ImageButton2 = Instance.new("ImageButton") 
ImageButton2.Parent = Frame
ImageButton2.BackgroundTransparency = 0.4
ImageButton2.BackgroundColor3 = Color3.new(0,0,0)
ImageButton2.Position = UDim2.new(0.35,0,0)
ImageButton2.Size = UDim2.new(0.3,0,0.3)
ImageButton2.Image = "rbxassetid://113602635747658"

local ImageButton3 = Instance.new("ImageButton") 
ImageButton3.Parent = Frame
ImageButton3.BackgroundTransparency = 0.4
ImageButton3.BackgroundColor3 = Color3.new(0,0,0)
ImageButton3.Position = UDim2.new(0.7,0,0)
ImageButton3.Size = UDim2.new(0.3,0,0.3)
ImageButton3.Image = "rbxassetid://113602635747658"

local ImageButton4 = Instance.new("ImageButton") 
ImageButton4.Parent = Frame
ImageButton4.BackgroundTransparency = 0.4
ImageButton4.BackgroundColor3 = Color3.new(0,0,0)
ImageButton4.Position = UDim2.new(0,0,0.35)
ImageButton4.Size = UDim2.new(0.3,0,0.3)
ImageButton4.Image = "rbxassetid://113602635747658"

local ImageButton5 = Instance.new("ImageButton") 
ImageButton5.Parent = Frame
ImageButton5.BackgroundTransparency = 0.4
ImageButton5.BackgroundColor3 = Color3.new(0,0,0)
ImageButton5.Position = UDim2.new(0.35,0,0.35)
ImageButton5.Size = UDim2.new(0.3,0,0.3)
ImageButton5.Image = "rbxassetid://113602635747658"

local ImageButton6 = Instance.new("ImageButton") 
ImageButton6.Parent = Frame
ImageButton6.BackgroundTransparency = 0.4
ImageButton6.BackgroundColor3 = Color3.new(0,0,0)
ImageButton6.Position = UDim2.new(0.7,0,0.35)
ImageButton6.Size = UDim2.new(0.3,0,0.3)
ImageButton6.Image = "rbxassetid://113602635747658"

local ImageButton7 = Instance.new("ImageButton") 
ImageButton7.Parent = Frame
ImageButton7.BackgroundTransparency = 0.4
ImageButton7.BackgroundColor3 = Color3.new(0,0,0)
ImageButton7.Position = UDim2.new(0,0,0.7)
ImageButton7.Size = UDim2.new(0.3,0,0.3)
ImageButton7.Image = "rbxassetid://113602635747658"

local ImageButton8 = Instance.new("ImageButton") 
ImageButton8.Parent = Frame
ImageButton8.BackgroundTransparency = 0.4
ImageButton8.BackgroundColor3 = Color3.new(0,0,0)
ImageButton8.Position = UDim2.new(0.35,0,0.7)
ImageButton8.Size = UDim2.new(0.3,0,0.3)
ImageButton8.Image = "rbxassetid://113602635747658"

local ImageButton9 = Instance.new("ImageButton") 
ImageButton9.Parent = Frame
ImageButton9.BackgroundTransparency = 0.4
ImageButton9.BackgroundColor3 = Color3.new(0,0,0)
ImageButton9.Position = UDim2.new(0.7,0,0.7)
ImageButton9.Size = UDim2.new(0.3,0,0.3)
ImageButton9.Image = "rbxassetid://113602635747658"

local InfoText = Instance.new("TextLabel") 
InfoText.Parent = Frame
InfoText.BackgroundTransparency = 1
InfoText.Position = UDim2.new(0,0,-0.15)
InfoText.Size = UDim2.new(1,0,0.1)
InfoText.Font = Enum.Font.SourceSansBold
InfoText.TextColor3 = Color3.fromRGB(242,243,243)
InfoText.Text = "Your Turn"
InfoText.TextSize = 18
InfoText.TextScaled = true
InfoText.TextWrapped = false

local BotType = "Easy"
local Turn = nil
local player1 = nil
local player2 = nil


---Choose Role Function
local function ChooseRole(self, opponent)
 local choosed = math.random(1,2)
 if choosed == 1 then
    player1 = self
    player2 = opponent
    Turn = player1
 else
    player1 = opponent
    player2 = self
    Turn = player1
 end
end
---


---Winner Detector Function
local function DetectWinner(delay)
 if delay == nil then
    delay = 0
 end
 wait(delay)
 if ImageButton1.Image == "rbxassetid://122359375732177" and ImageButton2.Image == "rbxassetid://122359375732177" and ImageButton3.Image == "rbxassetid://122359375732177" or ImageButton4.Image == "rbxassetid://122359375732177" and ImageButton5.Image == "rbxassetid://122359375732177" and ImageButton6.Image == "rbxassetid://122359375732177" or ImageButton7.Image == "rbxassetid://122359375732177" and ImageButton8.Image == "rbxassetid://122359375732177" and ImageButton9.Image == "rbxassetid://122359375732177" or ImageButton1.Image == "rbxassetid://122359375732177" and ImageButton4.Image == "rbxassetid://122359375732177" and ImageButton7.Image == "rbxassetid://122359375732177" or ImageButton2.Image == "rbxassetid://122359375732177" and ImageButton5.Image == "rbxassetid://122359375732177" and ImageButton8.Image == "rbxassetid://122359375732177" or ImageButton3.Image == "rbxassetid://122359375732177" and ImageButton6.Image == "rbxassetid://122359375732177" and ImageButton9.Image == "rbxassetid://122359375732177" or ImageButton1.Image == "rbxassetid://122359375732177" and ImageButton5.Image == "rbxassetid://122359375732177" and ImageButton9.Image == "rbxassetid://122359375732177" or ImageButton3.Image == "rbxassetid://122359375732177" and ImageButton5.Image == "rbxassetid://122359375732177" and ImageButton7.Image == "rbxassetid://122359375732177" then
    InfoText.Text = player1.." is the Winner 🏆"
    ImageButton1.Image = "rbxassetid://113602635747658"
    ImageButton2.Image = "rbxassetid://113602635747658"
    ImageButton3.Image = "rbxassetid://113602635747658"
    ImageButton4.Image = "rbxassetid://113602635747658"
    ImageButton5.Image = "rbxassetid://113602635747658"
    ImageButton6.Image = "rbxassetid://113602635747658"
    ImageButton7.Image = "rbxassetid://113602635747658"
    ImageButton8.Image = "rbxassetid://113602635747658"
    ImageButton9.Image = "rbxassetid://113602635747658"
    Turn = nil
    player1 = nil
    player2 = nil
 end
 if ImageButton1.Image == "rbxassetid://133173363576745" and ImageButton2.Image == "rbxassetid://133173363576745" and ImageButton3.Image == "rbxassetid://133173363576745" or ImageButton4.Image == "rbxassetid://133173363576745" and ImageButton5.Image == "rbxassetid://133173363576745" and ImageButton6.Image == "rbxassetid://133173363576745" or ImageButton7.Image == "rbxassetid://133173363576745" and ImageButton8.Image == "rbxassetid://133173363576745" and ImageButton9.Image == "rbxassetid://133173363576745" or ImageButton1.Image == "rbxassetid://133173363576745" and ImageButton4.Image == "rbxassetid://133173363576745" and ImageButton7.Image == "rbxassetid://133173363576745" or ImageButton2.Image == "rbxassetid://133173363576745" and ImageButton5.Image == "rbxassetid://133173363576745" and ImageButton8.Image == "rbxassetid://133173363576745" or ImageButton3.Image == "rbxassetid://133173363576745" and ImageButton6.Image == "rbxassetid://133173363576745" and ImageButton9.Image == "rbxassetid://133173363576745" or ImageButton1.Image == "rbxassetid://133173363576745" and ImageButton5.Image == "rbxassetid://133173363576745" and ImageButton9.Image == "rbxassetid://133173363576745" or ImageButton3.Image == "rbxassetid://133173363576745" and ImageButton5.Image == "rbxassetid://133173363576745" and ImageButton7.Image == "rbxassetid://133173363576745" then
    InfoText.Text = player2.." is the Winner 🏆"
    ImageButton1.Image = "rbxassetid://113602635747658"
    ImageButton2.Image = "rbxassetid://113602635747658"
    ImageButton3.Image = "rbxassetid://113602635747658"
    ImageButton4.Image = "rbxassetid://113602635747658"
    ImageButton5.Image = "rbxassetid://113602635747658"
    ImageButton6.Image = "rbxassetid://113602635747658"
    ImageButton7.Image = "rbxassetid://113602635747658"
    ImageButton8.Image = "rbxassetid://113602635747658"
    ImageButton9.Image = "rbxassetid://113602635747658"
    Turn = nil
    player1 = nil
    player2 = nil
 end
end
---


---Change Turn Function
local function ChangeTurn()
 if Turn == player1 then
    InfoText.Text = player2.." Turn"
    Turn = player2
 else
    InfoText.Text = player1.." Turn"
    Turn = player1
 end
end
---


---Drew Detector Function
local function DetectDrew()
 if ImageButton1.Image ~= "rbxassetid://113602635747658" and ImageButton2.Image ~= "rbxassetid://113602635747658" and ImageButton3.Image ~= "rbxassetid://113602635747658" and ImageButton4.Image ~= "rbxassetid://113602635747658" and ImageButton5.Image ~= "rbxassetid://113602635747658" and ImageButton6.Image ~= "rbxassetid://113602635747658" and ImageButton7.Image ~= "rbxassetid://113602635747658" and ImageButton8.Image ~= "rbxassetid://113602635747658" and ImageButton9.Image ~= "rbxassetid://113602635747658" then
    ImageButton1.Image = "rbxassetid://113602635747658"
    ImageButton2.Image = "rbxassetid://113602635747658"
    ImageButton3.Image = "rbxassetid://113602635747658"
    ImageButton4.Image = "rbxassetid://113602635747658"
    ImageButton5.Image = "rbxassetid://113602635747658"
    ImageButton6.Image = "rbxassetid://113602635747658"
    ImageButton7.Image = "rbxassetid://113602635747658"
    ImageButton8.Image = "rbxassetid://113602635747658"
    ImageButton9.Image = "rbxassetid://113602635747658"
 end
end
---


---Bot Put Function 
local function PutBot(slot, delay)
 if delay then
    delay = math.random(1,delay)
 else
    delay = 0
 end
 wait(delay)
 if Turn == nil then
    return
 end
 local botrole = nil
 if player1 == "Bot" then
    botrole = "player1"
 else
    botrole = "player2"
 end
 if slot == 1 then
    if botrole == "player1" then
       ImageButton1.Image = "rbxassetid://122359375732177"
    else
       ImageButton1.Image = "rbxassetid://133173363576745"
    end
 elseif slot == 2 then
    if botrole == "player1" then
       ImageButton2.Image = "rbxassetid://122359375732177"
    else
       ImageButton2.Image = "rbxassetid://133173363576745"
    end
 elseif slot == 3 then
    if botrole == "player1" then
       ImageButton3.Image = "rbxassetid://122359375732177"
    else
       ImageButton3.Image = "rbxassetid://133173363576745"
    end
 elseif slot == 4 then
    if botrole == "player1" then
       ImageButton4.Image = "rbxassetid://122359375732177"
    else
       ImageButton4.Image = "rbxassetid://133173363576745"
    end
 elseif slot == 5 then
    if botrole == "player1" then
       ImageButton5.Image = "rbxassetid://122359375732177"
    else
       ImageButton5.Image = "rbxassetid://133173363576745"
    end
 elseif slot == 6 then
    if botrole == "player1" then
       ImageButton6.Image = "rbxassetid://122359375732177"
    else
       ImageButton6.Image = "rbxassetid://133173363576745"
    end
 elseif slot == 7 then
    if botrole == "player1" then
       ImageButton7.Image = "rbxassetid://122359375732177"
    else
       ImageButton7.Image = "rbxassetid://133173363576745"
    end
 elseif slot == 8 then
    if botrole == "player1" then
       ImageButton8.Image = "rbxassetid://122359375732177"
    else
       ImageButton8.Image = "rbxassetid://133173363576745"
    end
 elseif slot == 9 then
    if botrole == "player1" then
       ImageButton9.Image = "rbxassetid://122359375732177"
    else
       ImageButton9.Image = "rbxassetid://133173363576745"
    end
 end
 ChangeTurn()
 DetectWinner(1)
 DetectDrew()
end
---


---Request Random Move Function
local function RequestRandomMove()
 local foundslot = false
 local slot = nil
 repeat
   local botchoosed = math.random(1,9)
   if botchoosed == 1 and ImageButton1.Image == "rbxassetid://113602635747658" then
      foundslot = true
      slot = 1
   elseif botchoosed == 2 and ImageButton2.Image == "rbxassetid://113602635747658" then
      foundslot = true
      slot = 2
   elseif botchoosed == 3 and ImageButton3.Image == "rbxassetid://113602635747658" then
      foundslot = true
      slot = 3
   elseif botchoosed == 4 and ImageButton4.Image == "rbxassetid://113602635747658" then
      foundslot = true
      slot = 4
   elseif botchoosed == 5 and ImageButton5.Image == "rbxassetid://113602635747658" then
      foundslot = true
      slot = 5
   elseif botchoosed == 6 and ImageButton6.Image == "rbxassetid://113602635747658" then
      foundslot = true
      slot = 6
   elseif botchoosed == 7 and ImageButton7.Image == "rbxassetid://113602635747658" then
      foundslot = true
      slot = 7
   elseif botchoosed == 8 and ImageButton8.Image == "rbxassetid://113602635747658" then
      foundslot = true
      slot = 8
   elseif botchoosed == 9 and ImageButton9.Image == "rbxassetid://113602635747658" then
      foundslot = true
      slot = 9
   end
 until foundslot == true
 return slot
end
---


---Request Smart Move Function
local function RequestSmartMove()
 local botrole = nil
 if player1 == "Bot" then
    botrole = "player1"
 else
    botrole = "player2"
 end
 if botrole == "player1" then
    if ImageButton1.Image == "rbxassetid://113602635747658" and ImageButton2.Image == "rbxassetid://122359375732177" and ImageButton3.Image == "rbxassetid://122359375732177" or ImageButton1.Image == "rbxassetid://113602635747658" and ImageButton4.Image == "rbxassetid://122359375732177" and ImageButton7.Image == "rbxassetid://122359375732177" or ImageButton1.Image == "rbxassetid://113602635747658" and ImageButton5.Image == "rbxassetid://122359375732177" and ImageButton9.Image == "rbxassetid://122359375732177" then
       return 1
    end
    if ImageButton2.Image == "rbxassetid://113602635747658" and ImageButton1.Image == "rbxassetid://122359375732177" and ImageButton3.Image == "rbxassetid://122359375732177" or ImageButton2.Image == "rbxassetid://113602635747658" and ImageButton5.Image == "rbxassetid://122359375732177" and ImageButton8.Image == "rbxassetid://122359375732177" then
       return 2
    end
    if ImageButton3.Image == "rbxassetid://113602635747658" and ImageButton1.Image == "rbxassetid://122359375732177" and ImageButton2.Image == "rbxassetid://122359375732177" or ImageButton3.Image == "rbxassetid://113602635747658" and ImageButton6.Image == "rbxassetid://122359375732177" and ImageButton9.Image == "rbxassetid://122359375732177" or ImageButton3.Image == "rbxassetid://113602635747658" and ImageButton5.Image == "rbxassetid://122359375732177" and ImageButton7.Image == "rbxassetid://122359375732177" then
       return 3
    end
    if ImageButton4.Image == "rbxassetid://113602635747658" and ImageButton1.Image == "rbxassetid://122359375732177" and ImageButton7.Image == "rbxassetid://122359375732177" or ImageButton4.Image == "rbxassetid://113602635747658" and ImageButton5.Image == "rbxassetid://122359375732177" and ImageButton6.Image == "rbxassetid://122359375732177" then
       return 4
    end
    if ImageButton5.Image == "rbxassetid://113602635747658" and ImageButton4.Image == "rbxassetid://122359375732177" and ImageButton6.Image == "rbxassetid://122359375732177" or ImageButton5.Image == "rbxassetid://113602635747658" and ImageButton2.Image == "rbxassetid://122359375732177" and ImageButton8.Image == "rbxassetid://122359375732177" or ImageButton5.Image == "rbxassetid://113602635747658" and ImageButton1.Image == "rbxassetid://122359375732177" and ImageButton9.Image == "rbxassetid://122359375732177" or ImageButton5.Image == "rbxassetid://113602635747658" and ImageButton3.Image == "rbxassetid://122359375732177" and ImageButton7.Image == "rbxassetid://122359375732177" then
       return 5
    end
    if ImageButton6.Image == "rbxassetid://113602635747658" and ImageButton4.Image == "rbxassetid://122359375732177" and ImageButton5.Image == "rbxassetid://122359375732177" or ImageButton6.Image == "rbxassetid://113602635747658" and ImageButton3.Image == "rbxassetid://122359375732177" and ImageButton9.Image == "rbxassetid://122359375732177" then
       return 6
    end
    if ImageButton7.Image == "rbxassetid://113602635747658" and ImageButton1.Image == "rbxassetid://122359375732177" and ImageButton4.Image == "rbxassetid://122359375732177" or ImageButton7.Image == "rbxassetid://113602635747658" and ImageButton8.Image == "rbxassetid://122359375732177" and ImageButton9.Image == "rbxassetid://122359375732177" or ImageButton7.Image == "rbxassetid://113602635747658" and ImageButton5.Image == "rbxassetid://122359375732177" and ImageButton3.Image == "rbxassetid://122359375732177" then
       return 7
    end
    if ImageButton8.Image == "rbxassetid://113602635747658" and ImageButton7.Image == "rbxassetid://122359375732177" and ImageButton9.Image == "rbxassetid://122359375732177" or ImageButton8.Image == "rbxassetid://113602635747658" and ImageButton2.Image == "rbxassetid://122359375732177" and ImageButton5.Image == "rbxassetid://122359375732177" then
       return 8
    end
    if ImageButton9.Image == "rbxassetid://113602635747658" and ImageButton7.Image == "rbxassetid://122359375732177" and ImageButton8.Image == "rbxassetid://122359375732177" or ImageButton9.Image == "rbxassetid://113602635747658" and ImageButton3.Image == "rbxassetid://122359375732177" and ImageButton6.Image == "rbxassetid://122359375732177" or ImageButton9.Image == "rbxassetid://113602635747658" and ImageButton1.Image == "rbxassetid://122359375732177" and ImageButton5.Image == "rbxassetid://122359375732177" then
       return 9
    end
    if ImageButton1.Image == "rbxassetid://113602635747658" and ImageButton2.Image == "rbxassetid://133173363576745" and ImageButton3.Image == "rbxassetid://133173363576745" or ImageButton1.Image == "rbxassetid://113602635747658" and ImageButton4.Image == "rbxassetid://133173363576745" and ImageButton7.Image == "rbxassetid://133173363576745" or ImageButton1.Image == "rbxassetid://113602635747658" and ImageButton5.Image == "rbxassetid://133173363576745" and ImageButton9.Image == "rbxassetid://133173363576745" then
       return 1
    end
    if ImageButton2.Image == "rbxassetid://113602635747658" and ImageButton1.Image == "rbxassetid://133173363576745" and ImageButton3.Image == "rbxassetid://133173363576745" or ImageButton2.Image == "rbxassetid://113602635747658" and ImageButton5.Image == "rbxassetid://133173363576745" and ImageButton8.Image == "rbxassetid://133173363576745" then
       return 2
    end
    if ImageButton3.Image == "rbxassetid://113602635747658" and ImageButton2.Image == "rbxassetid://133173363576745" and ImageButton1.Image == "rbxassetid://133173363576745" or ImageButton3.Image == "rbxassetid://113602635747658" and ImageButton6.Image == "rbxassetid://133173363576745" and ImageButton7.Image == "rbxassetid://133173363576745" then
       return 3
    end
    if ImageButton4.Image == "rbxassetid://113602635747658" and ImageButton1.Image == "rbxassetid://133173363576745" and ImageButton7.Image == "rbxassetid://133173363576745" or ImageButton4.Image == "rbxassetid://113602635747658" and ImageButton5.Image == "rbxassetid://133173363576745" and ImageButton6.Image == "rbxassetid://133173363576745" then
       return 4
    end
    if ImageButton5.Image == "rbxassetid://113602635747658" and ImageButton4.Image == "rbxassetid://133173363576745" and ImageButton6.Image == "rbxassetid://133173363576745" or ImageButton5.Image == "rbxassetid://113602635747658" and ImageButton2.Image == "rbxassetid://133173363576745" and ImageButton8.Image == "rbxassetid://133173363576745" or ImageButton5.Image == "rbxassetid://113602635747658" and ImageButton1.Image == "rbxassetid://133173363576745" and ImageButton9.Image == "rbxassetid://133173363576745" or ImageButton5.Image == "rbxassetid://113602635747658" and ImageButton3.Image == "rbxassetid://133173363576745" and ImageButton7.Image == "rbxassetid://133173363576745" then
       return 5
    end
    if ImageButton6.Image == "rbxassetid://113602635747658" and ImageButton5.Image == "rbxassetid://133173363576745" and ImageButton4.Image == "rbxassetid://133173363576745" or ImageButton6.Image == "rbxassetid://113602635747658" and ImageButton3.Image == "rbxassetid://133173363576745" and ImageButton9.Image == "rbxassetid://133173363576745" then
       return 6
    end
    if ImageButton7.Image == "rbxassetid://113602635747658" and ImageButton1.Image == "rbxassetid://133173363576745" and ImageButton4.Image == "rbxassetid://133173363576745" or ImageButton7.Image == "rbxassetid://113602635747658" and ImageButton8.Image == "rbxassetid://133173363576745" and ImageButton9.Image == "rbxassetid://133173363576745" or ImageButton7.Image == "rbxassetid://113602635747658" and ImageButton5.Image == "rbxassetid://133173363576745" and ImageButton3.Image == "rbxassetid://133173363576745" then
       return 7
    end
    if ImageButton8.Image == "rbxassetid://113602635747658" and ImageButton7.Image == "rbxassetid://133173363576745" and ImageButton9.Image == "rbxassetid://133173363576745" or ImageButton8.Image == "rbxassetid://113602635747658" and ImageButton5.Image == "rbxassetid://133173363576745" and ImageButton2.Image == "rbxassetid://133173363576745" then
       return 8
    end
    if ImageButton9.Image == "rbxassetid://113602635747658" and ImageButton8.Image == "rbxassetid://133173363576745" and ImageButton7.Image == "rbxassetid://133173363576745" or ImageButton9.Image == "rbxassetid://113602635747658" and ImageButton6.Image == "rbxassetid://133173363576745" and ImageButton3.Image == "rbxassetid://133173363576745" or ImageButton9.Image == "rbxassetid://113602635747658" and ImageButton5.Image == "rbxassetid://133173363576745" and ImageButton1.Image == "rbxassetid://133173363576745" then
       return 9
    end
 else
    if ImageButton1.Image == "rbxassetid://113602635747658" and ImageButton2.Image == "rbxassetid://133173363576745" and ImageButton3.Image == "rbxassetid://133173363576745" or ImageButton1.Image == "rbxassetid://113602635747658" and ImageButton4.Image == "rbxassetid://133173363576745" and ImageButton7.Image == "rbxassetid://133173363576745" or ImageButton1.Image == "rbxassetid://113602635747658" and ImageButton5.Image == "rbxassetid://133173363576745" and ImageButton9.Image == "rbxassetid://133173363576745" then
       return 1
    end
    if ImageButton2.Image == "rbxassetid://113602635747658" and ImageButton1.Image == "rbxassetid://133173363576745" and ImageButton3.Image == "rbxassetid://133173363576745" or ImageButton2.Image == "rbxassetid://113602635747658" and ImageButton5.Image == "rbxassetid://133173363576745" and ImageButton8.Image == "rbxassetid://133173363576745" then
       return 2
    end
    if ImageButton3.Image == "rbxassetid://113602635747658" and ImageButton1.Image == "rbxassetid://133173363576745" and ImageButton2.Image == "rbxassetid://133173363576745" or ImageButton3.Image == "rbxassetid://113602635747658" and ImageButton6.Image == "rbxassetid://133173363576745" and ImageButton9.Image == "rbxassetid://133173363576745" or ImageButton3.Image == "rbxassetid://113602635747658" and ImageButton5.Image == "rbxassetid://133173363576745" and ImageButton7.Image == "rbxassetid://133173363576745" then
       return 3
    end
    if ImageButton4.Image == "rbxassetid://113602635747658" and ImageButton1.Image == "rbxassetid://133173363576745" and ImageButton7.Image == "rbxassetid://133173363576745" or ImageButton4.Image == "rbxassetid://113602635747658" and ImageButton5.Image == "rbxassetid://133173363576745" and ImageButton6.Image == "rbxassetid://133173363576745" then
       return 4
    end
    if ImageButton5.Image == "rbxassetid://113602635747658" and ImageButton4.Image == "rbxassetid://133173363576745" and ImageButton6.Image == "rbxassetid://133173363576745" or ImageButton5.Image == "rbxassetid://113602635747658" and ImageButton2.Image == "rbxassetid://133173363576745" and ImageButton8.Image == "rbxassetid://133173363576745" or ImageButton5.Image == "rbxassetid://113602635747658" and ImageButton1.Image == "rbxassetid://133173363576745" and ImageButton9.Image == "rbxassetid://133173363576745" or ImageButton5.Image == "rbxassetid://113602635747658" and ImageButton3.Image == "rbxassetid://133173363576745" and ImageButton7.Image == "rbxassetid://133173363576745" then
       return 5
    end
    if ImageButton6.Image == "rbxassetid://113602635747658" and ImageButton4.Image == "rbxassetid://133173363576745" and ImageButton5.Image == "rbxassetid://133173363576745" or ImageButton6.Image == "rbxassetid://113602635747658" and ImageButton3.Image == "rbxassetid://133173363576745" and ImageButton9.Image == "rbxassetid://133173363576745" then
       return 6
    end
    if ImageButton7.Image == "rbxassetid://113602635747658" and ImageButton1.Image == "rbxassetid://133173363576745" and ImageButton4.Image == "rbxassetid://133173363576745" or ImageButton7.Image == "rbxassetid://113602635747658" and ImageButton8.Image == "rbxassetid://133173363576745" and ImageButton9.Image == "rbxassetid://133173363576745" or ImageButton7.Image == "rbxassetid://113602635747658" and ImageButton5.Image == "rbxassetid://133173363576745" and ImageButton3.Image == "rbxassetid://133173363576745" then
       return 7
    end
    if ImageButton8.Image == "rbxassetid://113602635747658" and ImageButton7.Image == "rbxassetid://133173363576745" and ImageButton9.Image == "rbxassetid://133173363576745" or ImageButton8.Image == "rbxassetid://113602635747658" and ImageButton2.Image == "rbxassetid://133173363576745" and ImageButton5.Image == "rbxassetid://133173363576745" then
       return 8
    end
    if ImageButton9.Image == "rbxassetid://113602635747658" and ImageButton7.Image == "rbxassetid://133173363576745" and ImageButton8.Image == "rbxassetid://133173363576745" or ImageButton9.Image == "rbxassetid://113602635747658" and ImageButton3.Image == "rbxassetid://133173363576745" and ImageButton6.Image == "rbxassetid://133173363576745" or ImageButton9.Image == "rbxassetid://113602635747658" and ImageButton1.Image == "rbxassetid://133173363576745" and ImageButton5.Image == "rbxassetid://133173363576745" then
       return 9
    end
    if ImageButton1.Image == "rbxassetid://113602635747658" and ImageButton2.Image == "rbxassetid://122359375732177" and ImageButton3.Image == "rbxassetid://122359375732177" or ImageButton1.Image == "rbxassetid://113602635747658" and ImageButton4.Image == "rbxassetid://122359375732177" and ImageButton7.Image == "rbxassetid://122359375732177" or ImageButton1.Image == "rbxassetid://113602635747658" and ImageButton5.Image == "rbxassetid://122359375732177" and ImageButton9.Image == "rbxassetid://122359375732177" then
       return 1
    end
    if ImageButton2.Image == "rbxassetid://113602635747658" and ImageButton1.Image == "rbxassetid://122359375732177" and ImageButton3.Image == "rbxassetid://122359375732177" or ImageButton2.Image == "rbxassetid://113602635747658" and ImageButton5.Image == "rbxassetid://122359375732177" and ImageButton8.Image == "rbxassetid://122359375732177" then
       return 2
    end
    if ImageButton3.Image == "rbxassetid://113602635747658" and ImageButton2.Image == "rbxassetid://122359375732177" and ImageButton1.Image == "rbxassetid://122359375732177" or ImageButton3.Image == "rbxassetid://113602635747658" and ImageButton6.Image == "rbxassetid://122359375732177" and ImageButton7.Image == "rbxassetid://122359375732177" then
       return 3
    end
    if ImageButton4.Image == "rbxassetid://113602635747658" and ImageButton1.Image == "rbxassetid://122359375732177" and ImageButton7.Image == "rbxassetid://122359375732177" or ImageButton4.Image == "rbxassetid://113602635747658" and ImageButton5.Image == "rbxassetid://122359375732177" and ImageButton6.Image == "rbxassetid://122359375732177" then
       return 4
    end
    if ImageButton5.Image == "rbxassetid://113602635747658" and ImageButton4.Image == "rbxassetid://122359375732177" and ImageButton6.Image == "rbxassetid://122359375732177" or ImageButton5.Image == "rbxassetid://113602635747658" and ImageButton2.Image == "rbxassetid://122359375732177" and ImageButton8.Image == "rbxassetid://122359375732177" or ImageButton5.Image == "rbxassetid://113602635747658" and ImageButton1.Image == "rbxassetid://122359375732177" and ImageButton9.Image == "rbxassetid://122359375732177" or ImageButton5.Image == "rbxassetid://113602635747658" and ImageButton3.Image == "rbxassetid://122359375732177" and ImageButton7.Image == "rbxassetid://122359375732177" then
       return 5
    end
    if ImageButton6.Image == "rbxassetid://113602635747658" and ImageButton5.Image == "rbxassetid://122359375732177" and ImageButton4.Image == "rbxassetid://122359375732177" or ImageButton6.Image == "rbxassetid://113602635747658" and ImageButton3.Image == "rbxassetid://122359375732177" and ImageButton9.Image == "rbxassetid://122359375732177" then
       return 6
    end
    if ImageButton7.Image == "rbxassetid://113602635747658" and ImageButton1.Image == "rbxassetid://122359375732177" and ImageButton4.Image == "rbxassetid://122359375732177" or ImageButton7.Image == "rbxassetid://113602635747658" and ImageButton8.Image == "rbxassetid://122359375732177" and ImageButton9.Image == "rbxassetid://122359375732177" or ImageButton7.Image == "rbxassetid://113602635747658" and ImageButton5.Image == "rbxassetid://122359375732177" and ImageButton3.Image == "rbxassetid://122359375732177" then
       return 7
    end
    if ImageButton8.Image == "rbxassetid://113602635747658" and ImageButton7.Image == "rbxassetid://122359375732177" and ImageButton9.Image == "rbxassetid://122359375732177" or ImageButton8.Image == "rbxassetid://113602635747658" and ImageButton5.Image == "rbxassetid://122359375732177" and ImageButton2.Image == "rbxassetid://122359375732177" then
       return 8
    end
    if ImageButton9.Image == "rbxassetid://113602635747658" and ImageButton8.Image == "rbxassetid://122359375732177" and ImageButton7.Image == "rbxassetid://122359375732177" or ImageButton9.Image == "rbxassetid://113602635747658" and ImageButton6.Image == "rbxassetid://122359375732177" and ImageButton3.Image == "rbxassetid://122359375732177" or ImageButton9.Image == "rbxassetid://113602635747658" and ImageButton5.Image == "rbxassetid://122359375732177" and ImageButton1.Image == "rbxassetid://122359375732177" then
       return 9
    end
 end
 if BotType == "Hard" then
    if ImageButton5.Image == "rbxassetid://113602635747658" then
       return 5
    end
 end
 return RequestRandomMove()
end
---


---Bot AI Operator
local BetterLoopOperator = false
game:GetService('RunService').RenderStepped:Connect(function()
if Turn == "Bot" and BetterLoopOperator == false then
   BetterLoopOperator = true
   if BotType == "Easy" then
      local botchoosed = math.random(1,9)
      if botchoosed == 1 and ImageButton1.Image == "rbxassetid://113602635747658" then
         PutBot(1, 3)
      elseif botchoosed == 2 and ImageButton2.Image == "rbxassetid://113602635747658" then
         PutBot(2, 3)
      elseif botchoosed == 3 and ImageButton3.Image == "rbxassetid://113602635747658" then
         PutBot(3, 3)
      elseif botchoosed == 4 and ImageButton4.Image == "rbxassetid://113602635747658" then
         PutBot(4, 3)
      elseif botchoosed == 5 and ImageButton5.Image == "rbxassetid://113602635747658" then
         PutBot(5, 3)
      elseif botchoosed == 6 and ImageButton6.Image == "rbxassetid://113602635747658" then
         PutBot(6, 3)
      elseif botchoosed == 7 and ImageButton7.Image == "rbxassetid://113602635747658" then
         PutBot(7, 3)
      elseif botchoosed == 8 and ImageButton8.Image == "rbxassetid://113602635747658" then
         PutBot(8, 3)
      elseif botchoosed == 9 and ImageButton9.Image == "rbxassetid://113602635747658" then
         PutBot(9, 3)
      end
   end
   if BotType == "Medium" then
      if ImageButton1.Image == "rbxassetid://113602635747658" or ImageButton2.Image == "rbxassetid://113602635747658" or ImageButton3.Image == "rbxassetid://113602635747658" or ImageButton4.Image == "rbxassetid://113602635747658" or ImageButton5.Image == "rbxassetid://113602635747658" or ImageButton6.Image == "rbxassetid://113602635747658" or ImageButton7.Image == "rbxassetid://113602635747658" or ImageButton8.Image == "rbxassetid://113602635747658" or ImageButton9.Image == "rbxassetid://113602635747658" then
         local botchoosed = math.random(1,3)
         if botchoosed == 1 or botchoosed == 2 then
            PutBot(RequestSmartMove(), 2)
         else
            PutBot(RequestRandomMove(), 2)
         end
      end
   end
   if BotType == "Hard" then
      if ImageButton1.Image == "rbxassetid://113602635747658" or ImageButton2.Image == "rbxassetid://113602635747658" or ImageButton3.Image == "rbxassetid://113602635747658" or ImageButton4.Image == "rbxassetid://113602635747658" or ImageButton5.Image == "rbxassetid://113602635747658" or ImageButton6.Image == "rbxassetid://113602635747658" or ImageButton7.Image == "rbxassetid://113602635747658" or ImageButton8.Image == "rbxassetid://113602635747658" or ImageButton9.Image == "rbxassetid://113602635747658" then
         PutBot(RequestSmartMove())
      end
   end
   BetterLoopOperator = false
end
end)
---


---Request Restart Function
local function Restart()
 local Turn = nil
 local player1 = nil
 local player2 = nil
 ImageButton1.Image = "rbxassetid://113602635747658"
 ImageButton2.Image = "rbxassetid://113602635747658"
 ImageButton3.Image = "rbxassetid://113602635747658"
 ImageButton4.Image = "rbxassetid://113602635747658"
 ImageButton5.Image = "rbxassetid://113602635747658"
 ImageButton6.Image = "rbxassetid://113602635747658"
 ImageButton7.Image = "rbxassetid://113602635747658"
 ImageButton8.Image = "rbxassetid://113602635747658"
 ImageButton9.Image = "rbxassetid://113602635747658"
 ChooseRole(game.Players.LocalPlayer.Name, "Bot")
end
---


ImageButton1.MouseButton1Click:Connect(function()
if Turn == game.Players.LocalPlayer.Name and ImageButton1.Image == "rbxassetid://113602635747658" then
   if player1 == game.Players.LocalPlayer.Name then
      ImageButton1.Image = "rbxassetid://122359375732177"
   else
      ImageButton1.Image = "rbxassetid://133173363576745"
   end
   ChangeTurn()
   DetectWinner(1)
   DetectDrew()
end
end)

ImageButton2.MouseButton1Click:Connect(function()
if Turn == game.Players.LocalPlayer.Name and ImageButton2.Image == "rbxassetid://113602635747658" then
   if player1 == game.Players.LocalPlayer.Name then
      ImageButton2.Image = "rbxassetid://122359375732177"
   else
      ImageButton2.Image = "rbxassetid://133173363576745"
   end
   ChangeTurn()
   DetectWinner(1)
   DetectDrew()
end
end)

ImageButton3.MouseButton1Click:Connect(function()
if Turn == game.Players.LocalPlayer.Name and ImageButton3.Image == "rbxassetid://113602635747658" then
   if player1 == game.Players.LocalPlayer.Name then
      ImageButton3.Image = "rbxassetid://122359375732177"
   else
      ImageButton3.Image = "rbxassetid://133173363576745"
   end
   ChangeTurn()
   DetectWinner(1)
   DetectDrew()
end
end)

ImageButton4.MouseButton1Click:Connect(function()
if Turn == game.Players.LocalPlayer.Name and ImageButton4.Image == "rbxassetid://113602635747658" then
   if player1 == game.Players.LocalPlayer.Name then
      ImageButton4.Image = "rbxassetid://122359375732177"
   else
      ImageButton4.Image = "rbxassetid://133173363576745"
   end
   ChangeTurn()
   DetectWinner(1)
   DetectDrew()
end
end)

ImageButton5.MouseButton1Click:Connect(function()
if Turn == game.Players.LocalPlayer.Name and ImageButton5.Image == "rbxassetid://113602635747658" then
   if player1 == game.Players.LocalPlayer.Name then
      ImageButton5.Image = "rbxassetid://122359375732177"
   else
      ImageButton5.Image = "rbxassetid://133173363576745"
   end
   ChangeTurn()
   DetectWinner(1)
   DetectDrew()
end
end)

ImageButton6.MouseButton1Click:Connect(function()
if Turn == game.Players.LocalPlayer.Name and ImageButton6.Image == "rbxassetid://113602635747658" then
   if player1 == game.Players.LocalPlayer.Name then
      ImageButton6.Image = "rbxassetid://122359375732177"
   else
      ImageButton6.Image = "rbxassetid://133173363576745"
   end
   ChangeTurn()
   DetectWinner(1)
   DetectDrew()
end
end)

ImageButton7.MouseButton1Click:Connect(function()
if Turn == game.Players.LocalPlayer.Name and ImageButton7.Image == "rbxassetid://113602635747658" then
   if player1 == game.Players.LocalPlayer.Name then
      ImageButton7.Image = "rbxassetid://122359375732177"
   else
      ImageButton7.Image = "rbxassetid://133173363576745"
   end
   ChangeTurn()
   DetectWinner(1)
   DetectDrew()
end
end)

ImageButton8.MouseButton1Click:Connect(function()
if Turn == game.Players.LocalPlayer.Name and ImageButton8.Image == "rbxassetid://113602635747658" then
   if player1 == game.Players.LocalPlayer.Name then
      ImageButton8.Image = "rbxassetid://122359375732177"
   else
      ImageButton8.Image = "rbxassetid://133173363576745"
   end
   ChangeTurn()
   DetectWinner(1)
   DetectDrew()
end
end)

ImageButton9.MouseButton1Click:Connect(function()
if Turn == game.Players.LocalPlayer.Name and ImageButton9.Image == "rbxassetid://113602635747658" then
   if player1 == game.Players.LocalPlayer.Name then
      ImageButton9.Image = "rbxassetid://122359375732177"
   else
      ImageButton9.Image = "rbxassetid://133173363576745"
   end
   ChangeTurn()
   DetectWinner(1)
   DetectDrew()
end
end)


ChooseRole(game.Players.LocalPlayer.Name, "Bot")
InfoText.Text = Turn.." Turn"

local Frame1 = Instance.new("Frame") 
Frame1.Parent = ScreenGui1
Frame1.BackgroundColor3 = Color3.fromRGB(17,17,17)
Frame1.BackgroundTransparency = 0.3
Frame1.BorderSizePixel = 0
Frame1.BorderColor3 = Color3.fromRGB(242,243,243)
Frame1.Position = UDim2.new(0.7,0,0)
Frame1.Size = UDim2.new(0.29,0,0.6)
Frame1.Active = true
Frame1.Draggable = false

local TextButton1 = Instance.new("TextButton") 
TextButton1.Parent = Frame1
TextButton1.BackgroundColor3 = Color3.fromRGB(17,17,17)
TextButton1.BackgroundTransparency = 0.3
TextButton1.BorderSizePixel = 1
TextButton1.BorderColor3 = Color3.fromRGB(242,243,243)
TextButton1.Position = UDim2.new(0.05,0,0.05)
TextButton1.Size = UDim2.new(0.3,0,0.15)
TextButton1.Font = Enum.Font.SourceSansBold
TextButton1.TextColor3 = Color3.fromRGB(242,243,243)
TextButton1.Text = "Restart"
TextButton1.TextSize = 18
TextButton1.TextScaled = true
TextButton1.TextWrapped = true

local TextLabel1 = Instance.new("TextLabel") 
TextLabel1.Parent = Frame1
TextLabel1.BackgroundColor3 = Color3.fromRGB(17,17,17)
TextLabel1.BackgroundTransparency = 1
TextLabel1.Position = UDim2.new(0.43,0,0.05)
TextLabel1.Size = UDim2.new(0.5,0,0.15)
TextLabel1.Font = Enum.Font.SourceSansBold
TextLabel1.TextColor3 = Color3.fromRGB(242,243,243)
TextLabel1.Text = "AI Bot Level"
TextLabel1.TextSize = 18
TextLabel1.TextScaled = true
TextLabel1.TextWrapped = true

local TextButton2 = Instance.new("TextButton") 
TextButton2.Parent = Frame1
TextButton2.BackgroundColor3 = Color3.fromRGB(17,17,17)
TextButton2.BackgroundTransparency = 0.3
TextButton2.BorderSizePixel = 1
TextButton2.BorderColor3 = Color3.fromRGB(242,243,243)
TextButton2.Position = UDim2.new(0.43,0,0.25)
TextButton2.Size = UDim2.new(0.5,0,0.15)
TextButton2.Font = Enum.Font.SourceSansBold
TextButton2.TextColor3 = Color3.fromRGB(242,243,243)
TextButton2.Text = "Hard"
TextButton2.TextSize = 18
TextButton2.TextScaled = true
TextButton2.TextWrapped = true

local TextButton3 = TextButton2:Clone()
TextButton3.Parent = Frame1
TextButton3.Position = UDim2.new(0.43,0,0.5)
TextButton3.Text = "Medium"

local TextButton4 = TextButton2:Clone()
TextButton4.Parent = Frame1
TextButton4.Position = UDim2.new(0.43,0,0.75)
TextButton4.Text = "Easy"

local TextButton5 = TextButton2:Clone()
TextButton5.Parent = ScreenGui1
TextButton5.BorderSizePixel = 0
TextButton5.Position = UDim2.new(0.651,0,0)
TextButton5.Size = UDim2.new(0.049,0,0.1)
TextButton5.Text = "–"

local TextLabel2 = Instance.new("TextLabel") 
TextLabel2.Parent = Frame1
TextLabel2.BackgroundColor3 = Color3.fromRGB(17,17,17)
TextLabel2.BackgroundTransparency = 1
TextLabel2.Position = UDim2.new(0.02,0,0.4)
TextLabel2.Size = UDim2.new(0.38,0,0.2)
TextLabel2.Font = Enum.Font.SourceSansBold
TextLabel2.TextColor3 = Color3.fromRGB(242,243,243)
TextLabel2.Text = "AI Bot Level\
Easy"
TextLabel2.TextSize = 18
TextLabel2.TextScaled = true
TextLabel2.TextWrapped = true

TextButton1.MouseButton1Click:Connect(function()
Restart()
end)

TextButton2.MouseButton1Click:Connect(function()
TextLabel2.Text = "AI Bot Level\
Hard"
BotType = "Hard"
Restart()
end)

TextButton3.MouseButton1Click:Connect(function()
TextLabel2.Text = "AI Bot Level\
Medium"
BotType = "Medium"
Restart()
end)

TextButton4.MouseButton1Click:Connect(function()
TextLabel2.Text = "AI Bot Level\
Easy"
BotType = "Easy"
Restart()
end)

TextButton5.MouseButton1Click:Connect(function()
if Frame.Visible == true then
   TextButton5.Position = UDim2.new(0.941,0,0)
   Frame.Visible = false
   Frame1.Visible = false
else
   TextButton5.Position = UDim2.new(0.651,0,0)
   Frame.Visible = true
   Frame1.Visible = true
end
end)
