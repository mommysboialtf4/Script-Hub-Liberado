-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local flyLabel = Instance.new("TextLabel")
local Frame = Instance.new("Frame")
local Cebola = Instance.new("TextButton")
local HotDog = Instance.new("TextButton")
local InvisButton = Instance.new("TextButton")
local Pizza = Instance.new("TextButton")
local Noclip = Instance.new("TextButton")
local TextLabel = Instance.new("TextLabel")
local Imortalidade = Instance.new("TextButton")
local RGBsessao = Instance.new("TextButton")
local Sanduiche = Instance.new("TextButton")
local escudoButton = Instance.new("TextButton")
local SpeedButton = Instance.new("TextButton")
local SpeedButton2 = Instance.new("TextButton")
local superForcaButton = Instance.new("TextButton")
local flyButton = Instance.new("TextButton")
local hulkButton = Instance.new("TextButton")
local smallButton = Instance.new("TextButton")
local miniButton = Instance.new("TextButton")
local lagButton = Instance.new("TextButton")
local TextLabel_2 = Instance.new("TextLabel")
local TextLabel_3 = Instance.new("TextLabel")
local TextButton1 = Instance.new("TextButton")
local RGBlgl = Instance.new("TextLabel")
local rgb = Instance.new("Frame")
local RGBButton = Instance.new("TextButton")
local MoveEntitiesButton = Instance.new("TextButton")
local button = Instance.new("TextButton")
local _1Button = Instance.new("TextButton")
local MessageButton = Instance.new("TextButton")
local TextLabel_4 = Instance.new("TextLabel")
local MessageButton_2 = Instance.new("TextButton")
local TextLabel_5 = Instance.new("TextLabel")
local Button7 = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

flyLabel.Name = "flyLabel"
flyLabel.Parent = ScreenGui
flyLabel.BackgroundColor3 = Color3.fromRGB(12, 36, 57)
flyLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
flyLabel.BorderSizePixel = 3
flyLabel.Position = UDim2.new(0.0859259292, 0, 0.17336683, 0)
flyLabel.Size = UDim2.new(0, 1077, 0, 29)
flyLabel.Font = Enum.Font.SourceSans
flyLabel.Text = "Welcome to script hub! 🐢"
flyLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
flyLabel.TextSize = 23.000
flyLabel.TextStrokeColor3 = Color3.fromRGB(249, 249, 249)
flyLabel.TextWrapped = true
flyLabel.TextXAlignment = Enum.TextXAlignment.Left

Frame.Parent = flyLabel
Frame.BackgroundColor3 = Color3.fromRGB(4, 22, 30)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 3
Frame.Position = UDim2.new(-0.000602530898, 0, 0.998115301, 0)
Frame.Size = UDim2.new(0, 1077, 0, 589)

Cebola.Name = "Cebola"
Cebola.Parent = flyLabel
Cebola.BackgroundColor3 = Color3.fromRGB(0, 145, 0)
Cebola.BorderColor3 = Color3.fromRGB(0, 0, 0)
Cebola.BorderSizePixel = 0
Cebola.Position = UDim2.new(0.489322186, 0, 13.166667, 0)
Cebola.Size = UDim2.new(0, 148, 0, 58)
Cebola.Font = Enum.Font.SourceSans
Cebola.Text = "MilkShake🥤"
Cebola.TextColor3 = Color3.fromRGB(255, 255, 255)
Cebola.TextSize = 32.000

HotDog.Name = "HotDog"
HotDog.Parent = flyLabel
HotDog.BackgroundColor3 = Color3.fromRGB(0, 145, 0)
HotDog.BorderColor3 = Color3.fromRGB(0, 0, 0)
HotDog.BorderSizePixel = 0
HotDog.Position = UDim2.new(0.174558967, 0, 13.166667, 0)
HotDog.Size = UDim2.new(0, 148, 0, 58)
HotDog.Font = Enum.Font.SourceSans
HotDog.Text = "HotDog🌭"
HotDog.TextColor3 = Color3.fromRGB(255, 255, 255)
HotDog.TextSize = 32.000

InvisButton.Name = "InvisButton"
InvisButton.Parent = flyLabel
InvisButton.BackgroundColor3 = Color3.fromRGB(4, 37, 145)
InvisButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
InvisButton.BorderSizePixel = 0
InvisButton.Position = UDim2.new(0.646239579, 0, 4.16091967, 0)
InvisButton.Size = UDim2.new(0, 148, 0, 58)
InvisButton.Font = Enum.Font.SourceSans
InvisButton.Text = "Invisíbilidade"
InvisButton.TextColor3 = Color3.fromRGB(255, 255, 255)
InvisButton.TextSize = 32.000

Pizza.Name = "Pizza"
Pizza.Parent = flyLabel
Pizza.BackgroundColor3 = Color3.fromRGB(0, 145, 0)
Pizza.BorderColor3 = Color3.fromRGB(0, 0, 0)
Pizza.BorderSizePixel = 0
Pizza.Position = UDim2.new(0.331476331, 0, 13.166667, 0)
Pizza.Size = UDim2.new(0, 148, 0, 58)
Pizza.Font = Enum.Font.SourceSans
Pizza.Text = "Pizza🍕"
Pizza.TextColor3 = Color3.fromRGB(255, 255, 255)
Pizza.TextSize = 32.000

Noclip.Name = "Noclip"
Noclip.Parent = flyLabel
Noclip.BackgroundColor3 = Color3.fromRGB(4, 37, 145)
Noclip.BorderColor3 = Color3.fromRGB(0, 0, 0)
Noclip.BorderSizePixel = 0
Noclip.Position = UDim2.new(0.490250707, 0, 1.71264386, 0)
Noclip.Size = UDim2.new(0, 148, 0, 58)
Noclip.Font = Enum.Font.SourceSans
Noclip.Text = "Ativar Noclip"
Noclip.TextColor3 = Color3.fromRGB(255, 255, 255)
Noclip.TextSize = 32.000

TextLabel.Parent = Noclip
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(-0.121621624, 0, 1, 0)
TextLabel.Size = UDim2.new(0, 187, 0, 32)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Não pule, senão não funcionará"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 23.000

Imortalidade.Name = "Imortalidade"
Imortalidade.Parent = flyLabel
Imortalidade.BackgroundColor3 = Color3.fromRGB(4, 37, 145)
Imortalidade.BorderColor3 = Color3.fromRGB(0, 0, 0)
Imortalidade.BorderSizePixel = 0
Imortalidade.Position = UDim2.new(0.646239579, 0, 1.71264386, 0)
Imortalidade.Size = UDim2.new(0, 148, 0, 58)
Imortalidade.Font = Enum.Font.SourceSans
Imortalidade.Text = "Imortalidade"
Imortalidade.TextColor3 = Color3.fromRGB(255, 255, 255)
Imortalidade.TextSize = 32.000

RGBsessao.Name = "RGBsessao"
RGBsessao.Parent = flyLabel
RGBsessao.BackgroundColor3 = Color3.fromRGB(4, 37, 145)
RGBsessao.BorderColor3 = Color3.fromRGB(0, 0, 0)
RGBsessao.BorderSizePixel = 0
RGBsessao.Position = UDim2.new(0.705667555, 0, 13.1495533, 0)
RGBsessao.Size = UDim2.new(0, 148, 0, 58)
RGBsessao.Font = Enum.Font.SourceSans
RGBsessao.Text = "sessão poder"
RGBsessao.TextColor3 = Color3.fromRGB(255, 255, 255)
RGBsessao.TextSize = 32.000

Sanduiche.Name = "Sanduiche"
Sanduiche.Parent = flyLabel
Sanduiche.BackgroundColor3 = Color3.fromRGB(0, 145, 0)
Sanduiche.BorderColor3 = Color3.fromRGB(0, 0, 0)
Sanduiche.BorderSizePixel = 0
Sanduiche.Position = UDim2.new(0.0167130921, 0, 13.166667, 0)
Sanduiche.Size = UDim2.new(0, 148, 0, 58)
Sanduiche.Font = Enum.Font.SourceSans
Sanduiche.Text = "Sanduíche🥪"
Sanduiche.TextColor3 = Color3.fromRGB(255, 255, 255)
Sanduiche.TextSize = 32.000

