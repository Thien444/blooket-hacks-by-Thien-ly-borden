# blooket-hacks-by-Thien-ly-borden

hack 1: Object.values(document.querySelector("#app > div > div"))[1].children[0]._owner.stateNode.setState({ unlocks: Object.values(webpackJsonp.push([[], { ['']: (_, a, b) => { a.cache = b.c }, }, [['']],]).cache).find(x=>x.exports?.a?.toString().includes('UFO')).exports.a.toString().split('"').filter(b => !(b.startsWith(';') || b.startsWith(':') || b.startsWith('function') || b.startsWith('}'))) }); alert("Made by Thien")


hack 2: -- Gui to Lua
-- Version: 3

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local RedXGUI = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local speed = Instance.new("TextButton")
local gravity = Instance.new("TextButton")
local clickTP = Instance.new("TextButton")
local btools = Instance.new("TextButton")
local autocash = Instance.new("TextButton")
local fling = Instance.new("TextButton")
local fps = Instance.new("TextButton")
local speed_2 = Instance.new("TextButton")
local TextLabel_3 = Instance.new("TextLabel")
local close = Instance.new("TextButton")
local TextLabel_4 = Instance.new("TextLabel")
local open = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

RedXGUI.Name = "RedXGUI"
RedXGUI.Parent = ScreenGui
RedXGUI.BackgroundColor3 = Color3.new(0.666667, 1, 1)
RedXGUI.BorderSizePixel = 4
RedXGUI.Position = UDim2.new(0.465026885, 0, 0.275590599, 0)
RedXGUI.Size = UDim2.new(0, 535, 0, 338)
RedXGUI.Visible = false
RedXGUI.Active = true
RedXGUI.Draggable = true

TextLabel.Parent = RedXGUI
TextLabel.BackgroundColor3 = Color3.new(0.435294, 0.168627, 0.52549)
TextLabel.BorderColor3 = Color3.new(0, 0, 0)
TextLabel.BorderSizePixel = 3
TextLabel.Position = UDim2.new(0.0200752541, 0, -0.0384615362, 0)
TextLabel.Size = UDim2.new(0, 200, 0, 50)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "REDX  ADOPTME- TURNINGGLOBE"
TextLabel.TextColor3 = Color3.new(0, 0, 0)
TextLabel.TextSize = 14

TextLabel_2.Parent = RedXGUI
TextLabel_2.BackgroundColor3 = Color3.new(0.262745, 0.0666667, 0.435294)
TextLabel_2.BorderColor3 = Color3.new(0, 0, 0)
TextLabel_2.BorderSizePixel = 3
TextLabel_2.Position = UDim2.new(-0.287850469, 0, 0.514792919, 0)
TextLabel_2.Rotation = 90
TextLabel_2.Size = UDim2.new(0, 289, 0, 11)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = ""
TextLabel_2.TextColor3 = Color3.new(0, 0, 0)
TextLabel_2.TextSize = 14

speed.Name = "speed"
speed.Parent = RedXGUI
speed.BackgroundColor3 = Color3.new(0.666667, 0, 0)
speed.BackgroundTransparency = 0.5
speed.BorderColor3 = Color3.new(0.258824, 0.0901961, 0.4)
speed.BorderSizePixel = 3
speed.Position = UDim2.new(0.0186915882, 0, 0.189349115, 0)
speed.Size = UDim2.new(0, 137, 0, 31)
speed.Font = Enum.Font.Gotham
speed.Text = "SPEED[X]"
speed.TextColor3 = Color3.new(0, 0, 0)
speed.TextScaled = true
speed.TextSize = 14
speed.TextWrapped = true
speed.MouseButton1Down:connect(function()
	local walkspeedplayer = game:GetService("Players").LocalPlayer
	local walkspeedmouse = walkspeedplayer:GetMouse()
	
	local walkspeedenabled = false
	
	function x_walkspeed(key)
		if (key == "x") then
			if walkspeedenabled == false then
				_G.WS = 200;
				local Humanoid = game:GetService("Players").LocalPlayer.Character.Humanoid;
				Humanoid:GetPropertyChangedSignal("WalkSpeed"):Connect(function()
				Humanoid.WalkSpeed = _G.WS;
				end)
				Humanoid.WalkSpeed = _G.WS;
				
				walkspeedenabled = true
			elseif walkspeedenabled == true then
				_G.WS = 20;
				local Humanoid = game:GetService("Players").LocalPlayer.Character.Humanoid;
				Humanoid:GetPropertyChangedSignal("WalkSpeed"):Connect(function()
				Humanoid.WalkSpeed = _G.WS;
				end)
				Humanoid.WalkSpeed = _G.WS;
				
				walkspeedenabled = false
			end
		end
	end
	
	walkspeedmouse.KeyDown:connect(x_walkspeed)
	
end)

