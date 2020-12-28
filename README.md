-- Gui to Lua
-- Version: 3.2

-- Instances:

local RadiantLuckyBlocks = Instance.new("ScreenGui")
local Topbar = Instance.new("ImageLabel")
local LuckyBlocks = Instance.new("TextLabel")
local Line = Instance.new("ImageLabel")
local UIGradient = Instance.new("UIGradient")
local MainContainer = Instance.new("ScrollingFrame")
local Container2 = Instance.new("Frame")
local GetGear = Instance.new("ImageLabel")
local GetGearButton = Instance.new("TextButton")
local TextButton_Roundify_4px = Instance.new("ImageLabel")
local Fly = Instance.new("ImageLabel")
local FlyButton = Instance.new("TextButton")
local TextButton_Roundify_4px_2 = Instance.new("ImageLabel")
local Misc = Instance.new("TextLabel")
local WalkspeedFrame = Instance.new("ImageLabel")
local WalkSpeedSlider = Instance.new("TextButton")
local TextButton_Roundify_4px_3 = Instance.new("ImageLabel")
local WalkSpeedInner = Instance.new("ImageLabel")
local UIGradient_2 = Instance.new("UIGradient")
local WalkSpeedCount = Instance.new("TextLabel")
local WalkspeedText = Instance.new("TextLabel")
local JumpPowerFrame = Instance.new("ImageLabel")
local JumpPowerSlider = Instance.new("TextButton")
local TextButton_Roundify_4px_4 = Instance.new("ImageLabel")
local JumpPowerInner = Instance.new("ImageLabel")
local UIGradient_3 = Instance.new("UIGradient")
local JumpPowerCount = Instance.new("TextLabel")
local JumpPowerText = Instance.new("TextLabel")
local Function = Instance.new("TextLabel")
local InfinityJump = Instance.new("ImageButton")
local ButtonOFF = Instance.new("ImageButton")
local UIGradient_4 = Instance.new("UIGradient")
local ButtonON = Instance.new("ImageButton")
local UIGradient_5 = Instance.new("UIGradient")
local InfinityJumpText = Instance.new("TextLabel")
local TpTools = Instance.new("ImageLabel")
local TpToolsButton = Instance.new("TextButton")
local TextButton_Roundify_4px_5 = Instance.new("ImageLabel")
local Button = Instance.new("ImageButton")

--Properties:

RadiantLuckyBlocks.Name = "Radiant-LuckyBlocks"
RadiantLuckyBlocks.Parent = game.CoreGui

Topbar.Name = "Topbar"
Topbar.Parent = RadiantLuckyBlocks
Topbar.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Topbar.BackgroundTransparency = 1.000
Topbar.Position = UDim2.new(0.00907715596, 0, 0.0212443098, 0)
Topbar.Size = UDim2.new(0, 163, 0, 33)
Topbar.Image = "rbxassetid://3570695787"
Topbar.ImageColor3 = Color3.fromRGB(15, 15, 15)
Topbar.ScaleType = Enum.ScaleType.Slice
Topbar.SliceCenter = Rect.new(100, 100, 100, 100)
Topbar.SliceScale = 0.040

LuckyBlocks.Name = "LuckyBlocks"
LuckyBlocks.Parent = Topbar
LuckyBlocks.Active = true
LuckyBlocks.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LuckyBlocks.BackgroundTransparency = 1.000
LuckyBlocks.Size = UDim2.new(0, 104, 0, 33)
LuckyBlocks.Font = Enum.Font.SourceSansSemibold
LuckyBlocks.Text = "LUCKY BLOCKS"
LuckyBlocks.TextColor3 = Color3.fromRGB(255, 255, 255)
LuckyBlocks.TextSize = 14.000

Line.Name = "Line"
Line.Parent = Topbar
Line.Active = true
Line.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Line.BackgroundTransparency = 1.000
Line.Position = UDim2.new(0, 0, 0.939393997, 0)
Line.Size = UDim2.new(0, 163, 0, 2)
Line.Image = "rbxassetid://3570695787"
Line.ScaleType = Enum.ScaleType.Slice
Line.SliceCenter = Rect.new(100, 100, 100, 100)
Line.SliceScale = 0.040

UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(182, 141, 159)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(64, 96, 161))}
UIGradient.Parent = Line

MainContainer.Name = "MainContainer"
MainContainer.Parent = Topbar
MainContainer.Active = true
MainContainer.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
MainContainer.BorderColor3 = Color3.fromRGB(20, 20, 20)
MainContainer.BorderSizePixel = 0
MainContainer.Position = UDim2.new(0, 0, 1, 0)
MainContainer.Size = UDim2.new(0, 163, 0, 0)
MainContainer.ScrollBarThickness = 0
MainContainer.ScrollingEnabled = false

Container2.Name = "Container2"
Container2.Parent = MainContainer
Container2.Active = true
Container2.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
Container2.BorderColor3 = Color3.fromRGB(20, 20, 20)
Container2.Size = UDim2.new(0, 163, 0, 250)