escudoButton.Name = "escudoButton"
escudoButton.Parent = flyLabel
escudoButton.BackgroundColor3 = Color3.fromRGB(4, 37, 145)
escudoButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
escudoButton.BorderSizePixel = 0
escudoButton.Position = UDim2.new(0.805013955, 0, 4.16091967, 0)
escudoButton.Size = UDim2.new(0, 148, 0, 58)
escudoButton.Font = Enum.Font.SourceSans
escudoButton.Text = "Escudo desat."
escudoButton.TextColor3 = Color3.fromRGB(255, 255, 255)
escudoButton.TextSize = 32.000

SpeedButton.Name = "SpeedButton"
SpeedButton.Parent = flyLabel
SpeedButton.BackgroundColor3 = Color3.fromRGB(4, 37, 145)
SpeedButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
SpeedButton.BorderSizePixel = 0
SpeedButton.Position = UDim2.new(0.805013955, 0, 1.71264386, 0)
SpeedButton.Size = UDim2.new(0, 148, 0, 58)
SpeedButton.Font = Enum.Font.SourceSans
SpeedButton.Text = "Velocidade+5"
SpeedButton.TextColor3 = Color3.fromRGB(255, 255, 255)
SpeedButton.TextSize = 32.000

SpeedButton2.Name = "SpeedButton2"
SpeedButton2.Parent = flyLabel
SpeedButton2.BackgroundColor3 = Color3.fromRGB(4, 37, 145)
SpeedButton2.BorderColor3 = Color3.fromRGB(0, 0, 0)
SpeedButton2.BorderSizePixel = 0
SpeedButton2.Position = UDim2.new(0.0167130921, 0, 4.16091967, 0)
SpeedButton2.Size = UDim2.new(0, 148, 0, 58)
SpeedButton2.Font = Enum.Font.SourceSans
SpeedButton2.Text = "Velocidade-5"
SpeedButton2.TextColor3 = Color3.fromRGB(255, 255, 255)
SpeedButton2.TextSize = 32.000

superForcaButton.Name = "superForcaButton"
superForcaButton.Parent = flyLabel
superForcaButton.BackgroundColor3 = Color3.fromRGB(4, 37, 145)
superForcaButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
superForcaButton.BorderSizePixel = 0
superForcaButton.Position = UDim2.new(0.0167130921, 0, 6.85057545, 0)
superForcaButton.Size = UDim2.new(0, 148, 0, 58)
superForcaButton.Font = Enum.Font.SourceSans
superForcaButton.Text = "Super Força"
superForcaButton.TextColor3 = Color3.fromRGB(255, 255, 255)
superForcaButton.TextSize = 32.000

flyButton.Name = "flyButton"
flyButton.Parent = flyLabel
flyButton.BackgroundColor3 = Color3.fromRGB(4, 37, 145)
flyButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
flyButton.BorderSizePixel = 0
flyButton.Position = UDim2.new(0.331476331, 0, 1.74712658, 0)
flyButton.Size = UDim2.new(0, 148, 0, 58)
flyButton.Font = Enum.Font.SourceSans
flyButton.Text = "Ativar Voo"
flyButton.TextColor3 = Color3.fromRGB(255, 255, 255)
flyButton.TextSize = 32.000

hulkButton.Name = "hulkButton"
hulkButton.Parent = flyLabel
hulkButton.BackgroundColor3 = Color3.fromRGB(4, 37, 145)
hulkButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
hulkButton.BorderSizePixel = 0
hulkButton.Position = UDim2.new(0.331476331, 0, 4.16091967, 0)
hulkButton.Size = UDim2.new(0, 148, 0, 58)
hulkButton.Font = Enum.Font.SourceSans
hulkButton.Text = "Giant Skin"
hulkButton.TextColor3 = Color3.fromRGB(255, 255, 255)
hulkButton.TextSize = 32.000

smallButton.Name = "smallButton"
smallButton.Parent = flyLabel
smallButton.BackgroundColor3 = Color3.fromRGB(4, 37, 145)
smallButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
smallButton.BorderSizePixel = 0
smallButton.Position = UDim2.new(0.490250707, 0, 4.16091967, 0)
smallButton.Size = UDim2.new(0, 148, 0, 58)
smallButton.Font = Enum.Font.SourceSans
smallButton.Text = "Small Skin"
smallButton.TextColor3 = Color3.fromRGB(255, 255, 255)
smallButton.TextSize = 32.000

miniButton.Name = "miniButton"
miniButton.Parent = flyLabel
miniButton.BackgroundColor3 = Color3.fromRGB(4, 37, 145)
miniButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
miniButton.BorderSizePixel = 0
miniButton.Position = UDim2.new(0.174558967, 0, 4.16091967, 0)
miniButton.Size = UDim2.new(0, 148, 0, 58)
miniButton.Font = Enum.Font.SourceSans
miniButton.Text = "Avatar Bug"
miniButton.TextColor3 = Color3.fromRGB(255, 255, 255)
miniButton.TextSize = 32.000

lagButton.Name = "lagButton"
lagButton.Parent = flyLabel
lagButton.BackgroundColor3 = Color3.fromRGB(4, 37, 145)
lagButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
lagButton.BorderSizePixel = 0
lagButton.Position = UDim2.new(0.174558967, 0, 6.85057545, 0)
lagButton.Size = UDim2.new(0, 148, 0, 58)
lagButton.Font = Enum.Font.SourceSans
lagButton.Text = "Fake Lag"
lagButton.TextColor3 = Color3.fromRGB(255, 255, 255)
lagButton.TextSize = 32.000

TextLabel_2.Parent = flyLabel
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Position = UDim2.new(0.00928505138, 0, 1.48994291, 0)
TextLabel_2.Selectable = true
TextLabel_2.Size = UDim2.new(0, 789, 0, 41)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "Aqui estão alguns scripts para começar a brincar."
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextSize = 17.000
TextLabel_2.TextXAlignment = Enum.TextXAlignment.Left

TextLabel_3.Parent = flyLabel
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.BorderSizePixel = 0
TextLabel_3.Position = UDim2.new(0.00928505138, 0, 9.75, 0)
TextLabel_3.Size = UDim2.new(0, 200, 0, 50)
TextLabel_3.Font = Enum.Font.SourceSans
TextLabel_3.Text = "Itens Especiais"
TextLabel_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.TextSize = 33.000
TextLabel_3.TextXAlignment = Enum.TextXAlignment.Left

TextButton1.Name = "TextButton1"
TextButton1.Parent = flyLabel
TextButton1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton1.BackgroundTransparency = 1.010
TextButton1.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton1.BorderSizePixel = 0
TextButton1.Position = UDim2.new(0.94150418, 0, -0.517241359, 0)
TextButton1.Size = UDim2.new(0, 62, 0, 43)
TextButton1.Font = Enum.Font.SourceSans
TextButton1.Text = "-"
TextButton1.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton1.TextSize = 84.000

RGBlgl.Name = "RGBlgl"
RGBlgl.Parent = ScreenGui
RGBlgl.BackgroundColor3 = Color3.fromRGB(106, 20, 255)
RGBlgl.BorderColor3 = Color3.fromRGB(0, 0, 0)
RGBlgl.BorderSizePixel = 3
RGBlgl.Position = UDim2.new(0.782481492, 0, 0.101663314, 0)
RGBlgl.Size = UDim2.new(0, 276, 0, 31)
RGBlgl.Font = Enum.Font.SourceSans
RGBlgl.Text = "Sessão de Scripts poderosos 🌯🥪"
RGBlgl.TextColor3 = Color3.fromRGB(255, 255, 255)
RGBlgl.TextSize = 19.000

rgb.Name = "rgb"
rgb.Parent = RGBlgl
rgb.BackgroundColor3 = Color3.fromRGB(39, 0, 139)
rgb.BorderColor3 = Color3.fromRGB(0, 0, 0)
rgb.BorderSizePixel = 3
rgb.Position = UDim2.new(0, 0, 0.949277341, 0)
rgb.Size = UDim2.new(0, 276, 0, 562)

RGBButton.Name = "RGBButton"
RGBButton.Parent = rgb
RGBButton.BackgroundColor3 = Color3.fromRGB(4, 37, 145)
RGBButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
RGBButton.BorderSizePixel = 0
RGBButton.Position = UDim2.new(0.18822667, 0, 0.366199046, 0)
RGBButton.Size = UDim2.new(0, 158, 0, 58)
RGBButton.Font = Enum.Font.SourceSans
RGBButton.Text = "Ativar RGB"
RGBButton.TextColor3 = Color3.fromRGB(255, 255, 255)
RGBButton.TextSize = 32.000

