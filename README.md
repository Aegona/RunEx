

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local Frame_2 = Instance.new("Frame")
local UICorner_2 = Instance.new("UICorner")
local UIAspectRatioConstraint = Instance.new("UIAspectRatioConstraint")
local menu1 = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local UIAspectRatioConstraint_2 = Instance.new("UIAspectRatioConstraint")
local UITextSizeConstraint = Instance.new("UITextSizeConstraint")
local BG1 = Instance.new("TextBox")
local UICorner_4 = Instance.new("UICorner")
local Attack = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local UIAspectRatioConstraint_3 = Instance.new("UIAspectRatioConstraint")
local UITextSizeConstraint_2 = Instance.new("UITextSizeConstraint")
local LoadClib = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local UIAspectRatioConstraint_4 = Instance.new("UIAspectRatioConstraint")
local UITextSizeConstraint_3 = Instance.new("UITextSizeConstraint")
local Run = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local UIAspectRatioConstraint_5 = Instance.new("UIAspectRatioConstraint")
local UITextSizeConstraint_4 = Instance.new("UITextSizeConstraint")
local AttacTex = Instance.new("TextLabel")
local UIAspectRatioConstraint_6 = Instance.new("UIAspectRatioConstraint")
local UITextSizeConstraint_5 = Instance.new("UITextSizeConstraint")
local UIAspectRatioConstraint_7 = Instance.new("UIAspectRatioConstraint")
local UITextSizeConstraint_6 = Instance.new("UITextSizeConstraint")
local UIAspectRatioConstraint_8 = Instance.new("UIAspectRatioConstraint")
local menu2 = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local UIAspectRatioConstraint_9 = Instance.new("UIAspectRatioConstraint")
local UITextSizeConstraint_7 = Instance.new("UITextSizeConstraint")
local BG2 = Instance.new("Frame")
local UICorner_9 = Instance.new("UICorner")
local UIAspectRatioConstraint_10 = Instance.new("UIAspectRatioConstraint")
local TextLabel = Instance.new("TextLabel")
local UIAspectRatioConstraint_11 = Instance.new("UIAspectRatioConstraint")
local UITextSizeConstraint_8 = Instance.new("UITextSizeConstraint")
local TextLabel_2 = Instance.new("TextLabel")
local UIAspectRatioConstraint_12 = Instance.new("UIAspectRatioConstraint")
local UITextSizeConstraint_9 = Instance.new("UITextSizeConstraint")
local TextButton = Instance.new("TextButton")
local UICorner_10 = Instance.new("UICorner")
local UIAspectRatioConstraint_13 = Instance.new("UIAspectRatioConstraint")
local UITextSizeConstraint_10 = Instance.new("UITextSizeConstraint")

--Properties:

ScreenGui.Parent = game.CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(77, 77, 77)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.238444611, 0, 0.273170739, 0)
Frame.Size = UDim2.new(0.523110807, 0, 0.453658551, 0)
Frame.Visible = false

UICorner.Parent = Frame

Frame_2.Parent = Frame
Frame_2.BackgroundColor3 = Color3.fromRGB(85, 85, 85)
Frame_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_2.BorderSizePixel = 0
Frame_2.Position = UDim2.new(0.0725960508, 0, 0.0339234062, 0)
Frame_2.Size = UDim2.new(0.92706871, 0, 0.857526898, 0)

UICorner_2.Parent = Frame_2

UIAspectRatioConstraint.Parent = Frame_2
UIAspectRatioConstraint.AspectRatio = 2.072

menu1.Name = "menu1"
menu1.Parent = Frame
menu1.BackgroundColor3 = Color3.fromRGB(97, 97, 97)
menu1.BorderColor3 = Color3.fromRGB(0, 0, 0)
menu1.BorderSizePixel = 0
menu1.Position = UDim2.new(0, 0, 0.155913979, 0)
menu1.Rotation = 11.000
menu1.Size = UDim2.new(0.0715287551, 0, 0.134408608, 0)
menu1.Font = Enum.Font.SourceSansBold
menu1.Text = "Menu1"
menu1.TextColor3 = Color3.fromRGB(255, 255, 255)
menu1.TextScaled = true
menu1.TextSize = 14.000
menu1.TextWrapped = true