GetGear.Name = "GetGear"
GetGear.Parent = Container2
GetGear.Active = true
GetGear.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
GetGear.BackgroundTransparency = 1.000
GetGear.Position = UDim2.new(0.030674845, 0, 0.0240000002, 0)
GetGear.Size = UDim2.new(0, 152, 0, 33)
GetGear.Image = "rbxassetid://3570695787"
GetGear.ImageColor3 = Color3.fromRGB(35, 35, 35)
GetGear.ScaleType = Enum.ScaleType.Slice
GetGear.SliceCenter = Rect.new(100, 100, 100, 100)
GetGear.SliceScale = 0.040

GetGearButton.Name = "GetGearButton"
GetGearButton.Parent = GetGear
GetGearButton.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
GetGearButton.BackgroundTransparency = 1.000
GetGearButton.BorderColor3 = Color3.fromRGB(30, 30, 30)
GetGearButton.BorderSizePixel = 0
GetGearButton.Position = UDim2.new(0.0394736864, 0, 0.121212125, 0)
GetGearButton.Size = UDim2.new(0, 141, 0, 25)
GetGearButton.ZIndex = 2
GetGearButton.Font = Enum.Font.SourceSansSemibold
GetGearButton.Text = "GET GEAR"
GetGearButton.TextColor3 = Color3.fromRGB(255, 255, 255)
GetGearButton.TextSize = 13.000

TextButton_Roundify_4px.Name = "TextButton_Roundify_4px"
TextButton_Roundify_4px.Parent = GetGearButton
TextButton_Roundify_4px.Active = true
TextButton_Roundify_4px.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_4px.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_4px.BackgroundTransparency = 1.000
TextButton_Roundify_4px.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_4px.Selectable = true
TextButton_Roundify_4px.Size = UDim2.new(1, 0, 1, 0)
TextButton_Roundify_4px.Image = "rbxassetid://3570695787"
TextButton_Roundify_4px.ImageColor3 = Color3.fromRGB(30, 30, 30)
TextButton_Roundify_4px.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_4px.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_4px.SliceScale = 0.040

Fly.Name = "Fly"
Fly.Parent = Container2
Fly.Active = true
Fly.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Fly.BackgroundTransparency = 1.000
Fly.Position = UDim2.new(0.030674845, 0, 0.180000022, 0)
Fly.Size = UDim2.new(0, 152, 0, 33)
Fly.Image = "rbxassetid://3570695787"
Fly.ImageColor3 = Color3.fromRGB(35, 35, 35)
Fly.ScaleType = Enum.ScaleType.Slice
Fly.SliceCenter = Rect.new(100, 100, 100, 100)
Fly.SliceScale = 0.040

FlyButton.Name = "FlyButton"
FlyButton.Parent = Fly
FlyButton.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
FlyButton.BackgroundTransparency = 1.000
FlyButton.BorderColor3 = Color3.fromRGB(30, 30, 30)
FlyButton.BorderSizePixel = 0
FlyButton.Position = UDim2.new(0.0394736864, 0, 0.121212125, 0)
FlyButton.Size = UDim2.new(0, 141, 0, 25)
FlyButton.ZIndex = 2
FlyButton.Font = Enum.Font.SourceSansSemibold
FlyButton.Text = "FLY ( PRESS F )"
FlyButton.TextColor3 = Color3.fromRGB(255, 255, 255)
FlyButton.TextSize = 13.000

TextButton_Roundify_4px_2.Name = "TextButton_Roundify_4px"
TextButton_Roundify_4px_2.Parent = FlyButton
TextButton_Roundify_4px_2.Active = true
TextButton_Roundify_4px_2.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_4px_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_4px_2.BackgroundTransparency = 1.000
TextButton_Roundify_4px_2.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_4px_2.Selectable = true
TextButton_Roundify_4px_2.Size = UDim2.new(1, 0, 1, 0)
TextButton_Roundify_4px_2.Image = "rbxassetid://3570695787"
TextButton_Roundify_4px_2.ImageColor3 = Color3.fromRGB(30, 30, 30)
TextButton_Roundify_4px_2.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_4px_2.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_4px_2.SliceScale = 0.040

Misc.Name = "Misc."
Misc.Parent = Container2
Misc.Active = true
Misc.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
Misc.BorderColor3 = Color3.fromRGB(20, 20, 20)
Misc.Position = UDim2.new(0, 0, 0.312000006, 0)
Misc.Size = UDim2.new(0, 163, 0, 17)
Misc.Font = Enum.Font.SourceSansSemibold
Misc.Text = "Misc."
Misc.TextColor3 = Color3.fromRGB(95, 95, 95)
Misc.TextSize = 14.000

WalkspeedFrame.Name = "WalkspeedFrame"
WalkspeedFrame.Parent = Container2
WalkspeedFrame.Active = true
WalkspeedFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
WalkspeedFrame.BackgroundTransparency = 1.000
WalkspeedFrame.Position = UDim2.new(0.030674845, 0, 0.408000052, 0)
WalkspeedFrame.Size = UDim2.new(0, 152, 0, 33)
WalkspeedFrame.Image = "rbxassetid://3570695787"
WalkspeedFrame.ImageColor3 = Color3.fromRGB(35, 35, 35)
WalkspeedFrame.ScaleType = Enum.ScaleType.Slice
WalkspeedFrame.SliceCenter = Rect.new(100, 100, 100, 100)
WalkspeedFrame.SliceScale = 0.040