MoveEntitiesButton.Name = "MoveEntitiesButton"
MoveEntitiesButton.Parent = RGBlgl
MoveEntitiesButton.BackgroundColor3 = Color3.fromRGB(4, 37, 145)
MoveEntitiesButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
MoveEntitiesButton.BorderSizePixel = 0
MoveEntitiesButton.Position = UDim2.new(0.183026299, 0, 4.87824535, 0)
MoveEntitiesButton.Size = UDim2.new(0, 159, 0, 58)
MoveEntitiesButton.Font = Enum.Font.SourceSans
MoveEntitiesButton.Text = "Dimensão"
MoveEntitiesButton.TextColor3 = Color3.fromRGB(255, 255, 255)
MoveEntitiesButton.TextSize = 32.000

button.Name = "button"
button.Parent = RGBlgl
button.BackgroundColor3 = Color3.fromRGB(4, 37, 145)
button.BorderColor3 = Color3.fromRGB(0, 0, 0)
button.BorderSizePixel = 0
button.Position = UDim2.new(0.0743306503, 0, 1.58866286, 0)
button.Size = UDim2.new(0, 227, 0, 58)
button.Font = Enum.Font.SourceSans
button.Text = "quebra da realidade"
button.TextColor3 = Color3.fromRGB(255, 255, 255)
button.TextSize = 32.000

_1Button.Name = "1Button"
_1Button.Parent = RGBlgl
_1Button.BackgroundColor3 = Color3.fromRGB(4, 37, 145)
_1Button.BorderColor3 = Color3.fromRGB(0, 0, 0)
_1Button.BorderSizePixel = 0
_1Button.Position = UDim2.new(0.196316928, 0, 10.0941792, 0)
_1Button.Size = UDim2.new(0, 158, 0, 58)
_1Button.Font = Enum.Font.SourceSans
_1Button.Text = "classic skin"
_1Button.TextColor3 = Color3.fromRGB(255, 255, 255)
_1Button.TextSize = 32.000

MessageButton.Name = "MessageButton"
MessageButton.Parent = RGBlgl
MessageButton.BackgroundColor3 = Color3.fromRGB(4, 37, 145)
MessageButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
MessageButton.BorderSizePixel = 0
MessageButton.Position = UDim2.new(0.196316928, 0, 12.7715988, 0)
MessageButton.Size = UDim2.new(0, 158, 0, 58)
MessageButton.Font = Enum.Font.SourceSans
MessageButton.Text = "bug mensage"
MessageButton.TextColor3 = Color3.fromRGB(255, 255, 255)
MessageButton.TextSize = 32.000

TextLabel_4.Parent = MessageButton
TextLabel_4.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_4.BackgroundTransparency = 0.500
TextLabel_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_4.BorderSizePixel = 0
TextLabel_4.Position = UDim2.new(-8.60784912, 0, 4.81173277, 0)
TextLabel_4.Size = UDim2.new(0, 1808, 0, 807)
TextLabel_4.Font = Enum.Font.SourceSans
TextLabel_4.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.TextSize = 46.000

MessageButton_2.Name = "MessageButton"
MessageButton_2.Parent = RGBlgl
MessageButton_2.BackgroundColor3 = Color3.fromRGB(4, 37, 145)
MessageButton_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
MessageButton_2.BorderSizePixel = 0
MessageButton_2.Position = UDim2.new(0.196316928, 0, 15.6748247, 0)
MessageButton_2.Size = UDim2.new(0, 158, 0, 58)
MessageButton_2.Font = Enum.Font.SourceSans
MessageButton_2.Text = "bug mensage2"
MessageButton_2.TextColor3 = Color3.fromRGB(255, 255, 255)
MessageButton_2.TextSize = 32.000

TextLabel_5.Parent = MessageButton_2
TextLabel_5.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_5.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_5.BorderSizePixel = 0
TextLabel_5.Position = UDim2.new(-8.53189945, 0, -9.77586174, 0)
TextLabel_5.Size = UDim2.new(0, 1808, 0, 57)
TextLabel_5.Font = Enum.Font.SourceSans
TextLabel_5.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_5.TextSize = 46.000

Button7.Name = "Button7"
Button7.Parent = ScreenGui
Button7.BackgroundColor3 = Color3.fromRGB(20, 40, 111)
Button7.BorderColor3 = Color3.fromRGB(0, 0, 0)
Button7.BorderSizePixel = 0
Button7.Position = UDim2.new(-0.000304136251, 0, 0.307708561, 0)
Button7.Size = UDim2.new(0, 69, 0, 61)
Button7.Font = Enum.Font.SourceSans
Button7.Text = "+"
Button7.TextColor3 = Color3.fromRGB(255, 255, 255)
Button7.TextSize = 54.000

-- Scripts:

local function TLLGYMJ_fake_script() -- flyLabel.DraggableLabel 
	local script = Instance.new('LocalScript', flyLabel)

	local UserInputService = game:GetService("UserInputService")
	local dragLabel = script.Parent
	
	local dragging = false
	local dragStart
	local startPos
	
	dragLabel.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 then
			dragging = true
			dragStart = input.Position
			startPos = dragLabel.Position
	
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragging = false
				end
			end)
		end
	end)
	
	UserInputService.InputChanged:Connect(function(input)
		if dragging and input.UserInputType == Enum.UserInputType.MouseMovement then
			local delta = input.Position - dragStart
			dragLabel.Position = UDim2.new(
				startPos.X.Scale,
				startPos.X.Offset + delta.X,
				startPos.Y.Scale,
				startPos.Y.Offset + delta.Y
			)
		end
	end)
	
	
end
coroutine.wrap(TLLGYMJ_fake_script)()
local function KFCM_fake_script() -- Cebola.LocalScript 
	local script = Instance.new('LocalScript', Cebola)

	local player = game.Players.LocalPlayer
	local cebolaButton = script.Parent -- O botão "Sanduiche"
	local replicatedStorage = game.ReplicatedStorage -- Onde você vai guardar a ferramenta temporariamente
	local toolName = "Tool" -- Nome da ferramenta
	
	-- Função para dar a ferramenta
	local function giveSandwich()
		local tool = replicatedStorage:FindFirstChild(toolName) -- Busca a ferramenta no ReplicatedStorage
		if tool then
			-- Clona a ferramenta e coloca no StarterPack (inventário do jogador)
			tool:Clone().Parent = player.Backpack
		end
	end
	
	-- Conectar o clique do botão à função giveSandwich
	cebolaButton.MouseButton1Click:Connect(giveSandwich)
	
	
end
coroutine.wrap(KFCM_fake_script)()
local function EWSOORV_fake_script() -- HotDog.LocalScript 
	local script = Instance.new('LocalScript', HotDog)

	local player = game.Players.LocalPlayer
	local hotdogButton = script.Parent -- O botão "Sanduiche"
	local replicatedStorage = game.ReplicatedStorage -- Onde você vai guardar a ferramenta temporariamente
	local toolName = "HotDog" -- Nome da ferramenta
	
	-- Função para dar a ferramenta
	local function giveSandwich()
		local tool = replicatedStorage:FindFirstChild(toolName) -- Busca a ferramenta no ReplicatedStorage
		if tool then
			-- Clona a ferramenta e coloca no StarterPack (inventário do jogador)
			tool:Clone().Parent = player.Backpack
		end
	end
	
	-- Conectar o clique do botão à função giveSandwich
	hotdogButton.MouseButton1Click:Connect(giveSandwich)
	
	
end
coroutine.wrap(EWSOORV_fake_script)()
local function RVKKKN_fake_script() -- flyLabel.LocalScript 
	local script = Instance.new('LocalScript', flyLabel)

	-- Referência para o TextButton
	local rgbButton = script.Parent:WaitForChild("RGBsessao")  -- O TextButton chamado RGBsessao
	
	-- O TextLabel está dentro do TextButton, então usamos "rgbButton" para encontrá-lo
	local textLabel = rgbButton:WaitForChild("RGBlgl")    -- O TextLabel chamado RGBlgl dentro do TextButton
	
	-- Inicialmente, o TextLabel estará invisível
	textLabel.Visible = false
	
	-- Função que será chamada quando o botão for clicado
	local function toggleTextLabelVisibility()
		-- Muda a visibilidade do TextLabel (alternando entre visível e invisível)
		textLabel.Visible = not textLabel.Visible
	end
	
	-- Conectando o clique do botão à função
	rgbButton.MouseButton1Click:Connect(toggleTextLabelVisibility)
	