UICorner_3.CornerRadius = UDim.new(0, 80)
UICorner_3.Parent = menu1

UIAspectRatioConstraint_2.Parent = menu1
UIAspectRatioConstraint_2.AspectRatio = 1.020

UITextSizeConstraint.Parent = menu1
UITextSizeConstraint.MaxTextSize = 14

BG1.Name = "BG1"
BG1.Parent = Frame
BG1.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
BG1.BorderColor3 = Color3.fromRGB(0, 0, 0)
BG1.BorderSizePixel = 0
BG1.Position = UDim2.new(0.115007013, 0, 0.0698924735, 0)
BG1.Size = UDim2.new(0.841514647, 0, 0.782258093, 0)
BG1.Visible = false
BG1.Font = Enum.Font.SourceSans
BG1.PlaceholderText = ">>>>>>>SCRIPT>>>>>>>"
BG1.Text = ""
BG1.TextColor3 = Color3.fromRGB(255, 255, 255)
BG1.TextScaled = true
BG1.TextSize = 14.000
BG1.TextWrapped = true
BG1.TextXAlignment = Enum.TextXAlignment.Left
BG1.TextYAlignment = Enum.TextYAlignment.Top

UICorner_4.Parent = BG1

Attack.Name = "Attack"
Attack.Parent = BG1
Attack.BackgroundColor3 = Color3.fromRGB(61, 61, 61)
Attack.BorderColor3 = Color3.fromRGB(0, 0, 0)
Attack.BorderSizePixel = 0
Attack.Position = UDim2.new(0.0216666665, 0, 1, 0)
Attack.Size = UDim2.new(0.291666687, 0, 0.171821311, 0)
Attack.Font = Enum.Font.SourceSans
Attack.Text = "Attack"
Attack.TextColor3 = Color3.fromRGB(255, 255, 255)
Attack.TextScaled = true
Attack.TextSize = 14.000
Attack.TextWrapped = true

UICorner_5.Parent = Attack

UIAspectRatioConstraint_3.Parent = Attack
UIAspectRatioConstraint_3.AspectRatio = 3.500

UITextSizeConstraint_2.Parent = Attack
UITextSizeConstraint_2.MaxTextSize = 50

LoadClib.Name = "LoadClib"
LoadClib.Parent = BG1
LoadClib.BackgroundColor3 = Color3.fromRGB(61, 61, 61)
LoadClib.BorderColor3 = Color3.fromRGB(0, 0, 0)
LoadClib.BorderSizePixel = 0
LoadClib.Position = UDim2.new(0.353333324, 0, 1, 0)
LoadClib.Size = UDim2.new(0.291666687, 0, 0.171821311, 0)
LoadClib.Font = Enum.Font.SourceSans
LoadClib.Text = "LoadClib"
LoadClib.TextColor3 = Color3.fromRGB(255, 255, 255)
LoadClib.TextScaled = true
LoadClib.TextSize = 14.000
LoadClib.TextWrapped = true

UICorner_6.Parent = LoadClib

UIAspectRatioConstraint_4.Parent = LoadClib
UIAspectRatioConstraint_4.AspectRatio = 3.500

UITextSizeConstraint_3.Parent = LoadClib
UITextSizeConstraint_3.MaxTextSize = 50

Run.Name = "Run"
Run.Parent = BG1
Run.BackgroundColor3 = Color3.fromRGB(61, 61, 61)
Run.BorderColor3 = Color3.fromRGB(0, 0, 0)
Run.BorderSizePixel = 0
Run.Position = UDim2.new(0.680000007, 0, 1, 0)
Run.Size = UDim2.new(0.291666687, 0, 0.171821311, 0)
Run.Font = Enum.Font.SourceSans
Run.Text = "Run"
Run.TextColor3 = Color3.fromRGB(255, 255, 255)
Run.TextScaled = true
Run.TextSize = 14.000
Run.TextWrapped = true

UICorner_7.Parent = Run