WalkSpeedSlider.Name = "WalkSpeedSlider"
WalkSpeedSlider.Parent = WalkspeedFrame
WalkSpeedSlider.BackgroundColor3 = Color3.fromRGB(15, 15, 15)
WalkSpeedSlider.BackgroundTransparency = 1.000
WalkSpeedSlider.BorderColor3 = Color3.fromRGB(15, 15, 15)
WalkSpeedSlider.BorderSizePixel = 0
WalkSpeedSlider.Position = UDim2.new(0.0394736826, 0, 0.636363626, 0)
WalkSpeedSlider.Size = UDim2.new(0, 141, 0, 5)
WalkSpeedSlider.ZIndex = 2
WalkSpeedSlider.Font = Enum.Font.SourceSans
WalkSpeedSlider.Text = ""
WalkSpeedSlider.TextColor3 = Color3.fromRGB(0, 0, 0)
WalkSpeedSlider.TextSize = 14.000

TextButton_Roundify_4px_3.Name = "TextButton_Roundify_4px"
TextButton_Roundify_4px_3.Parent = WalkSpeedSlider
TextButton_Roundify_4px_3.Active = true
TextButton_Roundify_4px_3.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_4px_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_4px_3.BackgroundTransparency = 1.000
TextButton_Roundify_4px_3.Position = UDim2.new(0.492907792, 0, 0.699999988, 0)
TextButton_Roundify_4px_3.Selectable = true
TextButton_Roundify_4px_3.Size = UDim2.new(1, 0, 1, 0)
TextButton_Roundify_4px_3.Image = "rbxassetid://3570695787"
TextButton_Roundify_4px_3.ImageColor3 = Color3.fromRGB(15, 15, 15)
TextButton_Roundify_4px_3.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_4px_3.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_4px_3.SliceScale = 0.040

WalkSpeedInner.Name = "WalkSpeedInner"
WalkSpeedInner.Parent = WalkSpeedSlider
WalkSpeedInner.Active = true
WalkSpeedInner.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
WalkSpeedInner.BackgroundTransparency = 1.000
WalkSpeedInner.Position = UDim2.new(0, 0, 0.199996948, 0)
WalkSpeedInner.Size = UDim2.new(0, 0, 0, 5)
WalkSpeedInner.Image = "rbxassetid://3570695787"
WalkSpeedInner.ScaleType = Enum.ScaleType.Slice
WalkSpeedInner.SliceCenter = Rect.new(100, 100, 100, 100)
WalkSpeedInner.SliceScale = 0.040

UIGradient_2.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(182, 141, 159)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(64, 96, 161))}
UIGradient_2.Parent = WalkSpeedInner

WalkSpeedCount.Name = "WalkSpeedCount"
WalkSpeedCount.Parent = WalkSpeedSlider
WalkSpeedCount.Active = true
WalkSpeedCount.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
WalkSpeedCount.BackgroundTransparency = 1.000
WalkSpeedCount.Position = UDim2.new(0.822695017, 0, -4.4000001, 0)
WalkSpeedCount.Size = UDim2.new(0, 25, 0, 27)
WalkSpeedCount.Font = Enum.Font.SourceSansSemibold
WalkSpeedCount.Text = "16"
WalkSpeedCount.TextColor3 = Color3.fromRGB(255, 255, 255)
WalkSpeedCount.TextSize = 13.000

WalkspeedText.Name = "WalkspeedText"
WalkspeedText.Parent = WalkspeedFrame
WalkspeedText.Active = true
WalkspeedText.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
WalkspeedText.BackgroundTransparency = 1.000
WalkspeedText.Position = UDim2.new(-0.032894738, 0, 0.0303030312, 0)
WalkspeedText.Size = UDim2.new(0, 82, 0, 26)
WalkspeedText.Font = Enum.Font.SourceSansSemibold
WalkspeedText.Text = "WALKSPEED"
WalkspeedText.TextColor3 = Color3.fromRGB(255, 255, 255)
WalkspeedText.TextSize = 13.000

JumpPowerFrame.Name = "JumpPowerFrame"
JumpPowerFrame.Parent = Container2
JumpPowerFrame.Active = true
JumpPowerFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
JumpPowerFrame.BackgroundTransparency = 1.000
JumpPowerFrame.Position = UDim2.new(0.030674845, 0, 0.56400007, 0)
JumpPowerFrame.Size = UDim2.new(0, 152, 0, 33)
JumpPowerFrame.Image = "rbxassetid://3570695787"
JumpPowerFrame.ImageColor3 = Color3.fromRGB(35, 35, 35)
JumpPowerFrame.ScaleType = Enum.ScaleType.Slice
JumpPowerFrame.SliceCenter = Rect.new(100, 100, 100, 100)
JumpPowerFrame.SliceScale = 0.040

JumpPowerSlider.Name = "JumpPowerSlider"
JumpPowerSlider.Parent = JumpPowerFrame
JumpPowerSlider.BackgroundColor3 = Color3.fromRGB(15, 15, 15)
JumpPowerSlider.BackgroundTransparency = 1.000
JumpPowerSlider.BorderColor3 = Color3.fromRGB(15, 15, 15)
JumpPowerSlider.BorderSizePixel = 0
JumpPowerSlider.Position = UDim2.new(0.0394736826, 0, 0.636363626, 0)
JumpPowerSlider.Size = UDim2.new(0, 141, 0, 5)
JumpPowerSlider.ZIndex = 2
JumpPowerSlider.Font = Enum.Font.SourceSans
JumpPowerSlider.Text = ""
JumpPowerSlider.TextColor3 = Color3.fromRGB(0, 0, 0)
JumpPowerSlider.TextSize = 14.000