end
coroutine.wrap(RVKKKN_fake_script)()
local function RKQYN_fake_script() -- InvisButton.LocalScript 
	local script = Instance.new('LocalScript', InvisButton)

	local player = game.Players.LocalPlayer
	local character = player.Character or player.CharacterAdded:Wait()
	local humanoid = character:WaitForChild("Humanoid")
	local invisButton = script.Parent -- O botão "Invisível"
	
	local invisivel = false -- Estado do modo invisível
	
	local function alternarInvisibilidade()
		invisivel = not invisivel
	
		if invisivel then
			-- Torna o personagem invisível
			for _, part in pairs(character:GetChildren()) do
				if part:IsA("BasePart") then
					part.Transparency = 1
					part.CanCollide = false -- Impede colisão para que o personagem não seja detectado
				end
			end
			humanoid.HealthDisplayDistance = 0 -- Torna a barra de vida invisível
			invisButton.Text = "Modo Visível" -- Muda o texto do botão
		else
			-- Restaura a visibilidade
			for _, part in pairs(character:GetChildren()) do
				if part:IsA("BasePart") then
					part.Transparency = 0
					part.CanCollide = true -- Restaura a colisão
				end
			end
			humanoid.HealthDisplayDistance = 100 -- Torna a barra de vida visível novamente
			invisButton.Text = "Modo Invisível" -- Muda o texto do botão
		end
	end
	
	invisButton.MouseButton1Click:Connect(alternarInvisibilidade)
	
	
end
coroutine.wrap(RKQYN_fake_script)()
local function NNZU_fake_script() -- Pizza.LocalScript 
	local script = Instance.new('LocalScript', Pizza)

	local player = game.Players.LocalPlayer
	local pizzaButton = script.Parent -- O botão "Sanduiche"
	local replicatedStorage = game.ReplicatedStorage -- Onde você vai guardar a ferramenta temporariamente
	local toolName = "Pizza" -- Nome da ferramenta
	
	-- Função para dar a ferramenta
	local function giveSandwich()
		local tool = replicatedStorage:FindFirstChild(toolName) -- Busca a ferramenta no ReplicatedStorage
		if tool then
			-- Clona a ferramenta e coloca no StarterPack (inventário do jogador)
			tool:Clone().Parent = player.Backpack
		end
	end
	
	-- Conectar o clique do botão à função giveSandwich
	pizzaButton.MouseButton1Click:Connect(giveSandwich)
	
	
end
coroutine.wrap(NNZU_fake_script)()
local function SDAXUQL_fake_script() -- Noclip.LocalScript 
	local script = Instance.new('LocalScript', Noclip)

	local player = game.Players.LocalPlayer
	local noclipButton = script.Parent -- O botão que você vai clicar
	
	local noclipEnabled = false
	local speed = 100 -- Defina a velocidade desejada
	
	-- Função para aplicar noclip
	local function applyNoclip(character)
		local humanoid = character:WaitForChild("Humanoid")
	
		if noclipEnabled then
			humanoid.WalkSpeed = speed
	
			-- Desativa colisão nas partes do personagem
			for _, part in pairs(character:GetChildren()) do
				if part:IsA("BasePart") then
					part.CanCollide = false
				end
			end
		else
			humanoid.WalkSpeed = 16 -- Velocidade normal
	
			-- Restaura a colisão nas partes do personagem
			for _, part in pairs(character:GetChildren()) do
				if part:IsA("BasePart") then
					part.CanCollide = true
				end
			end
		end
	end
	
	-- Função para alternar entre noclip e normal
	local function toggleNoclip()
		noclipEnabled = not noclipEnabled
		local character = player.Character or player.CharacterAdded:Wait()
		applyNoclip(character)
	end
	
	-- Monitorar respawns do personagem
	player.CharacterAdded:Connect(function(character)
		-- Aguarda o personagem ser completamente carregado
		wait(1)
		applyNoclip(character)
	end)
	
	-- Conectar o clique do botão à função toggleNoclip
	noclipButton.MouseButton1Click:Connect(toggleNoclip)
	
	
end
coroutine.wrap(SDAXUQL_fake_script)()
local function FMFLE_fake_script() -- Imortalidade.LocalScript 
	local script = Instance.new('LocalScript', Imortalidade)

	local player = game.Players.LocalPlayer
	local character = player.Character or player.CharacterAdded:Wait()
	local humanoid = character:WaitForChild("Humanoid")
	local imortalButton = script.Parent -- O botão "Imortalidade"
	
	-- Função para tornar o jogador imortal
	local function makeImmortal()
		humanoid.MaxHealth = math.huge -- Define a vida máxima como infinita
		humanoid.Health = math.huge -- Define a vida atual como infinita
	end
	
	-- Conectar o clique do botão à função makeImmortal
	imortalButton.MouseButton1Click:Connect(makeImmortal)
	
end
coroutine.wrap(FMFLE_fake_script)()
local function WUPF_fake_script() -- Sanduiche.LocalScript 
	local script = Instance.new('LocalScript', Sanduiche)

	local player = game.Players.LocalPlayer
	local sanduicheButton = script.Parent -- O botão "Sanduiche"
	local replicatedStorage = game.ReplicatedStorage -- Onde você vai guardar a ferramenta temporariamente
	local toolName = "Sandwich" -- Nome da ferramenta
	
	-- Função para dar a ferramenta
	local function giveSandwich()
		local tool = replicatedStorage:FindFirstChild(toolName) -- Busca a ferramenta no ReplicatedStorage
		if tool then
			-- Clona a ferramenta e coloca no StarterPack (inventário do jogador)
			tool:Clone().Parent = player.Backpack
		end
	end
	
	-- Conectar o clique do botão à função giveSandwich
	sanduicheButton.MouseButton1Click:Connect(giveSandwich)
	
	
end
coroutine.wrap(WUPF_fake_script)()
local function VZSPGC_fake_script() -- escudoButton.LocalScript 
	local script = Instance.new('LocalScript', escudoButton)

	local player = game.Players.LocalPlayer
	local character = player.Character or player.CharacterAdded:Wait()
	local humanoid = character:WaitForChild("Humanoid")
	local escudoButton = script.Parent -- O botão "Escudo Infinito"
	
	local escudoAtivo = false
	
	local function ativarEscudo()
		escudoAtivo = not escudoAtivo
	
		if escudoAtivo then
			-- Ativa o escudo (impede dano)
			humanoid.MaxHealth = humanoid.Health -- Garante que o jogador tem saúde infinita
			humanoid.HealthChanged:Connect(function()
				humanoid.Health = humanoid.MaxHealth -- Sempre restaura a saúde para o máximo
			end)
			escudoButton.Text = "Escudo Desativado"
		else
			-- Desativa o escudo (volta a saúde normal)
			humanoid.MaxHealth = 100 -- Ou o valor padrão de saúde que você quiser
			humanoid.Health = humanoid.MaxHealth
			escudoButton.Text = "Escudo Ativado"
		end
	end
	
	escudoButton.MouseButton1Click:Connect(ativarEscudo)
	
end
coroutine.wrap(VZSPGC_fake_script)()
local function GWUQ_fake_script() -- SpeedButton.LocalScript 
	local script = Instance.new('LocalScript', SpeedButton)

	local player = game.Players.LocalPlayer
	local character = player.Character or player.CharacterAdded:Wait()
	local humanoid = character:WaitForChild("Humanoid")
	local speedButton = script.Parent -- O botão SpeedButton
	
	-- Função para aumentar a velocidade
	local function increaseSpeed()
		humanoid.WalkSpeed = humanoid.WalkSpeed + 5 -- Aumenta a velocidade em +5
	end
	
	-- Conectar o clique do botão à função increaseSpeed
	speedButton.MouseButton1Click:Connect(increaseSpeed)
	
	
end
coroutine.wrap(GWUQ_fake_script)()
local function PBVQ_fake_script() -- SpeedButton2.LocalScript 
	local script = Instance.new('LocalScript', SpeedButton2)

	local player = game.Players.LocalPlayer
	local character = player.Character or player.CharacterAdded:Wait()
	local humanoid = character:WaitForChild("Humanoid")
	local speedButton2 = script.Parent -- O botão SpeedButton2
	
	-- Função para diminuir a velocidade
	local function decreaseSpeed()
		humanoid.WalkSpeed = humanoid.WalkSpeed - 5 -- Diminui a velocidade em -5
	end
	
	-- Conectar o clique do botão à função decreaseSpeed
	speedButton2.MouseButton1Click:Connect(decreaseSpeed)
	
