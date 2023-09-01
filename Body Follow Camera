local Camera = game.Workspace.CurrentCamera
local Player = game.Players.LocalPlayer
local Mouse = Player:GetMouse()

local Angles = CFrame.Angles
local aSin = math.asin
local aTan = math.atan
local MseGuide = true
local TurnCharacterToMouse = false
local HeadHorFactor = 1
local HeadVertFactor = 1
local CharacterHorFactor = 1
local CharacterVertFactor = 1
local UpdateSpeed = 0.3

if TurnCharacterToMouse == true then
	MseGuide = true
	HeadHorFactor = 0
	CharacterHorFactor = 0
end

Player.CharacterAdded:Connect(function(char)
	local Character = char
	local Head = Character:WaitForChild("Head")
	local Humanoid = Character:WaitForChild("Humanoid")
	local HumanoidRootPart = Character:WaitForChild("HumanoidRootPart")
	local IsR6 = (Humanoid.RigType.Value==0)
	local Torso = (IsR6 and Character:WaitForChild("Torso")) or Character:WaitForChild("UpperTorso")
	local Neck = (IsR6 and Torso:WaitForChild("Neck")) or Head:WaitForChild("Neck")
	local Waist = (not IsR6 and Torso:WaitForChild("Waist"))
	
	local NeckOrgnC0 = Neck.C0
	local WaistOrgnC0 = (not IsR6 and Waist.C0)
	Neck.MaxVelocity = 3/5
	game:GetService("RunService").RenderStepped:Connect(function()
		local CameraCF = Camera.CoordinateFrame
		if ((IsR6 and Character["Torso"]) or Character["UpperTorso"])~=nil and Character["Head"]~=nil then
			local TorsoLV = Torso.CFrame.lookVector
			local HdPos = Head.CFrame.p
			if IsR6 and Neck or Neck and Waist then
				if Camera.CameraSubject:IsDescendantOf(Character) or Camera.CameraSubject:IsDescendantOf(Player) then
					local Dist = nil;
					local Diff = nil;
					if not MseGuide then
						Dist = (Head.CFrame.p-CameraCF.p).magnitude
						Diff = Head.CFrame.Y-CameraCF.Y
						if not IsR6 then
							Neck.C0 = Neck.C0:lerp(NeckOrgnC0*Angles((aSin(Diff/Dist)*HeadVertFactor), -(((HdPos-CameraCF.p).Unit):Cross(TorsoLV)).Y*HeadHorFactor, 0), UpdateSpeed/2)
							Waist.C0 = Waist.C0:lerp(WaistOrgnC0*Angles((aSin(Diff/Dist)*CharacterVertFactor), -(((HdPos-CameraCF.p).Unit):Cross(TorsoLV)).Y*CharacterHorFactor, 0), UpdateSpeed/2)
						else
							Neck.C0 = Neck.C0:lerp(NeckOrgnC0*Angles(-(aSin(Diff/Dist)*HeadVertFactor), 0, -(((HdPos-CameraCF.p).Unit):Cross(TorsoLV)).Y*HeadHorFactor),UpdateSpeed/2)
						end
					else
						local Point = Mouse.Hit.p
						Dist = (Head.CFrame.p-Point).magnitude
						Diff = Head.CFrame.Y-Point.Y
						if not IsR6 then
							Neck.C0 = Neck.C0:lerp(NeckOrgnC0*Angles(-(aTan(Diff/Dist)*HeadVertFactor), (((HdPos-Point).Unit):Cross(TorsoLV)).Y*HeadHorFactor, 0), UpdateSpeed/2)
							Waist.C0 = Waist.C0:lerp(WaistOrgnC0*Angles(-(aTan(Diff/Dist)*CharacterVertFactor), (((HdPos-Point).Unit):Cross(TorsoLV)).Y*CharacterHorFactor, 0), UpdateSpeed/2)
						else
							Neck.C0 = Neck.C0:lerp(NeckOrgnC0*Angles((aTan(Diff/Dist)*HeadVertFactor), 0, (((HdPos-Point).Unit):Cross(TorsoLV)).Y*HeadHorFactor), UpdateSpeed/2)
						end
					end
				end
			end
		end
		if TurnCharacterToMouse == true then
			Humanoid.AutoRotate = false
			HumanoidRootPart.CFrame = HumanoidRootPart.CFrame:lerp(CFrame.new(HumanoidRootPart.Position, Vector3.new(Mouse.Hit.p.x, HumanoidRootPart.Position.Y, Mouse.Hit.p.z)), UpdateSpeed / 2)
		else
			Humanoid.AutoRotate = true
		end
	end)
end)


wait()
game.Players.LocalPlayer.Character.Humanoid.Health = 0
wait()
local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local Text = Instance.new("TextButton")


ScreenGui.Parent = game.CoreGui

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.new(0,0,0)
Frame.BorderColor3 = Color3.new(0,0,0)
Frame.Position = UDim2.new(0.00001,0.0009,0)
Frame.Size = UDim2.new(2,0.2,0.08)
Frame.Active = true
Frame.Draggable = false

Text.Parent = Frame
Text.BackgroundColor3 = Color3.new(0,0,0)
Text.BackgroundTransparency = 100
Text.Position = UDim2.new(0,0,0.1)
Text.Size = UDim2.new(0.5,0.9,0.6)
Text.TextColor3 = Color3.new(1,1,1)
Text.Text = "Script Made By GhostPlayer"
Text.TextScaled = true
Text.TextSize = 8
Text.TextWrapped = true
wait(5)
ScreenGui:Destroy()