TextButton_Roundify_4px_4.Name = "TextButton_Roundify_4px"
TextButton_Roundify_4px_4.Parent = JumpPowerSlider
TextButton_Roundify_4px_4.Active = true
TextButton_Roundify_4px_4.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_4px_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_4px_4.BackgroundTransparency = 1.000
TextButton_Roundify_4px_4.Position = UDim2.new(0.492907792, 0, 0.699999988, 0)
TextButton_Roundify_4px_4.Selectable = true
TextButton_Roundify_4px_4.Size = UDim2.new(1, 0, 1, 0)
TextButton_Roundify_4px_4.Image = "rbxassetid://3570695787"
TextButton_Roundify_4px_4.ImageColor3 = Color3.fromRGB(15, 15, 15)
TextButton_Roundify_4px_4.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_4px_4.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_4px_4.SliceScale = 0.040

JumpPowerInner.Name = "JumpPowerInner"
JumpPowerInner.Parent = JumpPowerSlider
JumpPowerInner.Active = true
JumpPowerInner.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
JumpPowerInner.BackgroundTransparency = 1.000
JumpPowerInner.Position = UDim2.new(0, 0, 0.199996948, 0)
JumpPowerInner.Size = UDim2.new(0, 0, 0, 5)
JumpPowerInner.Image = "rbxassetid://3570695787"
JumpPowerInner.ScaleType = Enum.ScaleType.Slice
JumpPowerInner.SliceCenter = Rect.new(100, 100, 100, 100)
JumpPowerInner.SliceScale = 0.040

UIGradient_3.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(182, 141, 159)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(64, 96, 161))}
UIGradient_3.Parent = JumpPowerInner

JumpPowerCount.Name = "JumpPowerCount"
JumpPowerCount.Parent = JumpPowerSlider
JumpPowerCount.Active = true
JumpPowerCount.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
JumpPowerCount.BackgroundTransparency = 1.000
JumpPowerCount.Position = UDim2.new(0.822695017, 0, -4.4000001, 0)
JumpPowerCount.Size = UDim2.new(0, 25, 0, 27)
JumpPowerCount.Font = Enum.Font.SourceSansSemibold
JumpPowerCount.Text = "50"
JumpPowerCount.TextColor3 = Color3.fromRGB(255, 255, 255)
JumpPowerCount.TextSize = 13.000

JumpPowerText.Name = "JumpPowerText"
JumpPowerText.Parent = JumpPowerFrame
JumpPowerText.Active = true
JumpPowerText.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
JumpPowerText.BackgroundTransparency = 1.000
JumpPowerText.Position = UDim2.new(-0.032894738, 0, 0.0303030312, 0)
JumpPowerText.Size = UDim2.new(0, 82, 0, 26)
JumpPowerText.Font = Enum.Font.SourceSansSemibold
JumpPowerText.Text = "JUMPPOWER"
JumpPowerText.TextColor3 = Color3.fromRGB(255, 255, 255)
JumpPowerText.TextSize = 13.000

Function.Name = "Function"
Function.Parent = Container2
Function.Active = true
Function.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
Function.BorderColor3 = Color3.fromRGB(20, 20, 20)
Function.Position = UDim2.new(-0.00613496918, 0, 0.69599998, 0)
Function.Size = UDim2.new(0, 163, 0, 22)
Function.Font = Enum.Font.SourceSansSemibold
Function.Text = "Funtion."
Function.TextColor3 = Color3.fromRGB(95, 95, 95)
Function.TextSize = 14.000

InfinityJump.Name = "InfinityJump"
InfinityJump.Parent = Container2
InfinityJump.BackgroundTransparency = 1.000
InfinityJump.Position = UDim2.new(0.779141128, 0, 0.783999979, 0)
InfinityJump.Size = UDim2.new(0, 25, 0, 25)
InfinityJump.ZIndex = 2
InfinityJump.Image = "rbxassetid://3926309567"
InfinityJump.ImageRectOffset = Vector2.new(628, 420)
InfinityJump.ImageRectSize = Vector2.new(48, 48)

ButtonOFF.Name = "ButtonOFF"
ButtonOFF.Parent = InfinityJump
ButtonOFF.BackgroundTransparency = 1.000
ButtonOFF.Position = UDim2.new(0.239999995, 0, 0.239999995, 0)
ButtonOFF.Size = UDim2.new(0, 13, 0, 13)
ButtonOFF.ZIndex = 2
ButtonOFF.Image = "rbxassetid://3926305904"
ButtonOFF.ImageRectOffset = Vector2.new(124, 124)
ButtonOFF.ImageRectSize = Vector2.new(36, 36)
ButtonOFF.ImageTransparency = 1.000

UIGradient_4.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(182, 141, 159)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(64, 96, 161))}
UIGradient_4.Parent = ButtonOFF