end
coroutine.wrap(PBVQ_fake_script)()
local function FAQTYGX_fake_script() -- superForcaButton.LocalScript 
	local script = Instance.new('LocalScript', superForcaButton)

	local player = game.Players.LocalPlayer
	local character = player.Character or player.CharacterAdded:Wait()
	local superForcaButton = script.Parent -- O botão "Super Força"
	
	local forcaAtiva = false -- Estado da força
	
	local function empurrarObjetos()
		-- Empurra objetos ao redor do jogador com a super força
		local raio = 10 -- Distância onde ele pode empurrar objetos
		local objetos = workspace:FindPartsInRegion3(character.HumanoidRootPart.Position - Vector3.new(raio, raio, raio), character.HumanoidRootPart.Position + Vector3.new(raio, raio, raio), nil)
	
		for _, objeto in pairs(objetos) do
			if objeto:IsA("BasePart") then
				-- Empurra o objeto com força
				local direcao = (objeto.Position - character.HumanoidRootPart.Position).unit
				objeto:ApplyImpulse(direcao * 500) -- Aplique a força
			end
		end
	end
	
	local function alternarSuperForca()
		if forcaAtiva then
			forcaAtiva = false
			superForcaButton.Text = "Super Força" -- Muda o texto do botão
		else
			forcaAtiva = true
			superForcaButton.Text = "Força Normal" -- Muda o texto do botão
			-- Começa a empurrar objetos enquanto o modo estiver ativo
			while forcaAtiva do
				empurrarObjetos()
				wait(1) -- Verifica a cada 1 segundo para empurrar objetos
			end
		end
	end
	
	superForcaButton.MouseButton1Click:Connect(alternarSuperForca)
	
end
coroutine.wrap(FAQTYGX_fake_script)()
local function AANBFJ_fake_script() -- flyButton.LocalScript 
	local script = Instance.new('LocalScript', flyButton)

	local player = game.Players.LocalPlayer
	local character = player.Character or player.CharacterAdded:Wait()
	local humanoidRootPart = character:WaitForChild("HumanoidRootPart")
	local humanoid = character:WaitForChild("Humanoid")
	local flyButton = script.Parent
	local camera = game.Workspace.CurrentCamera
	
	local flying = false
	local speed = 50 -- Velocidade do voo
	local flyVelocity
	local flyGyro
	local userInputService = game:GetService("UserInputService")
	
	local function startFlying()
		if flying then return end
		flying = true
	
		-- Criar BodyVelocity para permitir movimento suave
		flyVelocity = Instance.new("BodyVelocity")
		flyVelocity.Velocity = Vector3.new(0, 0, 0)
		flyVelocity.MaxForce = Vector3.new(math.huge, math.huge, math.huge)
		flyVelocity.Parent = humanoidRootPart
	
		-- Criar BodyGyro para manter a rotação suave
		flyGyro = Instance.new("BodyGyro")
		flyGyro.CFrame = humanoidRootPart.CFrame
		flyGyro.MaxTorque = Vector3.new(math.huge, math.huge, math.huge)
		flyGyro.Parent = humanoidRootPart
	
		humanoid.PlatformStand = true -- Evita animações estranhas
		flyButton.Text = "Desativar Voo"
	end
	
	local function stopFlying()
		if not flying then return end
		flying = false
	
		if flyVelocity then flyVelocity:Destroy() end
		if flyGyro then flyGyro:Destroy() end
	
		humanoid.PlatformStand = false -- Volta ao normal
		flyButton.Text = "Ativar Voo"
	end
	
	local function updateFlying()
		if flying then
			local moveDirection = Vector3.new(0, 0, 0)
			local camLook = camera.CFrame.LookVector -- Pega a direção da câmera
	
			-- Detecta teclas de movimento e ajusta para seguir a câmera
			if userInputService:IsKeyDown(Enum.KeyCode.W) then
				moveDirection = moveDirection + camLook
			end
			if userInputService:IsKeyDown(Enum.KeyCode.S) then
				moveDirection = moveDirection - camLook
			end
			if userInputService:IsKeyDown(Enum.KeyCode.A) then
				moveDirection = moveDirection - camera.CFrame.RightVector
			end
			if userInputService:IsKeyDown(Enum.KeyCode.D) then
				moveDirection = moveDirection + camera.CFrame.RightVector
			end
	
			-- Normaliza a direção para evitar que a velocidade seja muito alta diagonalmente
			if moveDirection.Magnitude > 0 then
				moveDirection = moveDirection.Unit * speed
			end
	
			-- Aplica a movimentação ao personagem
			flyVelocity.Velocity = moveDirection
			flyGyro.CFrame = camera.CFrame -- Mantém o personagem alinhado à câmera
		end
	end
	
	flyButton.MouseButton1Click:Connect(function()
		if flying then
			stopFlying()
		else
			startFlying()
		end
	end)
	
	game:GetService("RunService").RenderStepped:Connect(updateFlying)
	
	
end
coroutine.wrap(AANBFJ_fake_script)()
local function SPIBQ_fake_script() -- hulkButton.HulkButtonClient 
	local script = Instance.new('LocalScript', hulkButton)

	local button = script.Parent
	local remoteEvent = game:GetService("ReplicatedStorage"):WaitForChild("ScaleAvatarEvent")
	
	button.MouseButton1Click:Connect(function()
	    remoteEvent:FireServer()
	end)
	
	
end
coroutine.wrap(SPIBQ_fake_script)()
local function YXVK_fake_script() -- smallButton.SmallButtonClient 
	local script = Instance.new('LocalScript', smallButton)

	local button = script.Parent
	local remoteEvent = game:GetService("ReplicatedStorage"):WaitForChild("ScaleAvatarDownEvent")
	
	button.MouseButton1Click:Connect(function()
	    remoteEvent:FireServer()
	end)
	
	
end
coroutine.wrap(YXVK_fake_script)()
local function SCAHPN_fake_script() -- miniButton.LocalScript 
	local script = Instance.new('LocalScript', miniButton)

	local player = game.Players.LocalPlayer
	local character = player.Character or player.CharacterAdded:Wait()
	local humanoid = character:WaitForChild("Humanoid")
	local miniButton = script.Parent -- O botão "Mini Jogador"
	
	local isMini = false -- Estado inicial
	
	local function toggleMini()
		if not character then return end
	
		isMini = not isMini -- Alterna entre mini e normal
	
		-- Define o tamanho (menor ou normal)
		local scale = isMini and 0.5 or 1
	
		-- Ajusta o tamanho corretamente
		for _, part in pairs(character:GetChildren()) do
			if part:IsA("BasePart") then
				part.Size = part.Size * scale
			elseif part:IsA("Accessory") then
				part.Handle.Size = part.Handle.Size * scale
			end
		end
	
		-- Ajusta a velocidade para evitar bugs
		humanoid.WalkSpeed = isMini and 10 or 16
		humanoid.JumpPower = isMini and 30 or 50
	
		-- Corrige a posição para evitar ficar preso no chão
		character:SetPrimaryPartCFrame(character.PrimaryPart.CFrame + Vector3.new(0, isMini and 2 or -2, 0))
	end
	
	miniButton.MouseButton1Click:Connect(toggleMini)
	
end
coroutine.wrap(SCAHPN_fake_script)()
local function EORHZ_fake_script() -- lagButton.LocalScript 
	local script = Instance.new('LocalScript', lagButton)

	local player = game.Players.LocalPlayer
	local character = player.Character or player.CharacterAdded:Wait()
	local humanoid = character:WaitForChild("Humanoid")
	local lagButton = script.Parent -- O botão "Fake Lag"
	
	local lagAtivo = false -- Estado do fake lag
	
	local function alternarFakeLag()
		if lagAtivo then
			-- Desativa o fake lag
			lagAtivo = false
			lagButton.Text = "Ativar Fake Lag"
			humanoid.WalkSpeed = 16 -- Restaura a velocidade normal
			humanoid.JumpPower = 50 -- Restaura o pulo normal
			game.Workspace.Gravity = 196.2 -- Restaura a gravidade normal
		else
			-- Ativa o fake lag
			lagAtivo = true
			lagButton.Text = "Desativar Fake Lag"
	
			-- Simula o fake lag com variação de velocidade e pulo mais lento
			spawn(function()
				while lagAtivo do
					-- Varia a velocidade para simular o lag
					humanoid.WalkSpeed = math.random(5, 6) -- Aleatoriza a velocidade do movimento
	
					-- De vez em quando o personagem "congela" (sem movimento)
					if math.random() > 0.5 then
						humanoid.WalkSpeed =4 -- O personagem vai parar de se mover
					end
	
					-- Torna o pulo mais lento
					humanoid.JumpPower = 310 -- Mantém o pulo no valor 60
	
					-- Altera a gravidade para tornar o pulo mais lento
					game.Workspace.Gravity = 1-- Diminui a gravidade para tornar o pulo mais lento
	
					wait(math.random(1, 5)) -- Atraso aleatório para simular a mudança de velocidade
				end
			end)
		end
	end
	
	lagButton.MouseButton1Click:Connect(alternarFakeLag)
	