gravity.Name = "gravity"
gravity.Parent = RedXGUI
gravity.BackgroundColor3 = Color3.new(0.666667, 0, 0)
gravity.BackgroundTransparency = 0.5
gravity.BorderColor3 = Color3.new(0.258824, 0.0901961, 0.4)
gravity.BorderSizePixel = 3
gravity.Position = UDim2.new(0.355140209, 0, 0.189349115, 0)
gravity.Size = UDim2.new(0, 137, 0, 31)
gravity.Font = Enum.Font.Gotham
gravity.Text = "GRAVITY"
gravity.TextColor3 = Color3.new(0, 0, 0)
gravity.TextScaled = true
gravity.TextSize = 14
gravity.TextWrapped = true
gravity.MouseButton1Down:connect(function()
if Gravity == true then
Gravity = false
game.workspace.Gravity = 196.2
else
Gravity = true
game.workspace.Gravity = 45
end
end)

clickTP.Name = "clickTP"
clickTP.Parent = RedXGUI
clickTP.BackgroundColor3 = Color3.new(0.666667, 0, 0)
clickTP.BackgroundTransparency = 0.5
clickTP.BorderColor3 = Color3.new(0.258824, 0.0901961, 0.4)
clickTP.BorderSizePixel = 3
clickTP.Position = UDim2.new(0.693457961, 0, 0.189349115, 0)
clickTP.Size = UDim2.new(0, 137, 0, 31)
clickTP.Font = Enum.Font.Gotham
clickTP.Text = "CLICKTP[N]"
clickTP.TextColor3 = Color3.new(0, 0, 0)
clickTP.TextScaled = true
clickTP.TextSize = 14
clickTP.TextWrapped = true
clickTP.MouseButton1Click:Connect(function()
	toggle = true
    togglekey = "n" --Key that you will use to toggle the on and off
    killkey   = "k" --Key that you will use to kill a player
    function Hint(txt)
        local b = Instance.new('Hint', workspace)
        b.Text = txt
        wait(2)
        b:Destroy()
    end
    Local = game:GetService('Players').LocalPlayer
    Mouse = Local:GetMouse()
    Mouse.Button1Down:connect(function()
        pcall(function()
            if toggle then
                Local.Character.HumanoidRootPart.CFrame = Local:GetMouse().Hit
            end
        end)
    end)
    Mouse.KeyDown:connect(function(key)
        if key == togglekey then
            if toggle then
                toggle = false
                Hint('Turned Off!')
                print ('Turned Off!')
            else
                toggle = true
                Hint('Turned On!')
                print ('Turned On!')
            end
        elseif key == killkey then
            if toggle then
                pcall(function()
                    Mouse.Target.Parent:FindFirstChild('Humanoid').Health = 0
                    Hint('Killed ' .. Mouse.Target.Parent.Name)
                end)
            end
        end
    end)
end)