ButtonON.Name = "ButtonON"
ButtonON.Parent = InfinityJump
ButtonON.BackgroundTransparency = 1.000
ButtonON.Position = UDim2.new(0.239999995, 0, 0.239999995, 0)
ButtonON.Size = UDim2.new(0, 13, 0, 13)
ButtonON.Visible = false
ButtonON.ZIndex = 2
ButtonON.Image = "rbxassetid://3926305904"
ButtonON.ImageRectOffset = Vector2.new(124, 124)
ButtonON.ImageRectSize = Vector2.new(36, 36)

UIGradient_5.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(182, 141, 159)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(64, 96, 161))}
UIGradient_5.Parent = ButtonON

InfinityJumpText.Name = "InfinityJumpText"
InfinityJumpText.Parent = InfinityJump
InfinityJumpText.Active = true
InfinityJumpText.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
InfinityJumpText.BackgroundTransparency = 1.000
InfinityJumpText.Position = UDim2.new(-4.88000011, 0, 0, 0)
InfinityJumpText.Size = UDim2.new(0, 122, 0, 25)
InfinityJumpText.Font = Enum.Font.SourceSansSemibold
InfinityJumpText.Text = "INFINITY JUMP"
InfinityJumpText.TextColor3 = Color3.fromRGB(255, 255, 255)
InfinityJumpText.TextSize = 13.000

TpTools.Name = "TpTools"
TpTools.Parent = Container2
TpTools.Active = true
TpTools.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TpTools.BackgroundTransparency = 1.000
TpTools.Position = UDim2.new(0.030674845, 0, 0.907999992, 0)
TpTools.Size = UDim2.new(0, 152, 0, 33)
TpTools.Image = "rbxassetid://3570695787"
TpTools.ImageColor3 = Color3.fromRGB(35, 35, 35)
TpTools.ScaleType = Enum.ScaleType.Slice
TpTools.SliceCenter = Rect.new(100, 100, 100, 100)
TpTools.SliceScale = 0.040

TpToolsButton.Name = "TpToolsButton"
TpToolsButton.Parent = TpTools
TpToolsButton.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
TpToolsButton.BackgroundTransparency = 1.000
TpToolsButton.BorderColor3 = Color3.fromRGB(30, 30, 30)
TpToolsButton.BorderSizePixel = 0
TpToolsButton.Position = UDim2.new(0.0394736864, 0, 0.121212125, 0)
TpToolsButton.Size = UDim2.new(0, 141, 0, 25)
TpToolsButton.ZIndex = 2
TpToolsButton.Font = Enum.Font.SourceSansSemibold
TpToolsButton.Text = "TELEPORT TOOL"
TpToolsButton.TextColor3 = Color3.fromRGB(255, 255, 255)
TpToolsButton.TextSize = 13.000

TextButton_Roundify_4px_5.Name = "TextButton_Roundify_4px"
TextButton_Roundify_4px_5.Parent = TpToolsButton
TextButton_Roundify_4px_5.Active = true
TextButton_Roundify_4px_5.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_4px_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_4px_5.BackgroundTransparency = 1.000
TextButton_Roundify_4px_5.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_4px_5.Selectable = true
TextButton_Roundify_4px_5.Size = UDim2.new(1, 0, 1, 0)
TextButton_Roundify_4px_5.Image = "rbxassetid://3570695787"
TextButton_Roundify_4px_5.ImageColor3 = Color3.fromRGB(30, 30, 30)
TextButton_Roundify_4px_5.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_4px_5.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_4px_5.SliceScale = 0.040

Button.Name = "Button"
Button.Parent = Topbar
Button.BackgroundTransparency = 1.000
Button.Position = UDim2.new(0.83436507, 0, 0.181864172, 0)
Button.Rotation = 180.000
Button.Size = UDim2.new(0, 20, 0, 20)
Button.ZIndex = 2
Button.Image = "rbxassetid://3926307971"
Button.ImageRectOffset = Vector2.new(324, 524)
Button.ImageRectSize = Vector2.new(36, 36)