end
coroutine.wrap(EORHZ_fake_script)()
local function IDGOT_fake_script() -- ScreenGui.LocalScript 
	local script = Instance.new('LocalScript', ScreenGui)

	-- Referência para o TextLabel onde o TextButton está
	local flyLabel = script.Parent:WaitForChild("flyLabel")  -- O TextLabel chamado flyLabel
	
	-- Dentro do flyLabel, procuramos o TextButton
	local rgbButton = flyLabel:WaitForChild("RGBsessao")  -- O TextButton chamado RGBsessao dentro do flyLabel
	
	-- Referência para o TextLabel que queremos tornar visível ou invisível
	local textLabel = script.Parent:WaitForChild("RGBlgl")  -- O TextLabel chamado RGBlgl dentro do ScreenGui
	
	-- Inicialmente, o TextLabel estará invisível
	textLabel.Visible = false
	
	-- Função que será chamada quando o botão for clicado
	local function toggleTextLabelVisibility()
		-- Muda a visibilidade do TextLabel (alternando entre visível e invisível)
		textLabel.Visible = not textLabel.Visible
	end
	
	-- Conectando o clique do botão à função
	rgbButton.MouseButton1Click:Connect(toggleTextLabelVisibility)
	
end
coroutine.wrap(IDGOT_fake_script)()
local function NHDJBA_fake_script() -- RGBButton.LocalScript 
	local script = Instance.new('LocalScript', RGBButton)

	local button = script.Parent  -- O botão RGBButton
	local isRGBAtivo = false  -- Controle do efeito
	
	local coresRGB = {  -- 40 cores RGB diferentes
		Color3.fromRGB(255, 0, 0), Color3.fromRGB(255, 127, 0), Color3.fromRGB(255, 255, 0), 
		Color3.fromRGB(127, 255, 0), Color3.fromRGB(0, 255, 0), Color3.fromRGB(0, 255, 127),
		Color3.fromRGB(0, 255, 255), Color3.fromRGB(0, 127, 255), Color3.fromRGB(0, 0, 255), 
		Color3.fromRGB(127, 0, 255), Color3.fromRGB(255, 0, 255), Color3.fromRGB(255, 0, 127),
		Color3.fromRGB(192, 57, 43), Color3.fromRGB(231, 76, 60), Color3.fromRGB(155, 89, 182),
		Color3.fromRGB(52, 152, 219), Color3.fromRGB(46, 204, 113), Color3.fromRGB(241, 196, 15),
		Color3.fromRGB(230, 126, 34), Color3.fromRGB(236, 240, 241), Color3.fromRGB(149, 165, 166),
		Color3.fromRGB(243, 156, 18), Color3.fromRGB(211, 84, 0), Color3.fromRGB(189, 195, 199),
		Color3.fromRGB(127, 140, 141), Color3.fromRGB(44, 62, 80), Color3.fromRGB(39, 174, 96),
		Color3.fromRGB(142, 68, 173), Color3.fromRGB(192, 57, 43), Color3.fromRGB(22, 160, 133),
		Color3.fromRGB(230, 126, 34), Color3.fromRGB(231, 76, 60), Color3.fromRGB(243, 156, 18),
		Color3.fromRGB(211, 84, 0), Color3.fromRGB(189, 195, 199), Color3.fromRGB(127, 140, 141),
		Color3.fromRGB(44, 62, 80), Color3.fromRGB(39, 174, 96), Color3.fromRGB(142, 68, 173)
	}
	
	local function aplicarRGB()
		for _, model in pairs(workspace:GetChildren()) do
			if model:IsA("Model") and model:FindFirstChildOfClass("Humanoid") then
				local corAleatoria = coresRGB[math.random(1, #coresRGB)]
				for _, part in pairs(model:GetChildren()) do
					if part:IsA("BasePart") then
						part.Color = corAleatoria
					end
				end
			end
		end
	end
	
	local function ativarRGB()
		isRGBAtivo = not isRGBAtivo  
	
		if isRGBAtivo then
			task.spawn(function()
				while isRGBAtivo do
					aplicarRGB()
					task.wait(0.5)  -- Agora troca a cor a cada 0.5 segundos (meio segundo)
				end
			end)
		end
	end
	
	button.MouseButton1Click:Connect(ativarRGB)
	
end
coroutine.wrap(NHDJBA_fake_script)()
local function YSEYS_fake_script() -- MoveEntitiesButton.LocalScript 
	local script = Instance.new('LocalScript', MoveEntitiesButton)

	local button = script.Parent
	local Lighting = game:GetService("Lighting")
	
	-- Função para ativar a Dimensão Sombria
	local function ativarDimensaoSombria()
		-- Altera a cor da luz ambiente para algo misterioso
		Lighting.Ambient = Color3.fromRGB(10, 10, 10)
		Lighting.FogColor = Color3.fromRGB(0, 0, 0)
		Lighting.FogStart = 0
		Lighting.FogEnd = 2000
	
		-- Muda a cor do céu para uma cor escura e misteriosa
		Lighting.Sky.SkyboxBk = "rbxassetid://123456789"  -- Coloque o ID de uma skybox sombria
	
		-- Altera o brilho para deixar o ambiente mais tenso
		Lighting.Brightness = 0
	end
	
	button.MouseButton1Click:Connect(ativarDimensaoSombria)
	
end
coroutine.wrap(YSEYS_fake_script)()
local function YDNMPNP_fake_script() -- button.LocalScript 
	local script = Instance.new('LocalScript', button)

	local button = script.Parent  -- O botão que ativa o caos
	local isRealityBroken = false  -- Controle do estado
	
	-- Função para inverter a gravidade dos NPCs e jogadores
	local function inverterGravidade(humanoid)
		if humanoid then
			humanoid.Parent.HumanoidRootPart.Anchored = false
			task.spawn(function()
				while isRealityBroken do
					humanoid.Parent.HumanoidRootPart.Velocity = Vector3.new(0, math.random(-100, 100), 0)  -- Joga NPCs e players para cima e para baixo
					task.wait(math.random(0.2, 1))  -- Aleatoriza o tempo entre os "saltos"
				end
			end)
		end
	end
	
	-- Função para mudar as cores de todos os objetos
	local function coresPsicodelicas()
		task.spawn(function()
			while isRealityBroken do
				for _, part in pairs(workspace:GetDescendants()) do
					if part:IsA("BasePart") then
						part.Color = Color3.new(math.random(), math.random(), math.random())  -- Cor aleatória
					end
				end
				task.wait(0.5)  -- Troca a cor a cada meio segundo
			end
		end)
	end
	
	-- Função para fazer os NPCs e players andarem para todos os lados
	local function fazerAndarLouco()
		for _, obj in pairs(workspace:GetDescendants()) do
			if obj:IsA("Model") and obj:FindFirstChildOfClass("Humanoid") then
				local humanoid = obj:FindFirstChildOfClass("Humanoid")
				if humanoid and obj ~= game.Players.LocalPlayer.Character then
					task.spawn(function()
						while isRealityBroken do
							local randomMove = Vector3.new(math.random(-50, 50), 0, math.random(-50, 50))  -- Movimentos aleatórios para todos os lados
							obj:SetPrimaryPartCFrame(obj.PrimaryPart.CFrame + randomMove)
							task.wait(0.1)  -- Aleatório, pode andar rápido ou devagar
						end
					end)
				end
			end
		end
	end
	
	-- Função para fazer os NPCs e players girarem loucamente
	local function girarNPCs()
		for _, obj in pairs(workspace:GetDescendants()) do
			if obj:IsA("Model") and obj:FindFirstChildOfClass("Humanoid") then
				local humanoid = obj:FindFirstChildOfClass("Humanoid")
				if humanoid and obj ~= game.Players.LocalPlayer.Character then
					task.spawn(function()
						while isRealityBroken do
							local root = obj:FindFirstChild("HumanoidRootPart")
							if root then
								root.RotVelocity = Vector3.new(0, math.random(-50, 50), 0)  -- Faz girar aleatoriamente
							end
							task.wait(0.1)
						end
					end)
				end
			end
		end
	end
	
	-- Função para tremer a tela dos outros jogadores
	local function tremerTela(player)
		local character = player.Character
		if character and character:FindFirstChild("HumanoidRootPart") then
			local root = character.HumanoidRootPart
	
			task.spawn(function()
				while isRealityBroken do
					root.Position = root.Position + Vector3.new(math.random(-2, 2), math.random(-2, 2), math.random(-2, 2))  -- Tremor forte
					task.wait(0.05)
				end
			end)
		end
	end
	
	-- Função para adicionar um som de erro bizarro
	local function adicionarSom()
		local sound = Instance.new("Sound")
		sound.SoundId = "rbxassetid://261561113"  -- Som de erro
		sound.Volume = 0.5
		sound.Looped = true
		sound.Parent = workspace
		sound:Play()
	
		task.spawn(function()
			while isRealityBroken do
				task.wait(5)
				sound.Playing = not sound.Playing  -- Alterna o som para deixar o efeito mais insano
			end
		end)
	end
	
	-- Função para ativar o "caos" no jogo
	local function ativarCaos()
		isRealityBroken = not isRealityBroken
	
		if isRealityBroken then
			coresPsicodelicas()  -- Ativa a mudança de cores psicodélicas
			fazerAndarLouco()  -- Faz NPCs e players se moverem de forma insana
			girarNPCs()  -- Faz girar os NPCs e players
			adicionarSom()  -- Som de erro bizarro
			-- Aplique inversão de gravidade e tremor de tela para todos
			for _, obj in pairs(workspace:GetDescendants()) do
				if obj:IsA("Model") and obj:FindFirstChildOfClass("Humanoid") then
					local humanoid = obj:FindFirstChildOfClass("Humanoid")
					if humanoid and obj ~= game.Players.LocalPlayer.Character then
						inverterGravidade(humanoid)  -- Inverte a gravidade
					end
				end
			end
	
			for _, player in pairs(game.Players:GetPlayers()) do
				if player ~= game.Players.LocalPlayer then
					tremerTela(player)  -- Tela tremendo
				end
			end
	
		else  -- Se clicar de novo, tudo volta ao normal
			for _, obj in pairs(workspace:GetDescendants()) do
				if obj:IsA("Model") and obj:FindFirstChildOfClass("Humanoid") then
					local humanoid = obj:FindFirstChildOfClass("Humanoid")
					if humanoid then
						humanoid.JumpPower = 50
						humanoid.WalkSpeed = 16
						humanoid.Parent.HumanoidRootPart.Velocity = Vector3.new(0, 0, 0)  -- Para de jogar NPCs para cima e para baixo
						humanoid.Parent.HumanoidRootPart.RotVelocity = Vector3.new(0, 0, 0)  -- Para de girar
					end
				end
			end
	
			for _, part in pairs(workspace:GetDescendants()) do
				if part:IsA("BasePart") then
					part.Color = Color3.fromRGB(255, 255, 255)  -- Volta as cores ao normal
				end
			end
		end
	end
	
	button.MouseButton1Click:Connect(ativarCaos)
	
end
coroutine.wrap(YDNMPNP_fake_script)()
local function DDTLKZ_fake_script() -- _1Button.LocalScript 
	local script = Instance.new('LocalScript', _1Button)

	local button = script.Parent  -- O botão que ativa/desativa o modo clássico quadrado
	local isClassicMode = false  -- Controle de estado
	local originalData = {}  -- Guarda as aparências e rigs originais
	
	local function salvarAparencia(character)
		if character and character.Parent then
			local player = game.Players:GetPlayerFromCharacter(character)
			if player and not originalData[player] then
				originalData[player] = {
					AppearanceId = player.CharacterAppearanceId,
					RigType = character:FindFirstChildOfClass("Humanoid") and character:FindFirstChildOfClass("Humanoid").RigType
				}
			end
		end
	end
	
	local function transformarParaQuadrado(character)
		if not character or not character.Parent then return end
		local humanoid = character:FindFirstChildOfClass("Humanoid")
		if not humanoid then return end
	
		-- Remove acessórios e roupas
		for _, obj in pairs(character:GetChildren()) do
			if obj:IsA("Accessory") or obj:IsA("Shirt") or obj:IsA("Pants") or obj:IsA("CharacterMesh") then
				obj:Destroy()
			end
		end
	
		-- Define as cores clássicas
		local bodyColors = character:FindFirstChild("BodyColors") or Instance.new("BodyColors")
		bodyColors.Parent = character
		bodyColors.HeadColor = BrickColor.new("Bright yellow")
		bodyColors.TorsoColor = BrickColor.new("Bright blue")
		bodyColors.LeftArmColor = BrickColor.new("Bright yellow")
		bodyColors.RightArmColor = BrickColor.new("Bright yellow")
		bodyColors.LeftLegColor = BrickColor.new("Bright green")
		bodyColors.RightLegColor = BrickColor.new("Bright green")
	
		-- Deixar completamente quadrado removendo R15
		if humanoid.RigType == Enum.HumanoidRigType.R15 then
			humanoid.RigType = Enum.HumanoidRigType.R6
		end
	end
	
	local function restaurarAparencia(character)
		if not character or not character.Parent then return end
		local player = game.Players:GetPlayerFromCharacter(character)
	
		if player and originalData[player] then
			-- Restaura aparência do jogador
			player.CharacterAppearanceId = originalData[player].AppearanceId
			player:LoadCharacter()
		elseif not player then
			-- Restaura NPCs
			local humanoid = character:FindFirstChildOfClass("Humanoid")
			if humanoid then
				local newDesc = Instance.new("HumanoidDescription")
				humanoid:ApplyDescription(newDesc)
			end
		end
	end
	
	local function mudarTodos()
		isClassicMode = not isClassicMode  -- Alterna entre ativado/desativado
	
		for _, player in pairs(game.Players:GetPlayers()) do
			if player ~= game.Players.LocalPlayer and player.Character then  -- Não muda você mesmo
				if isClassicMode then
					salvarAparencia(player.Character)
					transformarParaQuadrado(player.Character)
				else
					restaurarAparencia(player.Character)
				end
			end
		end
	
		-- Também muda NPCs
		for _, obj in pairs(workspace:GetDescendants()) do
			if obj:IsA("Model") and obj:FindFirstChildOfClass("Humanoid") and not game.Players:GetPlayerFromCharacter(obj) then
				if isClassicMode then
					transformarParaQuadrado(obj)
				else
					restaurarAparencia(obj)
				end
			end
		end
	end
	
	button.MouseButton1Click:Connect(mudarTodos)
	
end
coroutine.wrap(DDTLKZ_fake_script)()
local function AFGAQ_fake_script() -- MessageButton.LocalScript 
	local script = Instance.new('LocalScript', MessageButton)

	local button = script.Parent  -- O botão
	local textLabel = button:FindFirstChild("TextLabel")  -- O TextLabel dentro do botão
	
	-- Lista de mensagens em árabe
	local mensagensEmArabe = {
		"مرحبا! كيف حالك؟", -- "Olá! Como vai?"
		"ماذا تفعل؟", -- "O que você está fazendo?"
		"هذا مثير جدا!", -- "Isso é muito legal!"
		"كل شيء تحت السيطرة.", -- "Tudo sob controle."
		"هل تعرف أين نحن؟", -- "Você sabe onde estamos?"
		"الوقت يمر بسرعة.", -- "O tempo está passando rápido."
		"ابتسم! العالم مكان رائع.", -- "Sorria! O mundo é um lugar incrível."
		"انتظر قليلا...", -- "Aguarde um pouco..."
		"التكنولوجيا في كل مكان.", -- "A tecnologia está em todo lugar."
		"النجاح يتطلب وقتا وجهدا.", -- "O sucesso requer tempo e esforço."
	}
	
	-- Variável para controlar o índice da mensagem
	local indiceMensagem = 1
	
	-- Função para mudar a mensagem automaticamente a cada 3 segundos
	local function mudarMensagemAutomaticamente()
		while true do
			-- Muda o texto do TextLabel para a mensagem atual
			textLabel.Text = mensagensEmArabe[indiceMensagem]
	
			-- Aumenta o índice para a próxima mensagem
			indiceMensagem = indiceMensagem + 1
	
			-- Se atingiu o final da lista, volta para a primeira mensagem
			if indiceMensagem > #mensagensEmArabe then
				indiceMensagem = 1
			end
	
			-- Espera 3 segundos antes de mudar a mensagem
			wait(3)
		end
	end
	
	-- Função para ativar o TextLabel e iniciar a troca de mensagens
	local function ativarMensagens()
		textLabel.Visible = true  -- Torna o TextLabel visível
		mudarMensagemAutomaticamente()  -- Começa a exibir as mensagens automaticamente
	end
	
	-- Inicialmente, o TextLabel começa invisível
	textLabel.Visible = false
	
	-- Conectar o evento de clique do botão
	button.MouseButton1Click:Connect(ativarMensagens)
	
end
coroutine.wrap(AFGAQ_fake_script)()
local function RUCEOI_fake_script() -- MessageButton.LocalScript 
	local script = Instance.new('LocalScript', MessageButton)

	local button = script.Parent  -- O botão
	local textLabel = button:FindFirstChild("TextLabel")  -- O TextLabel dentro do botão
	
	-- Função para mostrar e esconder o TextLabel
	local function mostrarESumir()
		textLabel.Visible = true  -- Torna o TextLabel visível
		wait(9)  -- Espera 3 segundos
		textLabel.Visible = false  -- Torna o TextLabel invisível
	end
	
	-- Conectar o evento de clique do botão
	button.MouseButton1Click:Connect(mostrarESumir)
	
end
coroutine.wrap(RUCEOI_fake_script)()
local function GXKJRAR_fake_script() -- MessageButton_2.LocalScript 
	local script = Instance.new('LocalScript', MessageButton_2)

	local button = script.Parent  -- O botão
	local textLabel = button:FindFirstChild("TextLabel")  -- O TextLabel dentro do botão
	
	-- Lista de mensagens em árabe
	local mensagensEmArabe = {
		"مرحبا! كيف حالك؟", -- "Olá! Como vai?"
		"ماذا تفعل؟", -- "O que você está fazendo?"
		"هذا مثير جدا!", -- "Isso é muito legal!"
		"كل شيء تحت السيطرة.", -- "Tudo sob controle."
		"هل تعرف أين نحن؟", -- "Você sabe onde estamos?"
		"الوقت يمر بسرعة.", -- "O tempo está passando rápido."
		"ابتسم! العالم مكان رائع.", -- "Sorria! O mundo é um lugar incrível."
		"انتظر قليلا...", -- "Aguarde um pouco..."
		"التكنولوجيا في كل مكان.", -- "A tecnologia está em todo lugar."
		"النجاح يتطلب وقتا وجهدا.", -- "O sucesso requer tempo e esforço."
	}
	
	-- Variável para controlar o índice da mensagem
	local indiceMensagem = 1
	
	-- Função para mudar a mensagem automaticamente a cada 3 segundos
	local function mudarMensagemAutomaticamente()
		while true do
			-- Muda o texto do TextLabel para a mensagem atual
			textLabel.Text = mensagensEmArabe[indiceMensagem]
	
			-- Aumenta o índice para a próxima mensagem
			indiceMensagem = indiceMensagem + 1
	
			-- Se atingiu o final da lista, volta para a primeira mensagem
			if indiceMensagem > #mensagensEmArabe then
				indiceMensagem = 1
			end
	
			-- Espera 3 segundos antes de mudar a mensagem
			wait(3)
		end
	end
	
	-- Função para ativar o TextLabel e iniciar a troca de mensagens
	local function ativarMensagens()
		textLabel.Visible = true  -- Torna o TextLabel visível
		mudarMensagemAutomaticamente()  -- Começa a exibir as mensagens automaticamente
	end
	
	-- Inicialmente, o TextLabel começa invisível
	textLabel.Visible = false
	
	-- Conectar o evento de clique do botão
	button.MouseButton1Click:Connect(ativarMensagens)
	
end
coroutine.wrap(GXKJRAR_fake_script)()
local function UNPXJF_fake_script() -- Button7.DraggableLabel 
	local script = Instance.new('LocalScript', Button7)

	local UserInputService = game:GetService("UserInputService")
	local dragLabel = script.Parent
	
	local dragging = false
	local dragStart
	local startPos
	
	dragLabel.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 then
			dragging = true
			dragStart = input.Position
			startPos = dragLabel.Position
	
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragging = false
				end
			end)
		end
	end)
	
	UserInputService.InputChanged:Connect(function(input)
		if dragging and input.UserInputType == Enum.UserInputType.MouseMovement then
			local delta = input.Position - dragStart
			dragLabel.Position = UDim2.new(
				startPos.X.Scale,
				startPos.X.Offset + delta.X,
				startPos.Y.Scale,
				startPos.Y.Offset + delta.Y
			)
		end
	end)
	
	