btools.Name = "btools"
btools.Parent = RedXGUI
btools.BackgroundColor3 = Color3.new(0.666667, 0, 0)
btools.BackgroundTransparency = 0.5
btools.BorderColor3 = Color3.new(0.258824, 0.0901961, 0.4)
btools.BorderSizePixel = 3
btools.Position = UDim2.new(0.0186915882, 0, 0.423076928, 0)
btools.Size = UDim2.new(0, 137, 0, 31)
btools.Font = Enum.Font.Gotham
btools.Text = "BTOOLS"
btools.TextColor3 = Color3.new(0, 0, 0)
btools.TextScaled = true
btools.TextSize = 14
btools.TextWrapped = true
btools.MouseButton1Down:connect(function()
	game.StarterGui:SetCoreGuiEnabled(Enum.CoreGuiType.Backpack, true)
for index, child in pairs(game:GetService("Workspace"):GetChildren()) do
   if child.ClassName == "Part" then
       child.Locked = false
   end
   if child.ClassName == "MeshPart" then
       child.Locked = false
   end
   if child.ClassName == "UnionOperation" then
       child.Locked = false
   end
   if child.ClassName == "Model" then
       for index, chil in pairs(child:GetChildren()) do
           if chil.ClassName == "Part" then
               chil.Locked = false
           end
           if chil.ClassName == "MeshPart" then
               chil.Locked = false
           end
           if chil.ClassName == "UnionOperation" then
               chil.Locked = false
           end
           if chil.ClassName == "Model" then
               for index, childe in pairs(chil:GetChildren()) do
                   if childe.ClassName == "Part" then
                       childe.Locked = false
                   end
                   if childe.ClassName == "MeshPart" then
                       childe.Locked = false
                   end
                   if childe.ClassName == "UnionOperation" then
                       childe.Locked = false
                   end
                   if childe.ClassName == "Model" then
                       for index, childeo in pairs(childe:GetChildren()) do
                           if childeo.ClassName == "Part" then
                               childeo.Locked = false
                           end
                           if childeo.ClassName == "MeshPart" then
                               childeo.Locked = false
                           end
                           if childeo.ClassName == "UnionOperation" then
                               childeo.Locked = false
                           end
                           if childeo.ClassName == "Model" then
                           end
                       end
                   end
               end
           end
       end
   end
end
c = Instance.new("HopperBin", game:GetService("Players").LocalPlayer.Backpack)
c.BinType = Enum.BinType.Hammer
c = Instance.new("HopperBin", game:GetService("Players").LocalPlayer.Backpack)
c.BinType = Enum.BinType.Clone
c = Instance.new("HopperBin", game:GetService("Players").LocalPlayer.Backpack)
c.BinType = Enum.BinType.Grab
end)

autocash.Name = "autocash"
autocash.Parent = RedXGUI
autocash.BackgroundColor3 = Color3.new(0.666667, 0, 0)
autocash.BackgroundTransparency = 0.5
autocash.BorderColor3 = Color3.new(0.258824, 0.0901961, 0.4)
autocash.BorderSizePixel = 3
autocash.Position = UDim2.new(0.355140209, 0, 0.423076928, 0)
autocash.Size = UDim2.new(0, 137, 0, 31)
autocash.Font = Enum.Font.Gotham
autocash.Text = "AUTOCASH"
autocash.TextColor3 = Color3.new(0, 0, 0)
autocash.TextScaled = true
autocash.TextSize = 14
autocash.TextWrapped = true

