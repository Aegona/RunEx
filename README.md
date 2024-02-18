-- Gui to Lua
-- Version: 3.2

-- Instances:

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
local TextButton = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local UIAspectRatioConstraint_9 = Instance.new("UIAspectRatioConstraint")
local UITextSizeConstraint_7 = Instance.new("UITextSizeConstraint")

--Properties:

ScreenGui.Parent = game.CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(77, 77, 77)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.238444611, 0, 0.273170739, 0)
Frame.Size = UDim2.new(0.523110807, 0, 0.453658551, 0)

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
AttacTex.Position = UDim2.new(0.0783333331, 0, -0.487972498, 0)
AttacTex.Size = UDim2.new(0.75666672, 0, 0.171821311, 0)
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

UICorner_8.CornerRadius = UDim.new(0, 80)
UICorner_8.Parent = TextButton

UIAspectRatioConstraint_9.Parent = TextButton
UIAspectRatioConstraint_9.AspectRatio = 0.980

UITextSizeConstraint_7.Parent = TextButton
UITextSizeConstraint_7.MaxTextSize = 14

-- Scripts:

local function CGGON_fake_script() -- Attack.LocalScript 
	local script = Instance.new('LocalScript', Attack)

	script.Parent.MouseButton1Click:Connect(function()
		local attacktex = script.Parent.Parent.AttacTex
		attacktex.Visible = true
		wait(3)
		attacktex.Visible = false
	end)
end
coroutine.wrap(CGGON_fake_script)()
local function VESI_fake_script() -- LoadClib.LocalScript 
	local script = Instance.new('LocalScript', LoadClib)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent.BG1.Text = "loadstring(game:HttpGet(('https://raw.githubusercontent.com/Aegona/Scriptkey1/main/README.md))()"
	end)
end
coroutine.wrap(VESI_fake_script)()
local function JRZPT_fake_script() -- Run.LocalScript 
	local script = Instance.new('LocalScript', Run)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet(("https://raw.githubusercontent.com/Aegona/Scriptkey1/main/README.md"), true))()
	end)
end
coroutine.wrap(JRZPT_fake_script)()
local function NKYEQET_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	script.Parent.MouseButton1Click:Connect(function()
		if script.Parent.Parent.Frame.Visible == true then
			script.Parent.Parent.Frame.Visible = false
		elseif script.Parent.Parent.Frame.Visible == false then
			script.Parent.Parent.Frame.Visible = true
		end
	end)
end
coroutine.wrap(NKYEQET_fake_script)()
