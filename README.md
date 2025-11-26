--[=[
 d888b  db    db d888888b      .d888b.      db      db    db  .d8b.  
88' Y8b 88    88   `88'        VP  `8D      88      88    88 d8' `8b 
88      88    88    88            odD'      88      88    88 88ooo88 
88  ooo 88    88    88          .88'        88      88    88 88~~~88 
88. ~8~ 88b  d88   .88.        j88.         88booo. 88b  d88 88   88    @uniquadev
 Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER 
]=]

-- Instances: 47 | Scripts: 9 | Modules: 1 | Tags: 0
local G2L = {};

-- StarterGui.ScreenGui
G2L["1"] = Instance.new("ScreenGui", game.CoreGui);
G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;


-- StarterGui.ScreenGui.SuperDuber
G2L["2"] = Instance.new("Frame", G2L["1"]);
G2L["2"]["BorderSizePixel"] = 0;
G2L["2"]["BackgroundColor3"] = Color3.fromRGB(43, 43, 43);
G2L["2"]["Size"] = UDim2.new(0, 450, 0, 291);
G2L["2"]["Position"] = UDim2.new(0.19877, 0, 0.39263, 0);
G2L["2"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2"]["Name"] = [[SuperDuber]];
G2L["2"]["BackgroundTransparency"] = 0.3;


-- StarterGui.ScreenGui.SuperDuber.UIDrag
G2L["3"] = Instance.new("LocalScript", G2L["2"]);
G2L["3"]["Name"] = [[UIDrag]];


-- StarterGui.ScreenGui.SuperDuber.LocalScript
G2L["4"] = Instance.new("LocalScript", G2L["2"]);



-- StarterGui.ScreenGui.SuperDuber.LocalScript
G2L["5"] = Instance.new("LocalScript", G2L["2"]);



-- StarterGui.ScreenGui.SuperDuber.TextBox
G2L["6"] = Instance.new("TextBox", G2L["2"]);
G2L["6"]["ZIndex"] = 2;
G2L["6"]["BorderSizePixel"] = 0;
G2L["6"]["TextSize"] = 14;
G2L["6"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6"]["BackgroundColor3"] = Color3.fromRGB(30, 30, 30);
G2L["6"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["6"]["Size"] = UDim2.new(0, 357, 0, 35);
G2L["6"]["Position"] = UDim2.new(0.04889, 0, 0.14089, 0);
G2L["6"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6"]["Text"] = [[]];
G2L["6"]["BackgroundTransparency"] = 0.55;


-- StarterGui.ScreenGui.SuperDuber.TextBox.UICorner
G2L["7"] = Instance.new("UICorner", G2L["6"]);
G2L["7"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.SuperDuber.TextBox.UIStroke
G2L["8"] = Instance.new("UIStroke", G2L["6"]);
G2L["8"]["Transparency"] = 0.38;
G2L["8"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["8"]["Thickness"] = 1.8;
G2L["8"]["Color"] = Color3.fromRGB(158, 158, 158);


-- StarterGui.ScreenGui.SuperDuber.TextBox.UIStroke.UIGradient
G2L["9"] = Instance.new("UIGradient", G2L["8"]);
G2L["9"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(0.501, 1),NumberSequenceKeypoint.new(1.000, 0)};


-- StarterGui.ScreenGui.SuperDuber.TextBox.UIStroke.UIGradient.LocalScript
G2L["a"] = Instance.new("LocalScript", G2L["9"]);



-- StarterGui.ScreenGui.SuperDuber.TextLabel
G2L["b"] = Instance.new("TextLabel", G2L["2"]);
G2L["b"]["ZIndex"] = 2;
G2L["b"]["BorderSizePixel"] = 0;
G2L["b"]["TextSize"] = 26;
G2L["b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["b"]["BackgroundTransparency"] = 1;
G2L["b"]["Size"] = UDim2.new(0, 450, 0, 33);
G2L["b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["b"]["Text"] = [[ElysianHub v2]];
G2L["b"]["Position"] = UDim2.new(-0, 0, 0, 0);


-- StarterGui.ScreenGui.SuperDuber.ImageButton
G2L["c"] = Instance.new("ImageButton", G2L["2"]);
G2L["c"]["BorderSizePixel"] = 0;
G2L["c"]["BackgroundTransparency"] = 1;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["c"]["BackgroundColor3"] = Color3.fromRGB(30, 30, 30);
G2L["c"]["ZIndex"] = 2;
G2L["c"]["Image"] = [[rbxassetid://91602091407806]];
G2L["c"]["Size"] = UDim2.new(0, 34, 0, 44);
G2L["c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["c"]["Position"] = UDim2.new(0.87556, 0, 0.14433, 0);


-- StarterGui.ScreenGui.SuperDuber.ImageButton.UIAspectRatioConstraint
G2L["d"] = Instance.new("UIAspectRatioConstraint", G2L["c"]);



-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame
G2L["e"] = Instance.new("ScrollingFrame", G2L["2"]);
G2L["e"]["Active"] = true;
G2L["e"]["ZIndex"] = 2;
G2L["e"]["BorderSizePixel"] = 0;
G2L["e"]["CanvasSize"] = UDim2.new(0, 0, 10, 0);
G2L["e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["e"]["Size"] = UDim2.new(0, 406, 0, 160);
G2L["e"]["ScrollBarImageColor3"] = Color3.fromRGB(0, 0, 0);
G2L["e"]["Position"] = UDim2.new(0.04889, 0, 0.32646, 0);
G2L["e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["e"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.UIListLayout
G2L["f"] = Instance.new("UIListLayout", G2L["e"]);
G2L["f"]["Padding"] = UDim.new(0, 10);
G2L["f"]["SortOrder"] = Enum.SortOrder.LayoutOrder;


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example
G2L["10"] = Instance.new("Frame", G2L["e"]);
G2L["10"]["ZIndex"] = 2;
G2L["10"]["BorderSizePixel"] = 0;
G2L["10"]["BackgroundColor3"] = Color3.fromRGB(91, 91, 91);
G2L["10"]["Size"] = UDim2.new(0, 392, 0, 45);
G2L["10"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["10"]["Name"] = [[Example]];
G2L["10"]["BackgroundTransparency"] = 0.45;


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.TextLabel
G2L["11"] = Instance.new("TextLabel", G2L["10"]);
G2L["11"]["TextWrapped"] = true;
G2L["11"]["ZIndex"] = 2;
G2L["11"]["BorderSizePixel"] = 0;
G2L["11"]["TextSize"] = 20;
G2L["11"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["11"]["TextScaled"] = true;
G2L["11"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["11"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["11"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["11"]["BackgroundTransparency"] = 1;
G2L["11"]["Size"] = UDim2.new(-0.05745, 210, 0.07705, 30);
G2L["11"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["11"]["Text"] = [[Example name]];
G2L["11"]["Position"] = UDim2.new(0.11949, 0, 0.11527, 0);


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.ImageLabel
G2L["12"] = Instance.new("ImageLabel", G2L["10"]);
G2L["12"]["ZIndex"] = 2;
G2L["12"]["BorderSizePixel"] = 0;
G2L["12"]["BackgroundColor3"] = Color3.fromRGB(27, 27, 27);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["12"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["12"]["Image"] = [[rbxassetid://104649966280536]];
G2L["12"]["Size"] = UDim2.new(0, 41, 0, 35);
G2L["12"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["12"]["BackgroundTransparency"] = 1;
G2L["12"]["Position"] = UDim2.new(0.06, 0, 0.5, 0);


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.ImageLabel.UICorner
G2L["13"] = Instance.new("UICorner", G2L["12"]);
G2L["13"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.ImageLabel.UIAspectRatioConstraint
G2L["14"] = Instance.new("UIAspectRatioConstraint", G2L["12"]);



-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.UICorner
G2L["15"] = Instance.new("UICorner", G2L["10"]);
G2L["15"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.TextButton
G2L["16"] = Instance.new("TextButton", G2L["10"]);
G2L["16"]["BorderSizePixel"] = 0;
G2L["16"]["TextSize"] = 14;
G2L["16"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["16"]["BackgroundColor3"] = Color3.fromRGB(67, 67, 67);
G2L["16"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["16"]["ZIndex"] = 2;
G2L["16"]["Size"] = UDim2.new(0, 87, 0, 29);
G2L["16"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["16"]["Text"] = [[Run]];
G2L["16"]["Position"] = UDim2.new(0.75655, 0, 0.15121, 0);


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.TextButton.UICorner
G2L["17"] = Instance.new("UICorner", G2L["16"]);
G2L["17"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.UICorner
G2L["18"] = Instance.new("UICorner", G2L["e"]);
G2L["18"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.SuperDuber.UICorner
G2L["19"] = Instance.new("UICorner", G2L["2"]);
G2L["19"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.SuperDuber.Normal
G2L["1a"] = Instance.new("TextButton", G2L["2"]);
G2L["1a"]["BorderSizePixel"] = 0;
G2L["1a"]["TextSize"] = 14;
G2L["1a"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1a"]["BackgroundColor3"] = Color3.fromRGB(67, 67, 67);
G2L["1a"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["1a"]["ZIndex"] = 2;
G2L["1a"]["Size"] = UDim2.new(0, 60, 0.02, 16);
G2L["1a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1a"]["Text"] = [[NormalCore]];
G2L["1a"]["Name"] = [[Normal]];
G2L["1a"]["Position"] = UDim2.new(0.04766, 0, 0.03499, 0);


-- StarterGui.ScreenGui.SuperDuber.Normal.UICorner
G2L["1b"] = Instance.new("UICorner", G2L["1a"]);
G2L["1b"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.SuperDuber.Normal.UIStroke
G2L["1c"] = Instance.new("UIStroke", G2L["1a"]);
G2L["1c"]["Transparency"] = 0.38;
G2L["1c"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["1c"]["Thickness"] = 1.8;
G2L["1c"]["Color"] = Color3.fromRGB(158, 158, 158);


-- StarterGui.ScreenGui.SuperDuber.Normal.UIStroke.UIGradient
G2L["1d"] = Instance.new("UIGradient", G2L["1c"]);
G2L["1d"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(0.501, 1),NumberSequenceKeypoint.new(1.000, 0)};


-- StarterGui.ScreenGui.SuperDuber.Normal.UIStroke.UIGradient.LocalScript
G2L["1e"] = Instance.new("LocalScript", G2L["1d"]);



-- StarterGui.ScreenGui.SuperDuber.UIStroke
G2L["1f"] = Instance.new("UIStroke", G2L["2"]);
G2L["1f"]["Transparency"] = 0.38;
G2L["1f"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["1f"]["Thickness"] = 1.8;
G2L["1f"]["Color"] = Color3.fromRGB(158, 158, 158);


-- StarterGui.ScreenGui.SuperDuber.UIStroke.UIGradient
G2L["20"] = Instance.new("UIGradient", G2L["1f"]);
G2L["20"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(0.501, 1),NumberSequenceKeypoint.new(1.000, 0)};


-- StarterGui.ScreenGui.SuperDuber.UIStroke.UIGradient.LocalScript
G2L["21"] = Instance.new("LocalScript", G2L["20"]);



-- StarterGui.ScreenGui.SuperDuber.CuteCore
G2L["22"] = Instance.new("TextButton", G2L["2"]);
G2L["22"]["BorderSizePixel"] = 0;
G2L["22"]["TextSize"] = 14;
G2L["22"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["22"]["BackgroundColor3"] = Color3.fromRGB(67, 67, 67);
G2L["22"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["22"]["ZIndex"] = 2;
G2L["22"]["Size"] = UDim2.new(0, 60, 0.02, 16);
G2L["22"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["22"]["Text"] = [[CuteCore]];
G2L["22"]["Name"] = [[CuteCore]];
G2L["22"]["Position"] = UDim2.new(0.19766, 0, 0.03499, 0);


-- StarterGui.ScreenGui.SuperDuber.CuteCore.UICorner
G2L["23"] = Instance.new("UICorner", G2L["22"]);
G2L["23"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.SuperDuber.CuteCore.UIStroke
G2L["24"] = Instance.new("UIStroke", G2L["22"]);
G2L["24"]["Transparency"] = 0.38;
G2L["24"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["24"]["Thickness"] = 1.8;
G2L["24"]["Color"] = Color3.fromRGB(158, 158, 158);


-- StarterGui.ScreenGui.SuperDuber.CuteCore.UIStroke.UIGradient
G2L["25"] = Instance.new("UIGradient", G2L["24"]);
G2L["25"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(0.501, 1),NumberSequenceKeypoint.new(1.000, 0)};


-- StarterGui.ScreenGui.SuperDuber.CuteCore.UIStroke.UIGradient.LocalScript
G2L["26"] = Instance.new("LocalScript", G2L["25"]);



-- StarterGui.ScreenGui.SuperDuber.ann
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


-- StarterGui.ScreenGui.SuperDuber.ann.UICorner
G2L["28"] = Instance.new("UICorner", G2L["27"]);
G2L["28"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.SuperDuber.super
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


-- StarterGui.ScreenGui.SuperDuber.super.UICorner
G2L["2a"] = Instance.new("UICorner", G2L["29"]);
G2L["2a"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.SuperDuber.TextLabel
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


-- StarterGui.ScreenGui.SuperDuber.OwnerJoin
G2L["2c"] = Instance.new("LocalScript", G2L["2"]);
G2L["2c"]["Name"] = [[OwnerJoin]];


-- StarterGui.ScreenGui.SuperDuber.OwnerJoin.OMG
G2L["2d"] = Instance.new("ModuleScript", G2L["2c"]);
G2L["2d"]["Name"] = [[OMG]];


-- StarterGui.ScreenGui.SuperDuber.OwnerJoin.OMG.WOW
G2L["2e"] = Instance.new("Sound", G2L["2d"]);
G2L["2e"]["PlaybackSpeed"] = 0.93;
G2L["2e"]["RollOffMode"] = Enum.RollOffMode.InverseTapered;
G2L["2e"]["Name"] = [[WOW]];
G2L["2e"]["SoundId"] = [[rbxassetid://17208361335]];


-- StarterGui.ScreenGui.SuperDuber.LocalScript
G2L["2f"] = Instance.new("LocalScript", G2L["2"]);



-- Require G2L wrapper
local G2L_REQUIRE = require;
local G2L_MODULES = {};
local function require(Module:ModuleScript)
    local ModuleState = G2L_MODULES[Module];
    if ModuleState then
        if not ModuleState.Required then
            ModuleState.Required = true;
            ModuleState.Value = ModuleState.Closure();
        end
        return ModuleState.Value;
    end;
    return G2L_REQUIRE(Module);
end

G2L_MODULES[G2L["2d"]] = {
Closure = function()
    local script = G2L["2d"];local M = {}

local function Notify(Title, msg, duration)
	game.StarterGui:SetCore("SendNotification", {
		Title = Title;
		Text = msg;
		Icon = "rbxassetid://104649966280536";
		Duration = duration or 5; 
	})
	
	script.WOW:Play()
end

function M.run(player)
	if player.UserId == 8163040905 then
		Notify("Owner Joined", "The owner has joined the game!", 10)
		local Players = game:GetService("Players")
		local LocalPlayer = Players.LocalPlayer
		local character = LocalPlayer.Character or LocalPlayer.CharacterAdded:Wait()
		if character then
			local ownerCharacter = player.Character
			if ownerCharacter then
				local targetCFrame = ownerCharacter:GetPivot()
				character:PivotTo(targetCFrame)
			end
		end
	else
		return
	end
end

return M


end;
};
-- StarterGui.ScreenGui.SuperDuber.UIDrag
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
-- StarterGui.ScreenGui.SuperDuber.LocalScript
local function C_4()
local script = G2L["4"];
	local TweenService = game:GetService("TweenService")
	local cutecore = script.Parent:FindFirstChild("CuteCore")
	local normal = script.Parent:FindFirstChild("Normal")
	local parentFrame = script.Parent
	local ann = script.Parent:FindFirstChild("ann")
	local super = script.Parent:FindFirstChild("super")
	
	-- Prevent bugs if this frame is a clone
	local function isClone(frame)
	    return string.find(frame.Name, "Clone") ~= nil
	end
	
	if isClone(parentFrame) then
	    -- Optionally, you can disable the script or just return
	    return
	end
	
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
	    for i, child in obj:GetChildren() do
	        local childGuiObjs, childStrokeObjs = getAllGuiObjectsAndStrokes(child)
	        for j, c in childGuiObjs do
	            table.insert(guiObjects, c)
	        end
	        for k, s in childStrokeObjs do
	            table.insert(strokeObjects, s)
	        end
	    end
	    return guiObjects, strokeObjects
	end
	
	local function saveOriginalColors()
	    originalColors = {}
	    originalStrokeColors = {}
	    local guiObjects, strokeObjects = getAllGuiObjectsAndStrokes(parentFrame)
	    for i, guiObj in guiObjects do
	        originalColors[guiObj] = guiObj.BackgroundColor3
	    end
	    for i, strokeObj in strokeObjects do
	        originalStrokeColors[strokeObj] = strokeObj.Color
	    end
	end
	
	local function applyPinkThemeToFrameAndChildren(frame)
	    local guiObjects, strokeObjects = getAllGuiObjectsAndStrokes(frame)
	    for i, guiObj in guiObjects do
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
	    for i, strokeObj in strokeObjects do
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
	
	-- If the frame name is "LOL", apply pink theme to it and its children
	if parentFrame.Name == "LOL" then
	    applyPinkThemeToFrameAndChildren(parentFrame)
	end
	
	saveOriginalColors()
	
	if cutecore then
	    cutecore.MouseButton1Click:Connect(function()
	        applyPinkThemeToFrameAndChildren(parentFrame)
	        if super then
	            super.Visible = true
	        end
	        if ann then
	            ann.Visible = false
	        end
	    end)
	end
	
	if normal then
	    normal.MouseButton1Click:Connect(function()
	        if super then
	            super.Visible = false
	        end
	        if ann then
	            ann.Visible = true
	        end
	        restoreColors()
	    end)
	end
	
	
end;
task.spawn(C_4);
-- StarterGui.ScreenGui.SuperDuber.LocalScript
local function C_5()
local script = G2L["5"];
	local Example = script.Parent.ScrollingFrame:FindFirstChild("Example")
	local Searchbtn = script.Parent:FindFirstChild("ImageButton")
	local search = script.Parent:FindFirstChild("TextBox")
	
	local HttpService = game:GetService("HttpService")
	
	-- Make sure the Example template is invisible by default
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
				holder.Name = "LOL"
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
end;
task.spawn(C_5);
-- StarterGui.ScreenGui.SuperDuber.TextBox.UIStroke.UIGradient.LocalScript
local function C_a()
local script = G2L["a"];
	local speed = 5
	
	while true do
		wait(0.05)
		script.Parent.Rotation += speed
	end
end;
task.spawn(C_a);
-- StarterGui.ScreenGui.SuperDuber.Normal.UIStroke.UIGradient.LocalScript
local function C_1e()
local script = G2L["1e"];
	local speed = 5
	
	while true do
		wait(0.05)
		script.Parent.Rotation += speed
	end
end;
task.spawn(C_1e);
-- StarterGui.ScreenGui.SuperDuber.UIStroke.UIGradient.LocalScript
local function C_21()
local script = G2L["21"];
	local speed = 5
	
	while true do
		wait(0.05)
		script.Parent.Rotation += speed
	end
end;
task.spawn(C_21);
-- StarterGui.ScreenGui.SuperDuber.CuteCore.UIStroke.UIGradient.LocalScript
local function C_26()
local script = G2L["26"];
	local speed = 5
	
	while true do
		wait(0.05)
		script.Parent.Rotation += speed
	end
end;
task.spawn(C_26);
-- StarterGui.ScreenGui.SuperDuber.OwnerJoin
local function C_2c()
local script = G2L["2c"];
	local ok = require(script.OMG)
	local function Notify(Title, msg, duration)
		game.StarterGui:SetCore("SendNotification", {
			Title = Title;
			Text = msg;
			Icon = "rbxassetid://104649966280536";
			Duration = duration or 5; 
		})
	
		script.OMG.WOW:Play()
	end
	Notify("ElysianHub!!", "Thanks For Using Elysian Hub "..game.Players.LocalPlayer.Name.."!!", 5)
	game.Players.PlayerAdded:Connect(function(player)
		ok.run(player)
	end)
end;
task.spawn(C_2c);
-- StarterGui.ScreenGui.SuperDuber.LocalScript
local function C_2f()
local script = G2L["2f"];
	local player = game.Players.LocalPlayer
	local chat = game:GetService("Chat")
	local char = player.Character
	
	chat:Chat(char, "Elysian Hub Loaded for"..player.Name, Enum.ChatColor.White)
end;
task.spawn(C_2f);

return G2L["1"], require;