UIAspectRatioConstraint_5.Parent = Run
UIAspectRatioConstraint_5.AspectRatio = 3.500

UITextSizeConstraint_4.Parent = Run
UITextSizeConstraint_4.MaxTextSize = 50

AttacTex.Name = "AttacTex"
AttacTex.Parent = BG1
AttacTex.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
AttacTex.BackgroundTransparency = 1.000
AttacTex.BorderColor3 = Color3.fromRGB(0, 0, 0)
AttacTex.BorderSizePixel = 0
AttacTex.Position = UDim2.new(-0.0533333905, 0, -0.522336781, 0)
AttacTex.Size = UDim2.new(1.10333347, 0, 0.257731944, 0)
AttacTex.Visible = false
AttacTex.Font = Enum.Font.SourceSansBold
AttacTex.Text = "Attack Suscess"
AttacTex.TextColor3 = Color3.fromRGB(64, 0, 255)
AttacTex.TextScaled = true
AttacTex.TextSize = 14.000
AttacTex.TextWrapped = true

UIAspectRatioConstraint_6.Parent = AttacTex
UIAspectRatioConstraint_6.AspectRatio = 9.080

UITextSizeConstraint_5.Parent = AttacTex
UITextSizeConstraint_5.MaxTextSize = 50

UIAspectRatioConstraint_7.Parent = BG1
UIAspectRatioConstraint_7.AspectRatio = 2.062

UITextSizeConstraint_6.Parent = BG1
UITextSizeConstraint_6.MaxTextSize = 14

UIAspectRatioConstraint_8.Parent = Frame
UIAspectRatioConstraint_8.AspectRatio = 1.917

menu2.Name = "menu2"
menu2.Parent = Frame
menu2.BackgroundColor3 = Color3.fromRGB(97, 97, 97)
menu2.BorderColor3 = Color3.fromRGB(0, 0, 0)
menu2.BorderSizePixel = 0
menu2.Position = UDim2.new(0, 0, 0.319892466, 0)
menu2.Rotation = 11.000
menu2.Size = UDim2.new(0.0715287551, 0, 0.134408608, 0)
menu2.Font = Enum.Font.SourceSansBold
menu2.Text = "Menu2"
menu2.TextColor3 = Color3.fromRGB(255, 255, 255)
menu2.TextScaled = true
menu2.TextSize = 14.000
menu2.TextWrapped = true

UICorner_8.CornerRadius = UDim.new(0, 80)
UICorner_8.Parent = menu2

UIAspectRatioConstraint_9.Parent = menu2
UIAspectRatioConstraint_9.AspectRatio = 1.020

UITextSizeConstraint_7.Parent = menu2
UITextSizeConstraint_7.MaxTextSize = 14

BG2.Name = "BG2"
BG2.Parent = Frame
BG2.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
BG2.BorderColor3 = Color3.fromRGB(0, 0, 0)
BG2.BorderSizePixel = 0
BG2.Position = UDim2.new(0.115000002, 0, 0.0700000003, 0)
BG2.Size = UDim2.new(0.842000008, 0, 0.782000005, 0)
BG2.Visible = false

UICorner_9.Parent = BG2

UIAspectRatioConstraint_10.Parent = BG2
UIAspectRatioConstraint_10.AspectRatio = 2.064

TextLabel.Parent = BG2
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.0116472542, 0, 0.0341790244, 0)
TextLabel.Size = UDim2.new(1.00108933, 0, 0.17187801, 0)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Auto Run Script = False"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

UIAspectRatioConstraint_11.Parent = TextLabel
UIAspectRatioConstraint_11.AspectRatio = 12.020

UITextSizeConstraint_8.Parent = TextLabel
UITextSizeConstraint_8.MaxTextSize = 50

TextLabel_2.Parent = BG2
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Position = UDim2.new(0.0116472542, 0, 0.205162913, 0)
TextLabel_2.Size = UDim2.new(1.00108933, 0, 0.17187801, 0)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "Auto Delete Workspack Flie = true"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 14.000
TextLabel_2.TextWrapped = true

UIAspectRatioConstraint_12.Parent = TextLabel_2
UIAspectRatioConstraint_12.AspectRatio = 12.020

