--[[ Request Toast Message Function
RequestToastMessage("Hello World", 2) --Use this to request toast message notification
--]]

function RequestToastMessage(msg,delay)
 local ToastMessage = msg
 local ToastDisappearTime = 2
 if delay then
    ToastDisappearTime = delay 
 end

 local ToastSizeOperator = nil
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
 local Text = Instance.new("TextLabel")
 local ToastUICorner = Instance.new("UICorner")

 ToastGui.Parent = game.CoreGui

 Text.Parent = ToastGui
 Text.BackgroundColor3 = Color3.new(1,1,1)
 Text.BackgroundTransparency = 0
 Text.Position = UDim2.new(0.5 - ToastSize / 2, 1, 0.775, 1)
 Text.TextColor3 = Color3.new(0,0,0)
 Text.Size = UDim2.new(ToastSize,1,0.15)
 Text.Font = Enum.Font.SourceSansSemibold
 Text.FontSize = Enum.FontSize.Size14
 Text.Text = ToastMessage
 Text.TextScaled = false
 Text.TextSize = 20
 Text.TextWrapped = true
 Text.Transparency = 1

 ToastUICorner.CornerRadius = UDim.new(10, 0)
 ToastUICorner.Parent = Text

 while Text.Transparency >= 0 do
   wait(.000000001)
   Text.Transparency -= .1
 end

 wait(ToastDisappearTime)
 while Text.Transparency <= 1.1 do
   wait(.000000001)
   Text.Transparency += .1
   if Text.Transparency == 1.1 or Text.Transparency >= 1.1 then
      ToastGui:Destroy()
   end
 end
end