fling.Name = "fling"
fling.Parent = RedXGUI
fling.BackgroundColor3 = Color3.new(0.666667, 0, 0)
fling.BackgroundTransparency = 0.5
fling.BorderColor3 = Color3.new(0.258824, 0.0901961, 0.4)
fling.BorderSizePixel = 3
fling.Position = UDim2.new(0.693457961, 0, 0.423076928, 0)
fling.Size = UDim2.new(0, 137, 0, 31)
fling.Font = Enum.Font.Gotham
fling.Text = "FLINGGUI"
fling.TextColor3 = Color3.new(0, 0, 0)
fling.TextScaled = true
fling.TextSize = 14
fling.TextWrapped = true
fling.MouseButton1Click:Connect(function()
	-- Made By JackMcJagger15
local FlingKill = Instance.new("ScreenGui")
local Main = Instance.new("Frame")
local Label = Instance.new("Frame")
local Shadow = Instance.new("Frame")
local StartKill = Instance.new("TextButton")
local StopKill = Instance.new("TextButton")
local Instructions = Instance.new("TextLabel")
local CurrentPower = Instance.new("TextLabel")
local Recomendation = Instance.new("TextLabel")
local NameOfGui = Instance.new("TextLabel")
local Exit = Instance.new("TextButton")
local UPArrow = Instance.new("TextButton")
local DownArrow = Instance.new("TextButton")

-- Properties

FlingKill.Name = "Fling/Kill"
FlingKill.Parent = game.CoreGui

Main.Name = "Main"
Main.Parent = FlingKill
Main.BackgroundColor3 = Color3.new(0.92549, 0.941177, 0.945098)
Main.BorderSizePixel = 0
Main.Position = UDim2.new(0.702554762, 0, 0.446640313, 0)
Main.Size = UDim2.new(0, 217, 0, 233)
Main.Selectable = true
Main.Active = true
Main.Draggable = true

Label.Name = "Label"
Label.Parent = Main
Label.BackgroundColor3 = Color3.new(0.741176, 0.764706, 0.780392)
Label.BorderSizePixel = 0
Label.Size = UDim2.new(0, 217, 0, 27)

Shadow.Name = "Shadow"
Shadow.Parent = Main
Shadow.BackgroundColor3 = Color3.new(0.67451, 0.694118, 0.705882)
Shadow.BorderSizePixel = 0
Shadow.Position = UDim2.new(0, 0, 0.115879826, 0)
Shadow.Size = UDim2.new(0, 217, 0, 9)

StartKill.Name = "StartKill"
StartKill.Parent = Main
StartKill.BackgroundColor3 = Color3.new(0.741176, 0.764706, 0.780392)
StartKill.BorderSizePixel = 0
StartKill.Position = UDim2.new(0.195852548, 0, 0.227467805, 0)
StartKill.Size = UDim2.new(0, 126, 0, 23)
StartKill.Font = Enum.Font.Cartoon
StartKill.Text = "FE Kill/Fling"
StartKill.TextColor3 = Color3.new(0, 0, 0)
StartKill.TextSize = 14

StopKill.Name = "StopKill"
StopKill.Parent = Main
StopKill.BackgroundColor3 = Color3.new(0.741176, 0.764706, 0.780392)
StopKill.BorderSizePixel = 0
StopKill.Position = UDim2.new(0.207373276, 0, 0.38197428, 0)
StopKill.Size = UDim2.new(0, 124, 0, 23)
StopKill.Font = Enum.Font.Cartoon
StopKill.Text = "Stop FE Kill/Fling"
StopKill.TextColor3 = Color3.new(0, 0, 0)
StopKill.TextSize = 14

Instructions.Name = "Instructions"
Instructions.Parent = Main
Instructions.BackgroundColor3 = Color3.new(1, 1, 1)
Instructions.BackgroundTransparency = 1
Instructions.Position = UDim2.new(0.0391705073, 0, 0.549356222, 0)
Instructions.Size = UDim2.new(0, 200, 0, 32)
Instructions.Font = Enum.Font.Cartoon
Instructions.Text = "Just touch someone to watch the fly to their death!"
Instructions.TextColor3 = Color3.new(0, 0, 0)
Instructions.TextSize = 14
Instructions.TextWrapped = true

CurrentPower.Name = "CurrentPower"
CurrentPower.Parent = Main
CurrentPower.BackgroundColor3 = Color3.new(1, 1, 1)
CurrentPower.BackgroundTransparency = 1
CurrentPower.Position = UDim2.new(0.276497692, 0, 0.686695278, 0)
CurrentPower.Size = UDim2.new(0, 98, 0, 36)
CurrentPower.Font = Enum.Font.Cartoon
CurrentPower.Text = "Current Power = 5"
CurrentPower.TextColor3 = Color3.new(0, 0, 0)
CurrentPower.TextSize = 14

Recomendation.Name = "Recomendation"
Recomendation.Parent = Main
Recomendation.BackgroundColor3 = Color3.new(1, 1, 1)
Recomendation.BackgroundTransparency = 1
Recomendation.Position = UDim2.new(0.0414746553, 0, 0.884120166, 0)
Recomendation.Size = UDim2.new(0, 200, 0, 21)
Recomendation.Font = Enum.Font.Cartoon
Recomendation.Text = "Recommended Power is 5"
Recomendation.TextColor3 = Color3.new(0, 0, 0)
Recomendation.TextSize = 14

NameOfGui.Name = "NameOfGui"
NameOfGui.Parent = Main
NameOfGui.BackgroundColor3 = Color3.new(1, 1, 1)
NameOfGui.BackgroundTransparency = 1
NameOfGui.Position = UDim2.new(0.0806451589, 0, 0, 0)
NameOfGui.Size = UDim2.new(0, 154, 0, 27)
NameOfGui.Font = Enum.Font.Cartoon
NameOfGui.Text = "FE Kill/Fling By JackMcJagger15"
NameOfGui.TextColor3 = Color3.new(0, 0, 0)
NameOfGui.TextSize = 14

Exit.Name = "Exit"
Exit.Parent = Main
Exit.BackgroundColor3 = Color3.new(1, 1, 1)
Exit.BackgroundTransparency = 1
Exit.Position = UDim2.new(0.907834113, 0, 0, 0)
Exit.Size = UDim2.new(0, 20, 0, 27)
Exit.Font = Enum.Font.Cartoon
Exit.Text = "X"
Exit.TextColor3 = Color3.new(0, 0, 0)
Exit.TextSize = 14

UPArrow.Name = "UPArrow"
UPArrow.Parent = Main
UPArrow.BackgroundColor3 = Color3.new(1, 1, 1)
UPArrow.BackgroundTransparency = 1
UPArrow.Position = UDim2.new(0.0783410147, 0, 0.716738224, 0)
UPArrow.Size = UDim2.new(0, 26, 0, 23)
UPArrow.Font = Enum.Font.Cartoon
UPArrow.Text = "Up"
UPArrow.TextColor3 = Color3.new(0, 0, 0)
UPArrow.TextSize = 12
UPArrow.TextWrapped = true

DownArrow.Name = "DownArrow"
DownArrow.Parent = Main
DownArrow.BackgroundColor3 = Color3.new(1, 1, 1)
DownArrow.BackgroundTransparency = 1
DownArrow.Position = UDim2.new(0.792626739, 0, 0.714592278, 0)
DownArrow.Size = UDim2.new(0, 26, 0, 23)
DownArrow.Font = Enum.Font.Cartoon
DownArrow.Text = "Down"
DownArrow.TextColor3 = Color3.new(0, 0, 0)
DownArrow.TextSize = 12
DownArrow.TextWrapped = true

power = 500
active = false
local val = Instance.new("IntValue")
val.Name = "Number"
val.Parent = game.Players.LocalPlayer
val.Value = 5

Exit.MouseButton1Click:connect(function()
FlingKill.Enabled = false
end)

StartKill.MouseButton1Click:connect(function()
game:GetService('RunService').Stepped:connect(function()
if game.Players.LocalPlayer.Character.Humanoid.RigType == Enum.HumanoidRigType.R6 then
game.Players.LocalPlayer.Character.Head.CanCollide = false
game.Players.LocalPlayer.Character.Torso.CanCollide = false
game.Players.LocalPlayer.Character["Left Leg"].CanCollide = false
game.Players.LocalPlayer.Character["Right Leg"].CanCollide = false
else
if game.Players.LocalPlayer.Character.Humanoid.RigType == Enum.HumanoidRigType.R15 then
game.Players.LocalPlayer.Character.Head.CanCollide = false
game.Players.LocalPlayer.Character.UpperTorso.CanCollide = false
game.Players.LocalPlayer.Character.LowerTorso.CanCollide = false
game.Players.LocalPlayer.Character.HumanoidRootPart.CanCollide = false
end
end
end)
wait(.1)
local bambam = Instance.new("BodyThrust")
bambam.Parent = game.Players.LocalPlayer.Character.HumanoidRootPart
bambam.Force = Vector3.new(power,0,power)
bambam.Location = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
end)

StopKill.MouseButton1Click:connect(function()
active = false
game.Players.LocalPlayer.Character.HumanoidRootPart.BodyThrust:Remove()
end)

UPArrow.MouseButton1Click:connect(function()
power = power + 100
game.Players.LocalPlayer.Number.Value = game.Players.LocalPlayer.Number.Value + 1
CurrentPower.Text = "Current Power = " .. game.Players.LocalPlayer.Number.Value
end)

DownArrow.MouseButton1Click:connect(function()
power = power - 100
game.Players.LocalPlayer.Number.Value = game.Players.LocalPlayer.Number.Value - 1
CurrentPower.Text = "Current Power = " .. game.Players.LocalPlayer.Number.Value
end)
end)

