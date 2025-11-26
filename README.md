--[=[
 d888b  db    db d888888b      .d888b.      db      db    db  .d8b.  
88' Y8b 88    88   `88'        VP  `8D      88      88    88 d8' `8b 
88      88    88    88            odD'      88      88    88 88ooo88 
88  ooo 88    88    88          .88'        88      88    88 88~~~88 
88. ~8~ 88b  d88   .88.        j88.         88booo. 88b  d88 88   88    @uniquadev
 Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER 
]=]

-- Instances: 43 | Scripts: 7 | Modules: 0 | Tags: 0
local G2L = {};

-- StarterGui.ScreenGui
G2L["1"] = Instance.new("ScreenGui", game:GetService("Players").LocalPlayer:WaitForChild("PlayerGui"));
G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;


-- StarterGui.ScreenGui.Frame
G2L["2"] = Instance.new("Frame", G2L["1"]);
G2L["2"]["BorderSizePixel"] = 0;
G2L["2"]["BackgroundColor3"] = Color3.fromRGB(43, 43, 43);
G2L["2"]["Size"] = UDim2.new(0, 450, 0, 291);
G2L["2"]["Position"] = UDim2.new(0.19877, 0, 0.39263, 0);
G2L["2"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2"]["BackgroundTransparency"] = 0.3;


-- StarterGui.ScreenGui.Frame.UIDrag
G2L["3"] = Instance.new("LocalScript", G2L["2"]);
G2L["3"]["Name"] = [[UIDrag]];


-- StarterGui.ScreenGui.Frame.TextBox
G2L["4"] = Instance.new("TextBox", G2L["2"]);
G2L["4"]["ZIndex"] = 2;
G2L["4"]["BorderSizePixel"] = 0;
G2L["4"]["TextSize"] = 14;
G2L["4"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["4"]["BackgroundColor3"] = Color3.fromRGB(30, 30, 30);
G2L["4"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["4"]["Size"] = UDim2.new(0, 357, 0, 35);
G2L["4"]["Position"] = UDim2.new(0.04889, 0, 0.14089, 0);
G2L["4"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4"]["Text"] = [[]];
G2L["4"]["BackgroundTransparency"] = 0.55;


-- StarterGui.ScreenGui.Frame.TextBox.UICorner
G2L["5"] = Instance.new("UICorner", G2L["4"]);
G2L["5"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.Frame.TextBox.UIStroke
G2L["6"] = Instance.new("UIStroke", G2L["4"]);
G2L["6"]["Transparency"] = 0.38;
G2L["6"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["6"]["Thickness"] = 1.8;
G2L["6"]["Color"] = Color3.fromRGB(158, 158, 158);


-- StarterGui.ScreenGui.Frame.TextBox.UIStroke.UIGradient
G2L["7"] = Instance.new("UIGradient", G2L["6"]);
G2L["7"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(0.501, 1),NumberSequenceKeypoint.new(1.000, 0)};


-- StarterGui.ScreenGui.Frame.TextBox.UIStroke.UIGradient.LocalScript
G2L["8"] = Instance.new("LocalScript", G2L["7"]);



-- StarterGui.ScreenGui.Frame.TextLabel
G2L["9"] = Instance.new("TextLabel", G2L["2"]);
G2L["9"]["ZIndex"] = 2;
G2L["9"]["BorderSizePixel"] = 0;
G2L["9"]["TextSize"] = 26;
G2L["9"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["9"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9"]["BackgroundTransparency"] = 1;
G2L["9"]["Size"] = UDim2.new(0, 450, 0, 33);
G2L["9"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["9"]["Text"] = [[ElysianHub]];
G2L["9"]["Position"] = UDim2.new(-0, 0, 0, 0);


-- StarterGui.ScreenGui.Frame.ImageButton
G2L["a"] = Instance.new("ImageButton", G2L["2"]);
G2L["a"]["BorderSizePixel"] = 0;
G2L["a"]["BackgroundTransparency"] = 1;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["a"]["BackgroundColor3"] = Color3.fromRGB(30, 30, 30);
G2L["a"]["ZIndex"] = 2;
G2L["a"]["Image"] = [[rbxassetid://91602091407806]];
G2L["a"]["Size"] = UDim2.new(0, 34, 0, 44);
G2L["a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a"]["Position"] = UDim2.new(0.87556, 0, 0.14433, 0);


-- StarterGui.ScreenGui.Frame.ImageButton.UIAspectRatioConstraint
G2L["b"] = Instance.new("UIAspectRatioConstraint", G2L["a"]);



-- StarterGui.ScreenGui.Frame.Normal
G2L["c"] = Instance.new("TextButton", G2L["2"]);
G2L["c"]["BorderSizePixel"] = 0;
G2L["c"]["TextSize"] = 14;
G2L["c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c"]["BackgroundColor3"] = Color3.fromRGB(67, 67, 67);
G2L["c"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["c"]["ZIndex"] = 2;
G2L["c"]["Size"] = UDim2.new(0, 60, 0.02, 16);
G2L["c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["c"]["Text"] = [[NormalCore]];
G2L["c"]["Name"] = [[Normal]];
G2L["c"]["Position"] = UDim2.new(0.04766, 0, 0.03499, 0);


-- StarterGui.ScreenGui.Frame.Normal.UICorner
G2L["d"] = Instance.new("UICorner", G2L["c"]);
G2L["d"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.Frame.Normal.UIStroke
G2L["e"] = Instance.new("UIStroke", G2L["c"]);
G2L["e"]["Transparency"] = 0.38;
G2L["e"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["e"]["Thickness"] = 1.8;
G2L["e"]["Color"] = Color3.fromRGB(158, 158, 158);


-- StarterGui.ScreenGui.Frame.Normal.UIStroke.UIGradient
G2L["f"] = Instance.new("UIGradient", G2L["e"]);
G2L["f"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(0.501, 1),NumberSequenceKeypoint.new(1.000, 0)};


-- StarterGui.ScreenGui.Frame.Normal.UIStroke.UIGradient.LocalScript
G2L["10"] = Instance.new("LocalScript", G2L["f"]);



-- StarterGui.ScreenGui.Frame.ScrollingFrame
G2L["11"] = Instance.new("ScrollingFrame", G2L["2"]);
G2L["11"]["Active"] = true;
G2L["11"]["ZIndex"] = 2;
G2L["11"]["BorderSizePixel"] = 0;
G2L["11"]["CanvasSize"] = UDim2.new(0, 0, 10, 0);
G2L["11"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["11"]["Size"] = UDim2.new(0, 406, 0, 160);
G2L["11"]["ScrollBarImageColor3"] = Color3.fromRGB(0, 0, 0);
G2L["11"]["Position"] = UDim2.new(0.04889, 0, 0.32646, 0);
G2L["11"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["11"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Frame.ScrollingFrame.UIListLayout
G2L["12"] = Instance.new("UIListLayout", G2L["11"]);
G2L["12"]["Padding"] = UDim.new(0, 10);
G2L["12"]["SortOrder"] = Enum.SortOrder.LayoutOrder;


-- StarterGui.ScreenGui.Frame.ScrollingFrame.Example
G2L["13"] = Instance.new("Frame", G2L["11"]);
G2L["13"]["ZIndex"] = 2;
G2L["13"]["BorderSizePixel"] = 0;
G2L["13"]["BackgroundColor3"] = Color3.fromRGB(91, 91, 91);
G2L["13"]["Size"] = UDim2.new(0, 392, 0, 45);
G2L["13"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["13"]["Name"] = [[Example]];
G2L["13"]["BackgroundTransparency"] = 0.45;


-- StarterGui.ScreenGui.Frame.ScrollingFrame.Example.TextLabel
G2L["14"] = Instance.new("TextLabel", G2L["13"]);
G2L["14"]["TextWrapped"] = true;
G2L["14"]["ZIndex"] = 2;
G2L["14"]["BorderSizePixel"] = 0;
G2L["14"]["TextSize"] = 20;
G2L["14"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["14"]["TextScaled"] = true;
G2L["14"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["14"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["14"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["14"]["BackgroundTransparency"] = 1;
G2L["14"]["Size"] = UDim2.new(-0.05745, 210, 0.07705, 30);
G2L["14"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["14"]["Text"] = [[Example name]];
G2L["14"]["Position"] = UDim2.new(0.11949, 0, 0.11527, 0);


-- StarterGui.ScreenGui.Frame.ScrollingFrame.Example.ImageLabel
G2L["15"] = Instance.new("ImageLabel", G2L["13"]);
G2L["15"]["ZIndex"] = 2;
G2L["15"]["BorderSizePixel"] = 0;
G2L["15"]["BackgroundColor3"] = Color3.fromRGB(27, 27, 27);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["15"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["15"]["Image"] = [[rbxassetid://104649966280536]];
G2L["15"]["Size"] = UDim2.new(0, 41, 0, 35);
G2L["15"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["15"]["BackgroundTransparency"] = 1;
G2L["15"]["Position"] = UDim2.new(0.06, 0, 0.5, 0);


-- StarterGui.ScreenGui.Frame.ScrollingFrame.Example.ImageLabel.UICorner
G2L["16"] = Instance.new("UICorner", G2L["15"]);
G2L["16"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.Frame.ScrollingFrame.Example.ImageLabel.UIAspectRatioConstraint
G2L["17"] = Instance.new("UIAspectRatioConstraint", G2L["15"]);



-- StarterGui.ScreenGui.Frame.ScrollingFrame.Example.UICorner
G2L["18"] = Instance.new("UICorner", G2L["13"]);
G2L["18"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.Frame.ScrollingFrame.Example.TextButton
G2L["19"] = Instance.new("TextButton", G2L["13"]);
G2L["19"]["BorderSizePixel"] = 0;
G2L["19"]["TextSize"] = 14;
G2L["19"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["19"]["BackgroundColor3"] = Color3.fromRGB(67, 67, 67);
G2L["19"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["19"]["ZIndex"] = 2;
G2L["19"]["Size"] = UDim2.new(0, 87, 0, 29);
G2L["19"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["19"]["Text"] = [[Run]];
G2L["19"]["Position"] = UDim2.new(0.75655, 0, 0.15121, 0);


-- StarterGui.ScreenGui.Frame.ScrollingFrame.Example.TextButton.UICorner
G2L["1a"] = Instance.new("UICorner", G2L["19"]);
G2L["1a"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.Frame.ScrollingFrame.UICorner
G2L["1b"] = Instance.new("UICorner", G2L["11"]);
G2L["1b"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.Frame.UICorner
G2L["1c"] = Instance.new("UICorner", G2L["2"]);
G2L["1c"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.Frame.UIStroke
G2L["1d"] = Instance.new("UIStroke", G2L["2"]);
G2L["1d"]["Transparency"] = 0.38;
G2L["1d"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["1d"]["Thickness"] = 1.8;
G2L["1d"]["Color"] = Color3.fromRGB(158, 158, 158);


-- StarterGui.ScreenGui.Frame.UIStroke.UIGradient
G2L["1e"] = Instance.new("UIGradient", G2L["1d"]);
G2L["1e"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(0.501, 1),NumberSequenceKeypoint.new(1.000, 0)};


-- StarterGui.ScreenGui.Frame.UIStroke.UIGradient.LocalScript
G2L["1f"] = Instance.new("LocalScript", G2L["1e"]);



-- StarterGui.ScreenGui.Frame.CuteCore
G2L["20"] = Instance.new("TextButton", G2L["2"]);
G2L["20"]["BorderSizePixel"] = 0;
G2L["20"]["TextSize"] = 14;
G2L["20"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["20"]["BackgroundColor3"] = Color3.fromRGB(67, 67, 67);
G2L["20"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["20"]["ZIndex"] = 2;
G2L["20"]["Size"] = UDim2.new(0, 60, 0.02, 16);
G2L["20"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["20"]["Text"] = [[CuteCore]];
G2L["20"]["Name"] = [[CuteCore]];
G2L["20"]["Position"] = UDim2.new(0.19766, 0, 0.03499, 0);


-- StarterGui.ScreenGui.Frame.CuteCore.UICorner
G2L["21"] = Instance.new("UICorner", G2L["20"]);
G2L["21"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.Frame.CuteCore.UIStroke
G2L["22"] = Instance.new("UIStroke", G2L["20"]);
G2L["22"]["Transparency"] = 0.38;
G2L["22"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["22"]["Thickness"] = 1.8;
G2L["22"]["Color"] = Color3.fromRGB(158, 158, 158);


-- StarterGui.ScreenGui.Frame.CuteCore.UIStroke.UIGradient
G2L["23"] = Instance.new("UIGradient", G2L["22"]);
G2L["23"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(0.501, 1),NumberSequenceKeypoint.new(1.000, 0)};


-- StarterGui.ScreenGui.Frame.CuteCore.UIStroke.UIGradient.LocalScript
G2L["24"] = Instance.new("LocalScript", G2L["23"]);



-- StarterGui.ScreenGui.Frame.LocalScript
G2L["25"] = Instance.new("LocalScript", G2L["2"]);



-- StarterGui.ScreenGui.Frame.LocalScript
G2L["26"] = Instance.new("LocalScript", G2L["2"]);



-- StarterGui.ScreenGui.Frame.ann
G2L["27"] = Instance.new("ImageLabel", G2L["2"]);
G2L["27"]["BorderSizePixel"] = 0;
G2L["27"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["27"]["ImageTransparency"] = 0.75;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["27"]["Image"] = [[rbxassetid://1878425826]];
G2L["27"]["Size"] = UDim2.new(0, 450, 0, 291);
G2L["27"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["27"]["BackgroundTransparency"] = 1;
G2L["27"]["Name"] = [[ann]];


-- StarterGui.ScreenGui.Frame.ann.UICorner
G2L["28"] = Instance.new("UICorner", G2L["27"]);
G2L["28"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.Frame.super
G2L["29"] = Instance.new("ImageLabel", G2L["2"]);
G2L["29"]["BorderSizePixel"] = 0;
G2L["29"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["29"]["ImageTransparency"] = 0.39;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["29"]["Image"] = [[rbxassetid://10286206897]];
G2L["29"]["Size"] = UDim2.new(0, 450, 0, 291);
G2L["29"]["Visible"] = false;
G2L["29"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["29"]["BackgroundTransparency"] = 1;
G2L["29"]["Name"] = [[super]];


-- StarterGui.ScreenGui.Frame.super.UICorner
G2L["2a"] = Instance.new("UICorner", G2L["29"]);
G2L["2a"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.Frame.TextLabel
G2L["2b"] = Instance.new("TextLabel", G2L["2"]);
G2L["2b"]["ZIndex"] = 2;
G2L["2b"]["BorderSizePixel"] = 0;
G2L["2b"]["TextSize"] = 13;
G2L["2b"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["2b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["2b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2b"]["BackgroundTransparency"] = 1;
G2L["2b"]["Size"] = UDim2.new(0, 108, 0, 25);
G2L["2b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2b"]["Text"] = [[by OutMoon and DreamyDolan2]];
G2L["2b"]["Position"] = UDim2.new(0.04889, 0, 0.89003, 0);


-- StarterGui.ScreenGui.Frame.UIDrag
local function C_3()
local script = G2L["3"];
	-- Made by Real_IceyDev (@lceyDex) --
	-- Simple UI dragger (PC Only/Any device that has a mouse) --
	
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
end;
task.spawn(C_3);
-- StarterGui.ScreenGui.Frame.TextBox.UIStroke.UIGradient.LocalScript
local function C_8()
local script = G2L["8"];
	local speed = 5
	
	while true do
		wait(0.05)
		script.Parent.Rotation += speed
	end
end;
task.spawn(C_8);
-- StarterGui.ScreenGui.Frame.Normal.UIStroke.UIGradient.LocalScript
local function C_10()
local script = G2L["10"];
	local speed = 5
	
	while true do
		wait(0.05)
		script.Parent.Rotation += speed
	end
end;
task.spawn(C_10);
-- StarterGui.ScreenGui.Frame.UIStroke.UIGradient.LocalScript
local function C_1f()
local script = G2L["1f"];
	local speed = 5
	
	while true do
		wait(0.05)
		script.Parent.Rotation += speed
	end
end;
task.spawn(C_1f);
-- StarterGui.ScreenGui.Frame.CuteCore.UIStroke.UIGradient.LocalScript
local function C_24()
local script = G2L["24"];
	local speed = 5
	
	while true do
		wait(0.05)
		script.Parent.Rotation += speed
	end
end;
task.spawn(C_24);
-- StarterGui.ScreenGui.Frame.LocalScript
local function C_25()
local script = G2L["25"];
	local TweenService = game:GetService("TweenService")
	local cutecore = script.Parent.CuteCore
	local normal = script.Parent.Normal
	local parentFrame = script.Parent
	local ann = script.Parent.ann
	local super = script.Parent.super
	
	
	local originalColors = {}
	local originalStrokeColors = {}
	
	
	local pinks = {
	    TextBox = Color3.fromRGB(255, 21, 255), 
	    TextLabel = Color3.fromRGB(255, 255, 255), 
	    Frame = Color3.fromRGB(228, 73, 255), 
	    TextButton = Color3.fromRGB(255, 11, 251),
	    UIStroke = Color3.fromRGB(151, 0, 162) 
	}
	
	
	local function tweenColor(guiObj, targetColor)
	    if guiObj.BackgroundColor3 then
	        local tweenInfo = TweenInfo.new(0.5, Enum.EasingStyle.Quad, Enum.EasingDirection.Out)
	        local propertyTable = {BackgroundColor3 = targetColor}
	        local tween = TweenService:Create(guiObj, tweenInfo, propertyTable)
	        tween:Play()
	    end
	end
	
	
	local function tweenStrokeColor(strokeObj, targetColor)
	    if strokeObj:IsA("UIStroke") then
	        local tweenInfo = TweenInfo.new(0.5, Enum.EasingStyle.Quad, Enum.EasingDirection.Out)
	        local propertyTable = {Color = targetColor}
	        local tween = TweenService:Create(strokeObj, tweenInfo, propertyTable)
	        tween:Play()
	    end
	end
	
	local function getAllGuiObjectsAndStrokes(obj)
	    local guiObjects = {}
	    local strokeObjects = {}
	    if obj:IsA("TextBox") or obj:IsA("TextLabel") or obj:IsA("Frame") or obj:IsA("TextButton") then
	        table.insert(guiObjects, obj)
	    end
	    if obj:IsA("UIStroke") then
	        table.insert(strokeObjects, obj)
	    end
	    for _, child in obj:GetChildren() do
	        local childGuiObjs, childStrokeObjs = getAllGuiObjectsAndStrokes(child)
	        for _, c in childGuiObjs do
	            table.insert(guiObjects, c)
	        end
	        for _, s in childStrokeObjs do
	            table.insert(strokeObjects, s)
	        end
	    end
	    return guiObjects, strokeObjects
	end
	
	
	local function saveOriginalColors()
	    originalColors = {}
	    originalStrokeColors = {}
	    local guiObjects, strokeObjects = getAllGuiObjectsAndStrokes(parentFrame)
	    for _, guiObj in guiObjects do
	        originalColors[guiObj] = guiObj.BackgroundColor3
	    end
	    for _, strokeObj in strokeObjects do
	        originalStrokeColors[strokeObj] = strokeObj.Color
	    end
	end
	
	
	local function applyPinkTheme()
	    local guiObjects, strokeObjects = getAllGuiObjectsAndStrokes(parentFrame)
	    for _, guiObj in guiObjects do
	        if guiObj:IsA("TextBox") then
	            tweenColor(guiObj, pinks.TextBox)
	        elseif guiObj:IsA("TextLabel") then
	            tweenColor(guiObj, pinks.TextLabel)
	        elseif guiObj:IsA("Frame") then
	            tweenColor(guiObj, pinks.Frame)
	        elseif guiObj:IsA("TextButton") then
	            tweenColor(guiObj, pinks.TextButton)
	        end
	    end
	    for _, strokeObj in strokeObjects do
	        tweenStrokeColor(strokeObj, pinks.UIStroke)
	    end
	end
	
	
	local function restoreColors()
	    for guiObj, color in originalColors do
	        tweenColor(guiObj, color)
	    end
	    for strokeObj, color in originalStrokeColors do
	        tweenStrokeColor(strokeObj, color)
	    end
	end
	
	
	saveOriginalColors()
	
	cutecore.MouseButton1Click:Connect(function()
		applyPinkTheme()
		super.Visible = true
		ann.Visible = false
	end)
	
	normal.MouseButton1Click:Connect(function()
		super.Visible = false
		ann.Visible = true
		restoreColors()
	end)
	
	
end;
task.spawn(C_25);
-- StarterGui.ScreenGui.Frame.LocalScript
local function C_26()
local script = G2L["26"];
	local Example = script.Parent.ScrollingFrame:FindFirstChild("Example")
	local Searchbtn = script.Parent:FindFirstChild("ImageButton")
	local search = script.Parent:FindFirstChild("TextBox")
	
	local HttpService = game:GetService("HttpService")
	
	if Example then
	    Example.Visible = false
	end
	
	local function clearResults()
	    local scrollingFrame = script.Parent.ScrollingFrame
	    local children = scrollingFrame:GetChildren()
	    for i = #children, 1, -1 do
	        local child = children[i]
	        if child.Name == "Example" and child ~= Example then
	            child:Destroy()
	        end
	    end
	end
	
	local function SearchScripts(txt)
	    clearResults()
	    local ok, response = pcall(function()
	        return game:HttpGet("https://scriptblox.com/api/script/search?q="..txt.."&page=1&max=1000")
	    end)
	    if not ok then return end
	
	    local data = HttpService:JSONDecode(response)
	    if not data.result or not data.result.scripts or #data.result.scripts == 0 then
	        -- Show "No results found" message
	        if Example then
	            local noResult = Example:Clone()
	            noResult.Parent = script.Parent.ScrollingFrame
	            noResult.Visible = true
	            if noResult:FindFirstChild("TextLabel") then
	                noResult.TextLabel.Text = "No results found."
	            end
	            if noResult:FindFirstChild("TextButton") then
	                noResult.TextButton.Visible = false
	            end
	            noResult.Size = UDim2.new(1,-10,0,40)
	        end
	        return
	    end
	
	    for i = 1, #data.result.scripts do
	        local info = data.result.scripts[i]
	        if Example then
	            local holder = Example:Clone()
	            holder.Parent = script.Parent.ScrollingFrame
	            holder.Visible = true
	            holder.Size = UDim2.new(1,-10,0,40)
	            if holder:FindFirstChild("TextLabel") then
	                holder.TextLabel.Text = info.title or "No Title"
	            end
	            if holder:FindFirstChild("TextButton") then
	                holder.TextButton.Visible = true
	                holder.TextButton.MouseButton1Click:Connect(function()
	                    pcall(function()
							loadstring(info.script)()
	                    end)
	                end)
	            end
	            if holder:FindFirstChild("ImageLabel") then
	                if info.icon and tostring(info.icon) ~= "" then
	                    holder.ImageLabel.Image = "rbxassetid://"..tostring(info.icon)
	                else
						holder.ImageLabel.Image = "rbxassetid://104649966280536"
	                end
	            end
	        end
	    end
	end
	
	if Searchbtn then
	    Searchbtn.MouseButton1Click:Connect(function()
	        if search and search.Text ~= "" then
	            SearchScripts(search.Text)
	        end
	    end)
	end
	
	
	if search then
	    search.FocusLost:Connect(function(enterPressed)
	        if enterPressed and search.Text ~= "" then
	            SearchScripts(search.Text)
	        end
	    end)
	end
	
	
end;
task.spawn(C_26);

return G2L["1"], require;
