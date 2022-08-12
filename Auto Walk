local CoreGui = game:GetService("StarterGui")

CoreGui:SetCore("SendNotification", {
    Title = "Script",
    Text = "Loading...",
    Duration = 5,
})
wait(4)
local CoreGui = game:GetService("StarterGui")

local Library =
   loadstring(game:HttpGet("https://raw.githubusercontent.com/preztel/AzureLibrary/master/uilib.lua", true))()

local AutoTab = Library:CreateTab("Auto Walk")

AutoTab:CreateToggle(
   "↑",
   function(ssse1)
       _G.s1s1 = ssse1 or false
       while _G.s1s1 and wait(.1) do
           local vim = game:service("VirtualInputManager")
           vim:SendKeyEvent(true, "W", false, game)
       end
   end)
   
AutoTab:CreateToggle(
    "←",
   function(ssse1)
       _G.s1s1 = ssse1 or false
       while _G.s1s1 and wait(.1) do
           local vim = game:service("VirtualInputManager")
           vim:SendKeyEvent(true, "A", false, game)
       end
   end)
   
AutoTab:CreateToggle(
    "→",
   function(ssse1)
       _G.s1s1 = ssse1 or false
       while _G.s1s1 and wait(.1) do
           local vim = game:service("VirtualInputManager")
           vim:SendKeyEvent(true, "D", false, game)
       end
   end)
   
AutoTab:CreateToggle(
    "↓",
   function(ssse1)
       _G.s1s1 = ssse1 or false
       while _G.s1s1 and wait(.1) do
           local vim = game:service("VirtualInputManager")
           vim:SendKeyEvent(true, "S", false, game)
       end
   end)


wait()
local CoreGui = game:GetService("StarterGui")

CoreGui:SetCore("SendNotification", {
    Title = "Script Creator By",
    Text = "GhostPlayer",
    Duration = 2.5,
})