UITextSizeConstraint_9.Parent = TextLabel_2
UITextSizeConstraint_9.MaxTextSize = 50

TextButton.Parent = ScreenGui
TextButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0.0227439478, 0, 0.048780486, 0)
TextButton.Size = UDim2.new(0.0359501094, 0, 0.0609756112, 0)
TextButton.Font = Enum.Font.SourceSans
TextButton.Text = ""
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextScaled = true
TextButton.TextSize = 14.000
TextButton.TextWrapped = true

UICorner_10.CornerRadius = UDim.new(0, 80)
UICorner_10.Parent = TextButton

UIAspectRatioConstraint_13.Parent = TextButton
UIAspectRatioConstraint_13.AspectRatio = 0.980

UITextSizeConstraint_10.Parent = TextButton
UITextSizeConstraint_10.MaxTextSize = 14

-- Scripts:

local function MGAWWHK_fake_script() -- menu1.LocalScript 
	local script = Instance.new('LocalScript', menu1)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.BG1.Visible = true
		script.Parent.Parent.BG2.Visible = false
	end)
end
coroutine.wrap(MGAWWHK_fake_script)()
local function SSAE_fake_script() -- Attack.LocalScript 
	local script = Instance.new('LocalScript', Attack)

	script.Parent.MouseButton1Click:Connect(function()
		local attacktex = script.Parent.Parent.AttacTex
		attacktex.Visible = true
		wait(3)
		attacktex.Visible = false
	end)
end
coroutine.wrap(SSAE_fake_script)()
local function CQNN_fake_script() -- LoadClib.LocalScript 
	local script = Instance.new('LocalScript', LoadClib)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent.BG1.Text = "loadstring(game:HttpGet(('https://raw.githubusercontent.com/Aegona/Scriptkey1/main/README.md))()"
	end)
end
coroutine.wrap(CQNN_fake_script)()
local function VQJJ_fake_script() -- Run.LocalScript 
	local script = Instance.new('LocalScript', Run)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet(("https://raw.githubusercontent.com/Aegona/Scriptkey1/main/README.md"), true))()
	end)
end
coroutine.wrap(VQJJ_fake_script)()
local function RUCL_fake_script() -- menu2.LocalScript 
	local script = Instance.new('LocalScript', menu2)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.BG1.Visible = false
		script.Parent.Parent.BG2.Visible = true
	end)
end
coroutine.wrap(RUCL_fake_script)()
local function FLUGP_fake_script() -- Frame.LocalScript 
	local script = Instance.new('LocalScript', Frame)

	local UIS = game:GetService('UserInputService')
	
	local frame = script.Parent
	
	
	
	local dragToggle = nil
	
	local dragSpeed = 0.25
	
	local dragStart = nil
	
	local startPos = nil
	
	
	
	local function updateInput(input)
	
		local delta = input.Position - dragStart
	
		local position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X,
	
			startPos.Y.Scale, startPos.Y.Offset + delta.Y)
	
		game:GetService('TweenService'):Create(frame, TweenInfo.new(dragSpeed), {Position = position}):Play()
	
	end
	
	
	
	frame.InputBegan:Connect(function(input)
	
		if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) then 
	
			dragToggle = true
	
			dragStart = input.Position
	
			startPos = frame.Position
	
			input.Changed:Connect(function()
	
				if input.UserInputState == Enum.UserInputState.End then
	
					dragToggle = false
	
				end
	
			end)
	
		end
	
	end)
	
	
	
	UIS.InputChanged:Connect(function(input)
	
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
	
			if dragToggle then
	
				updateInput(input)
	
			end
	
		end
	
	end)
end
coroutine.wrap(FLUGP_fake_script)()
local function QRILI_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	script.Parent.MouseButton1Click:Connect(function()
		if script.Parent.Parent.Frame.Visible == true then
			script.Parent.Parent.Frame.Visible = false
		elseif script.Parent.Parent.Frame.Visible == false then
			script.Parent.Parent.Frame.Visible = true
		end
	end)
end
coroutine.wrap(QRILI_fake_script)()