end
coroutine.wrap(UNPXJF_fake_script)()
local function TAZB_fake_script() -- ScreenGui.LocalScript 
	local script = Instance.new('LocalScript', ScreenGui)

	-- Acessando os objetos
	local flyLabel = script.Parent  -- O TextLabel (flyLabel)
	local TextButton1 = flyLabel:WaitForChild("TextButton1")  -- O botão inicial dentro do flyLabel
	local Button7 = script.Parent.Parent:WaitForChild("Button7")  -- Button7 está fora do flyLabel, mas dentro do ScreenGui
	
	-- Inicializando Button7 como invisível
	Button7.Visible = false
	
	-- Função para esconder o flyLabel e mostrar Button7
	local function esconderFlyLabel()
		flyLabel.Visible = false
		Button7.Visible = true  -- Button7 se torna visível após clicar no TextButton1
	end
	
	-- Função para mostrar o flyLabel e esconder Button7
	local function mostrarFlyLabel()
		flyLabel.Visible = true
		Button7.Visible = false  -- Button7 desaparece novamente quando clicado
	end
	
	-- Quando o TextButton1 for clicado, esconde o flyLabel e mostra Button7
	TextButton1.MouseButton1Click:Connect(esconderFlyLabel)
	
	-- Quando Button7 for clicado, mostra o flyLabel novamente e esconde Button7
	Button7.MouseButton1Click:Connect(mostrarFlyLabel)
	-- Acessando os objetos
	local flyLabel = script.Parent  -- O TextLabel (flyLabel)
	local TextButton1 = flyLabel:WaitForChild("TextButton1")  -- O botão inicial dentro do flyLabel
	local Button7 = script.Parent.Parent:WaitForChild("Button7")  -- Button7 está fora do flyLabel, mas dentro do ScreenGui
	
	-- Inicializando Button7 como invisível
	Button7.Visible = false
	
	-- Função para esconder o flyLabel e mostrar Button7
	local function esconderFlyLabel()
		flyLabel.Visible = false
		Button7.Visible = true  -- Button7 se torna visível após clicar no TextButton1
	end
	
	-- Função para mostrar o flyLabel e esconder Button7
	local function mostrarFlyLabel()
		flyLabel.Visible = true
		Button7.Visible = false  -- Button7 desaparece novamente quando clicado
	end
	
	-- Quando o TextButton1 for clicado, esconde o flyLabel e mostra Button7
	TextButton1.MouseButton1Click:Connect(esconderFlyLabel)
	
	-- Quando Button7 for clicado, mostra o flyLabel novamente e esconde Button7
	Button7.MouseButton1Click:Connect(mostrarFlyLabel)
	