-- Scripts:

	local script = Instance.new('LocalScript', Topbar)

	local UIS = game:GetService("UserInputService")
	function dragify(Frame)
	    dragToggle = nil
	    local dragSpeed = 0.50
	    dragInput = nil
	    dragStart = nil
	    local dragPos = nil
	    function updateInput(input)
	        local Delta = input.Position - dragStart
	        local Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + Delta.X, startPos.Y.Scale, startPos.Y.Offset + Delta.Y)
	        game:GetService("TweenService"):Create(Frame, TweenInfo.new(0.30), {Position = Position}):Play()
	    end
	    Frame.InputBegan:Connect(function(input)
	        if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) and UIS:GetFocusedTextBox() == nil then
	            dragToggle = true
	            dragStart = input.Position
	            startPos = Frame.Position
	            input.Changed:Connect(function()
	                if input.UserInputState == Enum.UserInputState.End then
	                    dragToggle = false
	                end
	            end)
	        end
	    end)
	    Frame.InputChanged:Connect(function(input)
	        if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
	            dragInput = input
	        end
	    end)
	    game:GetService("UserInputService").InputChanged:Connect(function(input)
	        if input == dragInput and dragToggle then
	            updateInput(input)
	        end
	    end)
	end
	
	dragify(script.Parent)

	local script = Instance.new('LocalScript', RadiantLuckyBlocks)

	Topbar = script.Parent.Topbar
	MainContainer = script.Parent.Topbar.MainContainer
	Button = script.Parent.Topbar.Button
	InfinityJump = script.Parent.Topbar.MainContainer.Container2.InfinityJump
	InfinityJumpOFF = script.Parent.Topbar.MainContainer.Container2.InfinityJump.ButtonOFF
	InfinityJumpON = script.Parent.Topbar.MainContainer.Container2.InfinityJump.ButtonON
	GetGear = script.Parent.Topbar.MainContainer.Container2.GetGear.GetGearButton
	FlyButton = script.Parent.Topbar.MainContainer.Container2.Fly.FlyButton
	TpTools = script.Parent.Topbar.MainContainer.Container2.TpTools.TpToolsButton
	WalkspeedSlider = script.Parent.Topbar.MainContainer.Container2.WalkspeedFrame.WalkSpeedSlider
	WalkspeedInner = script.Parent.Topbar.MainContainer.Container2.WalkspeedFrame.WalkSpeedSlider.WalkSpeedInner
	WalkspeedCount = script.Parent.Topbar.MainContainer.Container2.WalkspeedFrame.WalkSpeedSlider.WalkSpeedCount
	JumpPowerSlider = script.Parent.Topbar.MainContainer.Container2.JumpPowerFrame.JumpPowerSlider
	JumpPowerInner = script.Parent.Topbar.MainContainer.Container2.JumpPowerFrame.JumpPowerSlider.JumpPowerInner
	JumpPowerCount = script.Parent.Topbar.MainContainer.Container2.JumpPowerFrame.JumpPowerSlider.JumpPowerCount
	
	
	InfinityJumpOFF.MouseEnter:Connect(function()
		InfinityJumpOFF.ImageTransparency = 0.5
		wait(0.01)
		InfinityJumpOFF.ImageTransparency = 0.3
		wait(0.01)
		InfinityJumpOFF.ImageTransparency = 0
	end)
	
	InfinityJumpOFF.MouseLeave:Connect(function()
		InfinityJumpOFF.ImageTransparency = 0
		wait(0.01)
		InfinityJumpOFF.ImageTransparency = 0.3
		wait(0.01)
		InfinityJumpOFF.ImageTransparency = 0.5
		wait(0.01)
		InfinityJumpOFF.ImageTransparency = 1
	end)
	
	InfinityJumpON.MouseButton1Down:Connect(function()
		InfinityJumpOFF.Visible = true
		InfinityJumpON.Visible = false
		
		InfiniteJumpEnabled = false
		game:GetService("UserInputService").JumpRequest:connect(function()
			if InfiniteJumpEnabled then
				game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")
			end
		end)
	end)
	
	InfinityJumpOFF.MouseButton1Down:Connect(function()
		if InfinityJumpOFF.ImageTransparency == 0 then
			InfinityJumpOFF.Visible = false
			InfinityJumpON.Visible = true
			
			InfiniteJumpEnabled = true
			game:GetService("UserInputService").JumpRequest:connect(function()
				if InfiniteJumpEnabled then
					game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")
				end
			end)
		end
	end)
	
	Button.MouseButton1Down:Connect(function()
		if Button.Rotation == 180 then
			wait(0.025)
			Button.Rotation = 90
			wait(0.025)
			Button.Rotation = 60
			wait(0.025)
			MainContainer:TweenSize(UDim2.new(0, 163,0, 270), "Out", "Sine", 0.25)
			Button.Rotation = 30
			wait(0.025)
			Button.Rotation = 0
		elseif
			Button.Rotation == 0 then
			wait(0.025)
			Button.Rotation = 0
			wait(0.025)
			Button.Rotation = 30
			wait(0.025)
			MainContainer:TweenSize(UDim2.new(0, 163,0, 0), "Out", "Sine", 0.25)
			Button.Rotation = 60
			wait(0.025)
			Button.Rotation = 90
			wait(0.025)
			Button.Rotation = 180
		
		end
	end)
	
	local GetGearButtonImage = script.Parent.Topbar.MainContainer.Container2.GetGear.GetGearButton.TextButton_Roundify_4px
	
	local isHovering = false
	
	local tweenService = game:GetService("TweenService")
	local tweenInfo = TweenInfo.new(0.2, Enum.EasingStyle.Quint, Enum.EasingDirection.InOut)
	
	local colourDarkTween = tweenService:Create(GetGearButtonImage, tweenInfo, {ImageColor3 = Color3.fromRGB(10, 10, 10)})
	local colourBrightTween = tweenService:Create(GetGearButtonImage, tweenInfo, {ImageColor3 = Color3.fromRGB(55, 55, 55)})
	local colourDefaultTween = tweenService:Create(GetGearButtonImage, tweenInfo, {ImageColor3 = Color3.fromRGB(30, 30, 30)})
	
	
	GetGearButtonImage.MouseEnter:Connect(function()
	
		isHovering = true
	
		colourBrightTween:Play()
	end)
	
	GetGearButtonImage.MouseLeave:Connect(function()
	
		isHovering = false
	
		colourDefaultTween:Play()
	end)
	
	GetGear.MouseButton1Down:Connect(function()
	
		colourDarkTween:Play()
		
		x = 0
		while x <= 200 do
			x = x+1
			local Event = game:GetService("ReplicatedStorage").SpawnGalaxyBlock
			Event:FireServer()
			wait(0.5)
		end
		
	end)
	
	GetGear.MouseButton1Up:Connect(function()
	
		if not isHovering then
			colourDefaultTween:Play()
		else
			colourBrightTween:Play()
		end
	end)
	
	local FlyButtonImage = script.Parent.Topbar.MainContainer.Container2.Fly.FlyButton.TextButton_Roundify_4px
	
	local isHovering = false
	
	local tweenService = game:GetService("TweenService")
	local tweenInfo = TweenInfo.new(0.2, Enum.EasingStyle.Quint, Enum.EasingDirection.InOut)
	
	local colourDarkTween = tweenService:Create(FlyButtonImage, tweenInfo, {ImageColor3 = Color3.fromRGB(10, 10, 10)})
	local colourBrightTween = tweenService:Create(FlyButtonImage, tweenInfo, {ImageColor3 = Color3.fromRGB(55, 55, 55)})
	local colourDefaultTween = tweenService:Create(FlyButtonImage, tweenInfo, {ImageColor3 = Color3.fromRGB(30, 30, 30)})
	
	
	FlyButtonImage.MouseEnter:Connect(function()
	
		isHovering = true
	
		colourBrightTween:Play()
	end)
	
	FlyButtonImage.MouseLeave:Connect(function()
	
		isHovering = false
	
		colourDefaultTween:Play()
	end)
	
	FlyButton.MouseButton1Down:Connect(function()
	
		colourDarkTween:Play()
		
		repeat wait() until game.Players.LocalPlayer and game.Players.LocalPlayer.Character and game.Players.LocalPlayer.Character:findFirstChild("Torso") and game.Players.LocalPlayer.Character:findFirstChild("Humanoid")
		local mouse = game.Players.LocalPlayer:GetMouse()
		repeat wait() until mouse
		local plr = game.Players.LocalPlayer
		local torso = plr.Character.Torso
		local flying = true
		local deb = true
		local ctrl = {f = 0, b = 0, l = 0, r = 0}
		local lastctrl = {f = 0, b = 0, l = 0, r = 0}
		local maxspeed = 50
		local speed = 0
	
		function Fly()
			local bg = Instance.new("BodyGyro", torso)
			bg.P = 9e4
			bg.maxTorque = Vector3.new(9e9, 9e9, 9e9)
			bg.cframe = torso.CFrame
			local bv = Instance.new("BodyVelocity", torso)
			bv.velocity = Vector3.new(0,0.1,0)
			bv.maxForce = Vector3.new(9e9, 9e9, 9e9)
			repeat wait()
				if ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0 then
					speed = speed+.5+(speed/maxspeed)
					if speed > maxspeed then
						speed = maxspeed
					end
				elseif not (ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0) and speed ~= 0 then
					speed = speed-1
					if speed < 0 then
						speed = 0
					end
				end
				if (ctrl.l + ctrl.r) ~= 0 or (ctrl.f + ctrl.b) ~= 0 then
					bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (ctrl.f+ctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(ctrl.l+ctrl.r,(ctrl.f+ctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
					lastctrl = {f = ctrl.f, b = ctrl.b, l = ctrl.l, r = ctrl.r}
				elseif (ctrl.l + ctrl.r) == 0 and (ctrl.f + ctrl.b) == 0 and speed ~= 0 then
					bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (lastctrl.f+lastctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(lastctrl.l+lastctrl.r,(lastctrl.f+lastctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
				else
					bv.velocity = Vector3.new(0,0.1,0)
				end
				bg.cframe = game.Workspace.CurrentCamera.CoordinateFrame * CFrame.Angles(-math.rad((ctrl.f+ctrl.b)*50*speed/maxspeed),0,0)
			until not flying
			ctrl = {f = 0, b = 0, l = 0, r = 0}
			lastctrl = {f = 0, b = 0, l = 0, r = 0}
			speed = 0
			bg:Destroy()
			bv:Destroy()
		end
		mouse.KeyDown:connect(function(key)
			if key:lower() == "f" then
				if flying then flying = false
				else
					flying = true
					Fly()
				end
			elseif key:lower() == "w" then
				ctrl.f = 1
			elseif key:lower() == "s" then
				ctrl.b = -1
			elseif key:lower() == "a" then
				ctrl.l = -1
			elseif key:lower() == "d" then
				ctrl.r = 1
			end
		end)
		mouse.KeyUp:connect(function(key)
			if key:lower() == "w" then
				ctrl.f = 0
			elseif key:lower() == "s" then
				ctrl.b = 0
			elseif key:lower() == "a" then
				ctrl.l = 0
			elseif key:lower() == "d" then
				ctrl.r = 0
			end
		end)
		Fly()
		
	end)
	
	FlyButton.MouseButton1Up:Connect(function()
	
		if not isHovering then
			colourDefaultTween:Play()
		else
			colourBrightTween:Play()
		end
	end)
	
	local TpToolsButtonImage = script.Parent.Topbar.MainContainer.Container2.TpTools.TpToolsButton.TextButton_Roundify_4px
	
	local isHovering = false
	
	local tweenService = game:GetService("TweenService")
	local tweenInfo = TweenInfo.new(0.2, Enum.EasingStyle.Quint, Enum.EasingDirection.InOut)
	
	local colourDarkTween = tweenService:Create(TpToolsButtonImage, tweenInfo, {ImageColor3 = Color3.fromRGB(10, 10, 10)})
	local colourBrightTween = tweenService:Create(TpToolsButtonImage, tweenInfo, {ImageColor3 = Color3.fromRGB(55, 55, 55)})
	local colourDefaultTween = tweenService:Create(TpToolsButtonImage, tweenInfo, {ImageColor3 = Color3.fromRGB(30, 30, 30)})
	
	
	TpToolsButtonImage.MouseEnter:Connect(function()
	
		isHovering = true
	
		colourBrightTween:Play()
	end)
	
	TpToolsButtonImage.MouseLeave:Connect(function()
	
		isHovering = false
	
		colourDefaultTween:Play()
	end)
	
	TpTools.MouseButton1Down:Connect(function()
	
		colourDarkTween:Play()
		
		mouse = game.Players.LocalPlayer:GetMouse()
		tool = Instance.new("Tool")
		tool.RequiresHandle = false
		tool.Name = "Radiant TP"
		tool.Activated:connect(function()
			local pos = mouse.Hit+Vector3.new(0,2.5,0)
			pos = CFrame.new(pos.X,pos.Y,pos.Z)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = pos
		end)
		tool.Parent = game.Players.LocalPlayer.Backpack
		
	end)
	
	TpTools.MouseButton1Up:Connect(function()
	
		if not isHovering then
			colourDefaultTween:Play()
		else
			colourBrightTween:Play()
		end
	end)
	
	--- WalkSpeed Slide ---
	
	min2value = min2value or 16
	max2value = max2value or 50
	
	callback = callback or function() end
	
	local mouse = game.Players.LocalPlayer:GetMouse()
	local uis = game:GetService("UserInputService")
	local Value;
	
	WalkspeedSlider.MouseButton1Down:Connect(function()
		Value = math.floor((((tonumber(max2value) - tonumber(min2value)) / 141) * WalkspeedInner.AbsoluteSize.X) + tonumber(min2value)) or 0
		pcall(function()
			callback(Value)
		end)
		WalkspeedInner.Size = UDim2.new(0, math.clamp(mouse.X - WalkspeedInner.AbsolutePosition.X, 0, 141), 0, 5)
		moveconnection = mouse.Move:Connect(function()
			WalkspeedCount.Text = Value
			Value = math.floor((((tonumber(max2value) - tonumber(min2value)) / 141) * WalkspeedInner.AbsoluteSize.X) + tonumber(min2value))
			pcall(function()
				callback(Value)
			end)
			WalkspeedInner.Size = UDim2.new(0, math.clamp(mouse.X - WalkspeedInner.AbsolutePosition.X, 0, 141), 0, 5)
		end)
		releaseconnection = uis.InputEnded:Connect(function(Mouse)
			if Mouse.UserInputType == Enum.UserInputType.MouseButton1 then
				Value = math.floor((((tonumber(max2value) - tonumber(min2value)) / 141) * WalkspeedInner.AbsoluteSize.X) + tonumber(min2value))
				pcall(function()
					callback(Value)
				end)
				WalkspeedInner.Size = UDim2.new(0, math.clamp(mouse.X - WalkspeedInner.AbsolutePosition.X, 0, 141), 0, 5)
				moveconnection:Disconnect()
				releaseconnection:Disconnect()
				game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = Value
			end
		end)
	end)
	
	--- WalkSpeed Slide ---
	
	--- JumpPower Slide ---
	
	minvalue = minvalue or 50
	maxvalue = maxvalue or 100
	
	callback = callback or function() end
	
	local mouse = game.Players.LocalPlayer:GetMouse()
	local uis = game:GetService("UserInputService")
	local Value;
	
	JumpPowerSlider.MouseButton1Down:Connect(function()
		Value = math.floor((((tonumber(maxvalue) - tonumber(minvalue)) / 141) * JumpPowerInner.AbsoluteSize.X) + tonumber(minvalue)) or 0
		pcall(function()
			callback(Value)
		end)
		JumpPowerInner.Size = UDim2.new(0, math.clamp(mouse.X - JumpPowerInner.AbsolutePosition.X, 0, 141), 0, 5)
		moveconnection = mouse.Move:Connect(function()
			JumpPowerCount.Text = Value
			Value = math.floor((((tonumber(maxvalue) - tonumber(minvalue)) / 141) * JumpPowerInner.AbsoluteSize.X) + tonumber(minvalue))
			pcall(function()
				callback(Value)
			end)
			JumpPowerInner.Size = UDim2.new(0, math.clamp(mouse.X - JumpPowerInner.AbsolutePosition.X, 0, 141), 0, 5)
		end)
		releaseconnection = uis.InputEnded:Connect(function(Mouse)
			if Mouse.UserInputType == Enum.UserInputType.MouseButton1 then
				Value = math.floor((((tonumber(maxvalue) - tonumber(minvalue)) / 141) * JumpPowerInner.AbsoluteSize.X) + tonumber(minvalue))
				pcall(function()
					callback(Value)
				end)
				JumpPowerInner.Size = UDim2.new(0, math.clamp(mouse.X - JumpPowerInner.AbsolutePosition.X, 0, 141), 0, 5)
				moveconnection:Disconnect()
				releaseconnection:Disconnect()
				game.Players.LocalPlayer.Character.Humanoid.JumpPower = Value
			end
		end)
	end)
	
	--- JumpPower Slide ---