fps.Name = "fps"
fps.Parent = RedXGUI
fps.BackgroundColor3 = Color3.new(0.666667, 0, 0)
fps.BackgroundTransparency = 0.5
fps.BorderColor3 = Color3.new(0.258824, 0.0901961, 0.4)
fps.BorderSizePixel = 3
fps.Position = UDim2.new(0.0186915882, 0, 0.636094689, 0)
fps.Size = UDim2.new(0, 137, 0, 31)
fps.Font = Enum.Font.SourceSans
fps.Text = "FPSBOOSTER"
fps.TextColor3 = Color3.new(0, 0, 0)
fps.TextScaled = true
fps.TextSize = 14
fps.TextWrapped = true
fps.MouseButton1Click:Connect(function()
	for _,v in pairs(workspace:GetDescendants()) do
if v.ClassName == "Part"
or v.ClassName == "SpawnLocation"
or v.ClassName == "WedgePart"
or v.ClassName == "Terrain"
or v.ClassName == "MeshPart" then
v.Material = "Plastic"
end
end

for _,v in pairs(workspace:GetDescendants()) do
if v.ClassName == "Decal"
or v.ClassName == "Texture" then
v:Destroy()
end
end
end)

speed_2.Name = "speed"
speed_2.Parent = RedXGUI
speed_2.BackgroundColor3 = Color3.new(0.666667, 0, 0)
speed_2.BackgroundTransparency = 0.5
speed_2.BorderColor3 = Color3.new(0.258824, 0.0901961, 0.4)
speed_2.BorderSizePixel = 3
speed_2.Position = UDim2.new(0.355140179, 0, 0.636094689, 0)
speed_2.Size = UDim2.new(0, 318, 0, 31)
speed_2.Font = Enum.Font.Gotham
speed_2.Text = "FLY[Q]"
speed_2.TextColor3 = Color3.new(0, 0, 0)
speed_2.TextScaled = true
speed_2.TextSize = 14
speed_2.TextWrapped = true
speed_2.MouseButton1Down:connect(function()
	local Enabled = false
	local Camera = game.Workspace.CurrentCamera
	local Player = game:GetService("Players").LocalPlayer
	local Input = game:GetService("UserInputService")
	local Forward = false
	local Back = false
	local Left = false
	local Right = false
	local Up = false
	local Down = false
	
	local function SetPlayer()
		for i,v in pairs(Player.Character:GetChildren()) do
			pcall(function()
				v.Anchored = not v.Anchored
			end)
		end
	end
	
	Input.InputBegan:Connect(function(Key,IsChat)
		if IsChat then return end
		if Key.KeyCode == Enum.KeyCode.Q then
			Enabled = not Enabled
			SetPlayer()
		end
		if Key.KeyCode == Enum.KeyCode.W then
			Forward = true
		end
		if Key.KeyCode == Enum.KeyCode.S then
			Back = true
		end
		if Key.KeyCode == Enum.KeyCode.A then
			Left = true
		end
		if Key.KeyCode == Enum.KeyCode.D then
			Right = true
		end
		if Key.KeyCode == Enum.KeyCode.Space then
			Up = true
		end
		if Key.KeyCode == Enum.KeyCode.LeftControl then
			Down = true
		end
	end)
	
	Input.InputEnded:Connect(function(Key,IsChat)
		if IsChat then return end
		if Key.KeyCode == Enum.KeyCode.W then
			Forward = false
		end
		if Key.KeyCode == Enum.KeyCode.S then
			Back = false
		end
		if Key.KeyCode == Enum.KeyCode.A then
			Left = false
		end
		if Key.KeyCode == Enum.KeyCode.D then
			Right = false
		end
		if Key.KeyCode == Enum.KeyCode.Space then
			Up = false
		end
		if Key.KeyCode == Enum.KeyCode.LeftControl then
			Down = false
		end
	end)
	
	while game:GetService("RunService").RenderStepped:Wait() do
		if Enabled then
			pcall(function()
			if Forward then
				Player.Character:TranslateBy(Camera.CFrame.lookVector*2)
			end
			if Back then
				Player.Character:TranslateBy(-Camera.CFrame.lookVector*2)
			end
				if Left then
					Player.Character:TranslateBy(-Camera.CFrame:vectorToWorldSpace(Vector3.new(1,0,0))*2)
				end
				if Right then
					Player.Character:TranslateBy(Camera.CFrame:vectorToWorldSpace(Vector3.new(1,0,0))*2)
				end
				if Up then
					Player.Character:TranslateBy(Camera.CFrame:vectorToWorldSpace(Vector3.new(0,1,0))*2)
				end
				if Down then
					Player.Character:TranslateBy(-Camera.CFrame:vectorToWorldSpace(Vector3.new(0,1,0))*2)
				end
			end)
		end
	end
end)