end
coroutine.wrap(TAZB_fake_script)()
local function OBNIDW_fake_script() -- ScreenGui.Script 
	local script = Instance.new('Script', ScreenGui)

	-- Acessando os objetos
	local flyLabel = script.Parent  -- O TextLabel (flyLabel)
	local TextButton1 = flyLabel:WaitForChild("TextButton1")  -- O botão inicial dentro do flyLabel
	local Button7 = script.Parent.Parent:WaitForChild("Button7")  -- Button7 está fora do flyLabel, mas dentro do ScreenGui
	
	-- Inicializando Button7 como invisível
	Button7.Visible = false
	
	-- Função para esconder o flyLabel e mostrar Button7
	local function esconderFlyLabel()
		flyLabel.Visible = false
		Button7.Visible = true  -- Button7 se torna visível após clicar no TextButton1
	end
	
	-- Função para mostrar o flyLabel e esconder Button7
	local function mostrarFlyLabel()
		flyLabel.Visible = true
		Button7.Visible = false  -- Button7 desaparece novamente quando clicado
	end
	
	-- Quando o TextButton1 for clicado, esconde o flyLabel e mostra Button7
	TextButton1.MouseButton1Click:Connect(esconderFlyLabel)
	
	-- Quando Button7 for clicado, mostra o flyLabel novamente e esconde Button7
	Button7.MouseButton1Click:Connect(mostrarFlyLabel)
	
end
coroutine.wrap(OBNIDW_fake_script)()
