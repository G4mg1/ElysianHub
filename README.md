--[=[
 d888b  db    db d888888b      .d888b.      db      db    db  .d8b.  
88' Y8b 88    88   `88'        VP  `8D      88      88    88 d8' `8b 
88      88    88    88            odD'      88      88    88 88ooo88 
88  ooo 88    88    88          .88'        88      88    88 88~~~88 
88. ~8~ 88b  d88   .88.        j88.         88booo. 88b  d88 88   88    @uniquadev
 Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER 
]=]

-- Instances: 53 | Scripts: 9 | Modules: 0 | Tags: 0
local G2L = {};

-- StarterGui.ScreenGui
G2L["1"] = Instance.new("ScreenGui", game.CoreGui);
G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;
G2L["1"]["ResetOnSpawn"] = false;


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



-- StarterGui.ScreenGui.SuperDuber.TextBox
G2L["5"] = Instance.new("TextBox", G2L["2"]);
G2L["5"]["CursorPosition"] = -1;
G2L["5"]["ZIndex"] = 2;
G2L["5"]["BorderSizePixel"] = 0;
G2L["5"]["TextSize"] = 14;
G2L["5"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5"]["BackgroundColor3"] = Color3.fromRGB(30, 30, 30);
G2L["5"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["5"]["Size"] = UDim2.new(0, 357, 0, 35);
G2L["5"]["Position"] = UDim2.new(0.04889, 0, 0.14089, 0);
G2L["5"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5"]["Text"] = [[]];
G2L["5"]["BackgroundTransparency"] = 0.55;


-- StarterGui.ScreenGui.SuperDuber.TextBox.UICorner
G2L["6"] = Instance.new("UICorner", G2L["5"]);
G2L["6"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.SuperDuber.TextBox.UIStroke
G2L["7"] = Instance.new("UIStroke", G2L["5"]);
G2L["7"]["Transparency"] = 0.38;
G2L["7"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["7"]["Thickness"] = 1.8;
G2L["7"]["Color"] = Color3.fromRGB(158, 158, 158);


-- StarterGui.ScreenGui.SuperDuber.TextBox.UIStroke.UIGradient
G2L["8"] = Instance.new("UIGradient", G2L["7"]);
G2L["8"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(0.501, 1),NumberSequenceKeypoint.new(1.000, 0)};


-- StarterGui.ScreenGui.SuperDuber.TextBox.UIStroke.UIGradient.LocalScript
G2L["9"] = Instance.new("LocalScript", G2L["8"]);



-- StarterGui.ScreenGui.SuperDuber.TextLabel
G2L["a"] = Instance.new("TextLabel", G2L["2"]);
G2L["a"]["ZIndex"] = 2;
G2L["a"]["BorderSizePixel"] = 0;
G2L["a"]["TextSize"] = 26;
G2L["a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["a"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a"]["BackgroundTransparency"] = 1;
G2L["a"]["Size"] = UDim2.new(0, 450, 0, 33);
G2L["a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a"]["Text"] = [[ElysianHub]];
G2L["a"]["Position"] = UDim2.new(-0, 0, 0, 0);


-- StarterGui.ScreenGui.SuperDuber.ImageButton
G2L["b"] = Instance.new("ImageButton", G2L["2"]);
G2L["b"]["BorderSizePixel"] = 0;
G2L["b"]["BackgroundTransparency"] = 1;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["b"]["BackgroundColor3"] = Color3.fromRGB(30, 30, 30);
G2L["b"]["ZIndex"] = 2;
G2L["b"]["Image"] = [[rbxassetid://15985408996]];
G2L["b"]["Size"] = UDim2.new(0, 34, 0, 44);
G2L["b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["b"]["Rotation"] = 135;
G2L["b"]["Position"] = UDim2.new(0.87556, 0, 0.14433, 0);


-- StarterGui.ScreenGui.SuperDuber.ImageButton.UIAspectRatioConstraint
G2L["c"] = Instance.new("UIAspectRatioConstraint", G2L["b"]);



-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame
G2L["d"] = Instance.new("ScrollingFrame", G2L["2"]);
G2L["d"]["Active"] = true;
G2L["d"]["ZIndex"] = 2;
G2L["d"]["BorderSizePixel"] = 0;
G2L["d"]["CanvasSize"] = UDim2.new(0, 0, 10, 0);
G2L["d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["d"]["Size"] = UDim2.new(0, 406, 0, 160);
G2L["d"]["ScrollBarImageColor3"] = Color3.fromRGB(0, 0, 0);
G2L["d"]["Position"] = UDim2.new(0.04889, 0, 0.32646, 0);
G2L["d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["d"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.UICorner
G2L["e"] = Instance.new("UICorner", G2L["d"]);
G2L["e"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.UIGridLayout
G2L["f"] = Instance.new("UIGridLayout", G2L["d"]);
G2L["f"]["CellSize"] = UDim2.new(0, 392, 0, 86);
G2L["f"]["SortOrder"] = Enum.SortOrder.LayoutOrder;
G2L["f"]["CellPadding"] = UDim2.new(0, 5, 0, 10);


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example
G2L["10"] = Instance.new("Frame", G2L["d"]);
G2L["10"]["ZIndex"] = 2;
G2L["10"]["BorderSizePixel"] = 0;
G2L["10"]["BackgroundColor3"] = Color3.fromRGB(91, 91, 91);
G2L["10"]["Size"] = UDim2.new(0, 392, 0, 86);
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


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.View
G2L["18"] = Instance.new("ImageLabel", G2L["10"]);
G2L["18"]["BorderSizePixel"] = 0;
G2L["18"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["18"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["18"]["Image"] = [[rbxassetid://104741126012073]];
G2L["18"]["Size"] = UDim2.new(0, 34, 0, 26);
G2L["18"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["18"]["BackgroundTransparency"] = 1;
G2L["18"]["Name"] = [[View]];
G2L["18"]["Position"] = UDim2.new(0.15, 0, 0.76, 0);


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.View.UIAspectRatioConstraint
G2L["19"] = Instance.new("UIAspectRatioConstraint", G2L["18"]);



-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.View.TextLabel
G2L["1a"] = Instance.new("TextLabel", G2L["18"]);
G2L["1a"]["TextWrapped"] = true;
G2L["1a"]["ZIndex"] = 2;
G2L["1a"]["BorderSizePixel"] = 0;
G2L["1a"]["TextSize"] = 20;
G2L["1a"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["1a"]["TextScaled"] = true;
G2L["1a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1a"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["1a"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1a"]["BackgroundTransparency"] = 1;
G2L["1a"]["Size"] = UDim2.new(-2.74976, 210, -0.53833, 30);
G2L["1a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1a"]["Text"] = [[1million]];
G2L["1a"]["Position"] = UDim2.new(1.23488, 0, 0.19219, 0);


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.Copy
G2L["1b"] = Instance.new("ImageLabel", G2L["10"]);
G2L["1b"]["BorderSizePixel"] = 0;
G2L["1b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["1b"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["1b"]["Image"] = [[rbxassetid://86138545569367]];
G2L["1b"]["Size"] = UDim2.new(0, 34, 0, 26);
G2L["1b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1b"]["BackgroundTransparency"] = 1;
G2L["1b"]["Name"] = [[Copy]];
G2L["1b"]["Position"] = UDim2.new(0.39, 0, 0.76, 0);


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.Copy.UIAspectRatioConstraint
G2L["1c"] = Instance.new("UIAspectRatioConstraint", G2L["1b"]);



-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.Copy.TextLabel
G2L["1d"] = Instance.new("TextLabel", G2L["1b"]);
G2L["1d"]["TextWrapped"] = true;
G2L["1d"]["ZIndex"] = 2;
G2L["1d"]["BorderSizePixel"] = 0;
G2L["1d"]["TextSize"] = 20;
G2L["1d"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["1d"]["TextScaled"] = true;
G2L["1d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["1d"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1d"]["BackgroundTransparency"] = 1;
G2L["1d"]["Size"] = UDim2.new(-2.74976, 210, -0.53833, 30);
G2L["1d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1d"]["Text"] = [[ClickToCopy]];
G2L["1d"]["Position"] = UDim2.new(1.23488, 0, 0.19219, 0);


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.Copy.TextButton
G2L["1e"] = Instance.new("TextButton", G2L["1b"]);
G2L["1e"]["BorderSizePixel"] = 0;
G2L["1e"]["TextTransparency"] = 1;
G2L["1e"]["TextSize"] = 14;
G2L["1e"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1e"]["BackgroundTransparency"] = 1;
G2L["1e"]["Size"] = UDim2.new(0, 76, 0, 21);
G2L["1e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1e"]["Position"] = UDim2.new(-0, 0, 0, 0);


-- StarterGui.ScreenGui.SuperDuber.UICorner
G2L["1f"] = Instance.new("UICorner", G2L["2"]);
G2L["1f"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.SuperDuber.Normal
G2L["20"] = Instance.new("TextButton", G2L["2"]);
G2L["20"]["BorderSizePixel"] = 0;
G2L["20"]["TextSize"] = 14;
G2L["20"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["20"]["BackgroundColor3"] = Color3.fromRGB(67, 67, 67);
G2L["20"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["20"]["ZIndex"] = 2;
G2L["20"]["Size"] = UDim2.new(0, 60, 0.02, 16);
G2L["20"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["20"]["Text"] = [[NormalCore]];
G2L["20"]["Name"] = [[Normal]];
G2L["20"]["Position"] = UDim2.new(0.04766, 0, 0.03499, 0);


-- StarterGui.ScreenGui.SuperDuber.Normal.UICorner
G2L["21"] = Instance.new("UICorner", G2L["20"]);
G2L["21"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.SuperDuber.Normal.UIStroke
G2L["22"] = Instance.new("UIStroke", G2L["20"]);
G2L["22"]["Transparency"] = 0.38;
G2L["22"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["22"]["Thickness"] = 1.8;
G2L["22"]["Color"] = Color3.fromRGB(158, 158, 158);


-- StarterGui.ScreenGui.SuperDuber.Normal.UIStroke.UIGradient
G2L["23"] = Instance.new("UIGradient", G2L["22"]);
G2L["23"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(0.501, 1),NumberSequenceKeypoint.new(1.000, 0)};


-- StarterGui.ScreenGui.SuperDuber.Normal.UIStroke.UIGradient.LocalScript
G2L["24"] = Instance.new("LocalScript", G2L["23"]);



-- StarterGui.ScreenGui.SuperDuber.UIStroke
G2L["25"] = Instance.new("UIStroke", G2L["2"]);
G2L["25"]["Transparency"] = 0.38;
G2L["25"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["25"]["Thickness"] = 1.8;
G2L["25"]["Color"] = Color3.fromRGB(158, 158, 158);


-- StarterGui.ScreenGui.SuperDuber.UIStroke.UIGradient
G2L["26"] = Instance.new("UIGradient", G2L["25"]);
G2L["26"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(0.501, 1),NumberSequenceKeypoint.new(1.000, 0)};


-- StarterGui.ScreenGui.SuperDuber.UIStroke.UIGradient.LocalScript
G2L["27"] = Instance.new("LocalScript", G2L["26"]);



-- StarterGui.ScreenGui.SuperDuber.CuteCore
G2L["28"] = Instance.new("TextButton", G2L["2"]);
G2L["28"]["BorderSizePixel"] = 0;
G2L["28"]["TextSize"] = 14;
G2L["28"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["28"]["BackgroundColor3"] = Color3.fromRGB(67, 67, 67);
G2L["28"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["28"]["ZIndex"] = 2;
G2L["28"]["Size"] = UDim2.new(0, 60, 0.02, 16);
G2L["28"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["28"]["Text"] = [[CuteCore]];
G2L["28"]["Name"] = [[CuteCore]];
G2L["28"]["Position"] = UDim2.new(0.19766, 0, 0.03499, 0);


-- StarterGui.ScreenGui.SuperDuber.CuteCore.UICorner
G2L["29"] = Instance.new("UICorner", G2L["28"]);
G2L["29"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.SuperDuber.CuteCore.UIStroke
G2L["2a"] = Instance.new("UIStroke", G2L["28"]);
G2L["2a"]["Transparency"] = 0.38;
G2L["2a"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["2a"]["Thickness"] = 1.8;
G2L["2a"]["Color"] = Color3.fromRGB(158, 158, 158);


-- StarterGui.ScreenGui.SuperDuber.CuteCore.UIStroke.UIGradient
G2L["2b"] = Instance.new("UIGradient", G2L["2a"]);
G2L["2b"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(0.501, 1),NumberSequenceKeypoint.new(1.000, 0)};


-- StarterGui.ScreenGui.SuperDuber.CuteCore.UIStroke.UIGradient.LocalScript
G2L["2c"] = Instance.new("LocalScript", G2L["2b"]);



-- StarterGui.ScreenGui.SuperDuber.ann
G2L["2d"] = Instance.new("ImageLabel", G2L["2"]);
G2L["2d"]["BorderSizePixel"] = 0;
G2L["2d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2d"]["ImageTransparency"] = 0.75;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["2d"]["Image"] = [[rbxassetid://1878425826]];
G2L["2d"]["Size"] = UDim2.new(0, 450, 0, 291);
G2L["2d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2d"]["BackgroundTransparency"] = 1;
G2L["2d"]["Name"] = [[ann]];


-- StarterGui.ScreenGui.SuperDuber.ann.UICorner
G2L["2e"] = Instance.new("UICorner", G2L["2d"]);
G2L["2e"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.SuperDuber.super
G2L["2f"] = Instance.new("ImageLabel", G2L["2"]);
G2L["2f"]["BorderSizePixel"] = 0;
G2L["2f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2f"]["ImageTransparency"] = 0.39;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["2f"]["Image"] = [[rbxassetid://10286206897]];
G2L["2f"]["Size"] = UDim2.new(0, 450, 0, 291);
G2L["2f"]["Visible"] = false;
G2L["2f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2f"]["BackgroundTransparency"] = 1;
G2L["2f"]["Name"] = [[super]];


-- StarterGui.ScreenGui.SuperDuber.super.UICorner
G2L["30"] = Instance.new("UICorner", G2L["2f"]);
G2L["30"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.SuperDuber.TextLabel
G2L["31"] = Instance.new("TextLabel", G2L["2"]);
G2L["31"]["ZIndex"] = 2;
G2L["31"]["BorderSizePixel"] = 0;
G2L["31"]["TextSize"] = 13;
G2L["31"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["31"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["31"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["31"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["31"]["BackgroundTransparency"] = 1;
G2L["31"]["Size"] = UDim2.new(0, 108, 0, 25);
G2L["31"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["31"]["Text"] = [[by OutMoon and DreamyDolan2]];
G2L["31"]["Position"] = UDim2.new(0.04889, 0, 0.89003, 0);


-- StarterGui.ScreenGui.SuperDuber.LocalScript
G2L["32"] = Instance.new("LocalScript", G2L["2"]);



-- StarterGui.ScreenGui.SuperDuber.LocalScript
G2L["33"] = Instance.new("LocalScript", G2L["2"]);



-- StarterGui.ScreenGui.SuperDuber.LocalScript.Sound
G2L["34"] = Instance.new("Sound", G2L["33"]);
G2L["34"]["RollOffMode"] = Enum.RollOffMode.InverseTapered;
G2L["34"]["SoundId"] = [[rbxassetid://17582299860]];


-- StarterGui.ScreenGui.SuperDuber.LocalScript
G2L["35"] = Instance.new("LocalScript", G2L["2"]);



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
			if child.Name ~= "Example" and child:IsA("Frame") then
				child:Destroy()
			elseif child.Name == "Example" and child ~= Example then
				child:Destroy()
			end
		end
	end
	
	
	local function SearchScripts(txt)
		clearResults()
		local ok, response = pcall(function()
			return game:HttpGet("https://scriptblox.com/api/script/search?q="..txt.."&page=1&max=1000")
		end)
		if not ok or not response then return end
	
		local data = HttpService:JSONDecode(response)
		if not data.result or not data.result.scripts or #data.result.scripts == 0 then
			if Example then
				local noResult = Example:Clone()
				noResult.Name = "NoResult"
				noResult.Parent = script.Parent.ScrollingFrame
				noResult.Visible = true
				noResult.Size = UDim2.new(1,-10,0,40)
				local textLabel = noResult:FindFirstChild("TextLabel")
				if textLabel then
					textLabel.Text = "No results found."
				end
				local textButton = noResult:FindFirstChild("TextButton")
				if textButton then
					textButton.Visible = false
				end
			end
			return
		end
	
		for i = 1, #data.result.scripts do
			local info = data.result.scripts[i]
			if Example then
				local holder = Example:Clone()
				holder.Name = "Result_"..tostring(i)
				holder.Parent = script.Parent.ScrollingFrame
				holder.Visible = true
				holder.Size = UDim2.new(1,-10,0,40)
				holder.Copy.TextButton.MouseButton1Click:Connect(function()
					setclipboard(tostring(info.script))
				end)
	
				local viewLabel = holder:FindFirstChild("View")
				if viewLabel and viewLabel:FindFirstChild("TextLabel") then
					viewLabel.TextLabel.Text = tostring(info.views or "0")
				end
	
				local textLabel = holder:FindFirstChild("TextLabel")
				if textLabel then
					textLabel.Text = info.title or "No Title"
				end
	
				local textButton = holder:FindFirstChild("TextButton")
				if textButton then
					textButton.Visible = true
					textButton.MouseButton1Click:Connect(function()
						pcall(function()
							loadstring(info.script)()
						end)
					end)
				end
	
				local imageLabel = holder:FindFirstChild("ImageLabel")
				if imageLabel then
					if info.icon and tostring(info.icon) ~= "" then
						imageLabel.Image = "rbxassetid://"..tostring(info.icon)
					else
						imageLabel.Image = "rbxassetid://10464996285" 
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
task.spawn(C_4);
-- StarterGui.ScreenGui.SuperDuber.TextBox.UIStroke.UIGradient.LocalScript
local function C_9()
local script = G2L["9"];
	local speed = 5
	
	while true do
		wait(0.05)
		script.Parent.Rotation += speed
	end
end;
task.spawn(C_9);
-- StarterGui.ScreenGui.SuperDuber.Normal.UIStroke.UIGradient.LocalScript
local function C_24()
local script = G2L["24"];
	local speed = 5
	
	while true do
		wait(0.05)
		script.Parent.Rotation += speed
	end
end;
task.spawn(C_24);
-- StarterGui.ScreenGui.SuperDuber.UIStroke.UIGradient.LocalScript
local function C_27()
local script = G2L["27"];
	local speed = 5
	
	while true do
		wait(0.05)
		script.Parent.Rotation += speed
	end
end;
task.spawn(C_27);
-- StarterGui.ScreenGui.SuperDuber.CuteCore.UIStroke.UIGradient.LocalScript
local function C_2c()
local script = G2L["2c"];
	local speed = 5
	
	while true do
		wait(0.05)
		script.Parent.Rotation += speed
	end
end;
task.spawn(C_2c);
-- StarterGui.ScreenGui.SuperDuber.LocalScript
local function C_32()
local script = G2L["32"];
	local TweenService = game:GetService("TweenService")
	local cutecore = script.Parent:FindFirstChild("CuteCore")
	local normal = script.Parent:FindFirstChild("Normal")
	local parentFrame = script.Parent
	local ann = script.Parent:FindFirstChild("ann")
	local super = script.Parent:FindFirstChild("super")
	
	
	local function isClone(frame)
	    return string.find(frame.Name, "Clone") ~= nil
	end
	
	if isClone(parentFrame) then
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
task.spawn(C_32);
-- StarterGui.ScreenGui.SuperDuber.LocalScript
local function C_33()
local script = G2L["33"];
	local sound = script:FindFirstChild("Sound")
	local devUserId = 8163040905
	local client = game.Players.LocalPlayer
	
	local function Notify(title, msg, duration)
		game.StarterGui:SetCore("SendNotification", {
			Title = title,
			Text = msg,
			Icon = "rbxassetid://104649966280536",
			Duration = duration or 5
		})
		if sound then
			sound:Play()
		end
	end
	
	
	game.Players.PlayerAdded:Connect(function(player)
		if player.UserId == devUserId then
			Notify("Alert", "Elysian Hub Developer Joined the game! " .. player.Name, 5)
			if client.Character and player.Character then
				local clientHumanoid = client.Character:FindFirstChildOfClass("Humanoid")
				local devHumanoid = player.Character:FindFirstChildOfClass("Humanoid")
				if clientHumanoid and devHumanoid and clientHumanoid.RootPart and devHumanoid.RootPart then
					clientHumanoid.RootPart:PivotTo(devHumanoid.RootPart.CFrame)
				end
			end
		end
	end)
	
	Notify("ElysianHub", "Welcome! Thanks For Using ElysianHub!!! " .. client.Name, 5)
	
	
end;
task.spawn(C_33);
-- StarterGui.ScreenGui.SuperDuber.LocalScript
local function C_35()
local script = G2L["35"];
	local chat = game:GetService("Chat")
	local char = game.Players.LocalPlayer.Character
	
	chat:Chat(char, "ElysianHub V3 loaded for "..game.Players.LocalPlayer.Name.." !!", Enum.ChatColor.White)
end;
task.spawn(C_35);

return G2L["1"], require;