TextLabel_3.Parent = RedXGUI
TextLabel_3.BackgroundColor3 = Color3.new(0.317647, 0.156863, 0.458824)
TextLabel_3.BorderSizePixel = 3
TextLabel_3.Position = UDim2.new(0.0672897175, 0, 0.547337294, 0)
TextLabel_3.Rotation = 90
TextLabel_3.Size = UDim2.new(0, 261, 0, 6)
TextLabel_3.Font = Enum.Font.SourceSans
TextLabel_3.Text = ""
TextLabel_3.TextColor3 = Color3.new(0, 0, 0)
TextLabel_3.TextSize = 14

close.Name = "close"
close.Parent = RedXGUI
close.BackgroundColor3 = Color3.new(0.34902, 0, 0.52549)
close.BorderSizePixel = 3
close.Position = UDim2.new(0.893457949, 0, 0.0384615399, 0)
close.Size = UDim2.new(0, 30, 0, 24)
close.Font = Enum.Font.SourceSans
close.Text = "X"
close.TextColor3 = Color3.new(0, 0, 0)
close.TextScaled = true
close.TextSize = 14
close.TextWrapped = true
close.MouseButton1Down:connect(function()
RedXGUI.Visible = false
open.Visible = true
end)

TextLabel_4.Parent = RedXGUI
TextLabel_4.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel_4.BackgroundTransparency = 1
TextLabel_4.Position = UDim2.new(0.428359777, 0, 0.794960082, 0)
TextLabel_4.Size = UDim2.new(0, 245, 0, 55)
TextLabel_4.Font = Enum.Font.Gotham
TextLabel_4.Text = "SUBSCRIBE TO TURNINGLOBERB ON YOUTUBE"
TextLabel_4.TextColor3 = Color3.new(0, 0, 0)
TextLabel_4.TextScaled = true
TextLabel_4.TextSize = 14
TextLabel_4.TextWrapped = true

open.Name = "open"
open.Parent = ScreenGui
open.BackgroundColor3 = Color3.new(0.666667, 1, 1)
open.BorderSizePixel = 3
open.Position = UDim2.new(0.00538047682, 0, 0.412598431, 0)
open.Size = UDim2.new(0, 75, 0, 31)
open.Font = Enum.Font.Gotham
open.Text = "OPEN"
open.TextColor3 = Color3.new(0, 0, 0)
open.TextScaled = true
open.TextSize = 14
open.TextWrapped = true
open.MouseButton1Down:connect(function()
RedXGUI.Visible = true
open.Visible = false
end)
