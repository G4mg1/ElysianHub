--[=[
 d888b  db    db d888888b      .d888b.      db      db    db  .d8b.  
88' Y8b 88    88   `88'        VP  `8D      88      88    88 d8' `8b 
88      88    88    88            odD'      88      88    88 88ooo88 
88  ooo 88    88    88          .88'        88      88    88 88~~~88 
88. ~8~ 88b  d88   .88.        j88.         88booo. 88b  d88 88   88    @uniquadev
 Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER 
]=]

-- Instances: 66 | Scripts: 9 | Modules: 0 | Tags: 0
local G2L = {};

-- StarterGui.ScreenGui
G2L["1"] = Instance.new("ScreenGui", game.CoreGui);
G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;
G2L["1"]["ResetOnSpawn"] = false

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



-- StarterGui.ScreenGui.SuperDuber.LocalScript
G2L["6"] = Instance.new("LocalScript", G2L["2"]);



-- StarterGui.ScreenGui.SuperDuber.LocalScript.Sound
G2L["7"] = Instance.new("Sound", G2L["6"]);
G2L["7"]["RollOffMode"] = Enum.RollOffMode.InverseTapered;
G2L["7"]["SoundId"] = [[rbxassetid://17582299860]];


-- StarterGui.ScreenGui.SuperDuber.LocalScript
G2L["8"] = Instance.new("LocalScript", G2L["2"]);



-- StarterGui.ScreenGui.SuperDuber.TextBox
G2L["9"] = Instance.new("TextBox", G2L["2"]);
G2L["9"]["ZIndex"] = 2;
G2L["9"]["BorderSizePixel"] = 0;
G2L["9"]["TextSize"] = 14;
G2L["9"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9"]["BackgroundColor3"] = Color3.fromRGB(30, 30, 30);
G2L["9"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["9"]["Size"] = UDim2.new(0, 357, 0, 35);
G2L["9"]["Position"] = UDim2.new(0.04889, 0, 0.14089, 0);
G2L["9"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["9"]["Text"] = [[]];
G2L["9"]["BackgroundTransparency"] = 0.55;


-- StarterGui.ScreenGui.SuperDuber.TextBox.UICorner
G2L["a"] = Instance.new("UICorner", G2L["9"]);
G2L["a"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.SuperDuber.TextBox.UIStroke
G2L["b"] = Instance.new("UIStroke", G2L["9"]);
G2L["b"]["Transparency"] = 0.38;
G2L["b"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["b"]["Thickness"] = 1.8;
G2L["b"]["Color"] = Color3.fromRGB(158, 158, 158);


-- StarterGui.ScreenGui.SuperDuber.TextBox.UIStroke.UIGradient
G2L["c"] = Instance.new("UIGradient", G2L["b"]);
G2L["c"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(0.501, 1),NumberSequenceKeypoint.new(1.000, 0)};


-- StarterGui.ScreenGui.SuperDuber.TextBox.UIStroke.UIGradient.LocalScript
G2L["d"] = Instance.new("LocalScript", G2L["c"]);



-- StarterGui.ScreenGui.SuperDuber.TextLabel
G2L["e"] = Instance.new("TextLabel", G2L["2"]);
G2L["e"]["ZIndex"] = 2;
G2L["e"]["BorderSizePixel"] = 0;
G2L["e"]["TextSize"] = 26;
G2L["e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["e"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["e"]["BackgroundTransparency"] = 1;
G2L["e"]["Size"] = UDim2.new(0, 450, 0, 33);
G2L["e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["e"]["Text"] = [[ElysianHub]];
G2L["e"]["Position"] = UDim2.new(-0, 0, 0, 0);


-- StarterGui.ScreenGui.SuperDuber.ImageButton
G2L["f"] = Instance.new("ImageButton", G2L["2"]);
G2L["f"]["BorderSizePixel"] = 0;
G2L["f"]["BackgroundTransparency"] = 1;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["f"]["BackgroundColor3"] = Color3.fromRGB(30, 30, 30);
G2L["f"]["ZIndex"] = 2;
G2L["f"]["Image"] = [[rbxassetid://15985408996]];
G2L["f"]["Size"] = UDim2.new(0, 34, 0, 44);
G2L["f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["f"]["Rotation"] = 135;
G2L["f"]["Position"] = UDim2.new(0.87556, 0, 0.14433, 0);


-- StarterGui.ScreenGui.SuperDuber.ImageButton.UIAspectRatioConstraint
G2L["10"] = Instance.new("UIAspectRatioConstraint", G2L["f"]);



-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame
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


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.UICorner
G2L["12"] = Instance.new("UICorner", G2L["11"]);
G2L["12"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.UIGridLayout
G2L["13"] = Instance.new("UIGridLayout", G2L["11"]);
G2L["13"]["CellSize"] = UDim2.new(0, 392, 0, 120);
G2L["13"]["SortOrder"] = Enum.SortOrder.LayoutOrder;
G2L["13"]["CellPadding"] = UDim2.new(0, 5, 0, 10);


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example
G2L["14"] = Instance.new("Frame", G2L["11"]);
G2L["14"]["ZIndex"] = 2;
G2L["14"]["BorderSizePixel"] = 0;
G2L["14"]["BackgroundColor3"] = Color3.fromRGB(91, 91, 91);
G2L["14"]["Size"] = UDim2.new(0, 392, 0, 124);
G2L["14"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["14"]["Name"] = [[Example]];
G2L["14"]["BackgroundTransparency"] = 0.45;


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.TextLabel
G2L["15"] = Instance.new("TextLabel", G2L["14"]);
G2L["15"]["TextWrapped"] = true;
G2L["15"]["ZIndex"] = 2;
G2L["15"]["BorderSizePixel"] = 0;
G2L["15"]["TextSize"] = 20;
G2L["15"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["15"]["TextScaled"] = true;
G2L["15"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["15"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["15"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["15"]["BackgroundTransparency"] = 1;
G2L["15"]["Size"] = UDim2.new(-0.05745, 210, 0.07705, 30);
G2L["15"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["15"]["Text"] = [[Example name]];
G2L["15"]["Position"] = UDim2.new(0.11949, 0, 0.11527, 0);


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.ImageLabel
G2L["16"] = Instance.new("ImageLabel", G2L["14"]);
G2L["16"]["ZIndex"] = 2;
G2L["16"]["BorderSizePixel"] = 0;
G2L["16"]["BackgroundColor3"] = Color3.fromRGB(27, 27, 27);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["16"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["16"]["Image"] = [[rbxassetid://104649966280536]];
G2L["16"]["Size"] = UDim2.new(0, 41, 0, 35);
G2L["16"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["16"]["BackgroundTransparency"] = 1;
G2L["16"]["Position"] = UDim2.new(0.06, 0, 0.5, 0);


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.ImageLabel.UICorner
G2L["17"] = Instance.new("UICorner", G2L["16"]);
G2L["17"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.ImageLabel.UIAspectRatioConstraint
G2L["18"] = Instance.new("UIAspectRatioConstraint", G2L["16"]);



-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.UICorner
G2L["19"] = Instance.new("UICorner", G2L["14"]);
G2L["19"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.TextButton
G2L["1a"] = Instance.new("TextButton", G2L["14"]);
G2L["1a"]["BorderSizePixel"] = 0;
G2L["1a"]["TextSize"] = 14;
G2L["1a"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1a"]["BackgroundColor3"] = Color3.fromRGB(67, 67, 67);
G2L["1a"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["1a"]["ZIndex"] = 2;
G2L["1a"]["Size"] = UDim2.new(0, 87, 0, 29);
G2L["1a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1a"]["Text"] = [[Run]];
G2L["1a"]["Position"] = UDim2.new(0.75655, 0, 0.15121, 0);


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.TextButton.UICorner
G2L["1b"] = Instance.new("UICorner", G2L["1a"]);
G2L["1b"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.View
G2L["1c"] = Instance.new("ImageLabel", G2L["14"]);
G2L["1c"]["BorderSizePixel"] = 0;
G2L["1c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["1c"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["1c"]["Image"] = [[rbxassetid://104741126012073]];
G2L["1c"]["Size"] = UDim2.new(0, 34, 0, 26);
G2L["1c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1c"]["BackgroundTransparency"] = 1;
G2L["1c"]["Name"] = [[View]];
G2L["1c"]["Position"] = UDim2.new(0.15, 0, 0.76, 0);


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.View.UIAspectRatioConstraint
G2L["1d"] = Instance.new("UIAspectRatioConstraint", G2L["1c"]);



-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.View.TextLabel
G2L["1e"] = Instance.new("TextLabel", G2L["1c"]);
G2L["1e"]["TextWrapped"] = true;
G2L["1e"]["ZIndex"] = 2;
G2L["1e"]["BorderSizePixel"] = 0;
G2L["1e"]["TextSize"] = 20;
G2L["1e"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["1e"]["TextScaled"] = true;
G2L["1e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["1e"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1e"]["BackgroundTransparency"] = 1;
G2L["1e"]["Size"] = UDim2.new(-5.69334, 210, -0.53833, 30);
G2L["1e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1e"]["Text"] = [[1million]];
G2L["1e"]["Position"] = UDim2.new(1.23488, 0, 0.19219, 0);


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.Copy
G2L["1f"] = Instance.new("ImageLabel", G2L["14"]);
G2L["1f"]["BorderSizePixel"] = 0;
G2L["1f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["1f"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["1f"]["Image"] = [[rbxassetid://86138545569367]];
G2L["1f"]["Size"] = UDim2.new(0, 34, 0, 26);
G2L["1f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1f"]["BackgroundTransparency"] = 1;
G2L["1f"]["Name"] = [[Copy]];
G2L["1f"]["Position"] = UDim2.new(0.39, 0, 0.76, 0);


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.Copy.UIAspectRatioConstraint
G2L["20"] = Instance.new("UIAspectRatioConstraint", G2L["1f"]);



-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.Copy.TextLabel
G2L["21"] = Instance.new("TextLabel", G2L["1f"]);
G2L["21"]["TextWrapped"] = true;
G2L["21"]["ZIndex"] = 2;
G2L["21"]["BorderSizePixel"] = 0;
G2L["21"]["TextSize"] = 20;
G2L["21"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["21"]["TextScaled"] = true;
G2L["21"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["21"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["21"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["21"]["BackgroundTransparency"] = 1;
G2L["21"]["Size"] = UDim2.new(-4.9395, 210, -0.53833, 30);
G2L["21"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["21"]["Text"] = [[ClickToCopy]];
G2L["21"]["Position"] = UDim2.new(1.23488, 0, 0.19219, 0);


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.Copy.TextButton
G2L["22"] = Instance.new("TextButton", G2L["1f"]);
G2L["22"]["BorderSizePixel"] = 0;
G2L["22"]["TextTransparency"] = 1;
G2L["22"]["TextSize"] = 14;
G2L["22"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["22"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["22"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["22"]["BackgroundTransparency"] = 1;
G2L["22"]["Size"] = UDim2.new(0, 76, 0, 21);
G2L["22"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["22"]["Position"] = UDim2.new(-0, 0, 0, 0);


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.COntainsKEy
G2L["23"] = Instance.new("ImageLabel", G2L["14"]);
G2L["23"]["BorderSizePixel"] = 0;
G2L["23"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["23"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["23"]["Image"] = [[rbxassetid://81864026272064]];
G2L["23"]["Size"] = UDim2.new(0, 34, 0, 26);
G2L["23"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["23"]["BackgroundTransparency"] = 1;
G2L["23"]["Name"] = [[COntainsKEy]];
G2L["23"]["Position"] = UDim2.new(0.68, 0, 0.76, 0);


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.COntainsKEy.UIAspectRatioConstraint
G2L["24"] = Instance.new("UIAspectRatioConstraint", G2L["23"]);



-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.COntainsKEy.TextLabel
G2L["25"] = Instance.new("TextLabel", G2L["23"]);
G2L["25"]["TextWrapped"] = true;
G2L["25"]["ZIndex"] = 2;
G2L["25"]["BorderSizePixel"] = 0;
G2L["25"]["TextSize"] = 20;
G2L["25"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["25"]["TextScaled"] = true;
G2L["25"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["25"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["25"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["25"]["BackgroundTransparency"] = 1;
G2L["25"]["Size"] = UDim2.new(-4.75641, 210, -0.53833, 30);
G2L["25"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["25"]["Text"] = [[ClickToCopy]];
G2L["25"]["Position"] = UDim2.new(1.23488, 0, 0.19219, 0);


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.COntainsKEy.TextButton
G2L["26"] = Instance.new("TextButton", G2L["23"]);
G2L["26"]["BorderSizePixel"] = 0;
G2L["26"]["TextTransparency"] = 1;
G2L["26"]["TextSize"] = 14;
G2L["26"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["26"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["26"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["26"]["BackgroundTransparency"] = 1;
G2L["26"]["Size"] = UDim2.new(0, 76, 0, 21);
G2L["26"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["26"]["Position"] = UDim2.new(-0, 0, 0, 0);


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.Verify
G2L["27"] = Instance.new("ImageLabel", G2L["14"]);
G2L["27"]["BorderSizePixel"] = 0;
G2L["27"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["27"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["27"]["Image"] = [[rbxassetid://106324515607448]];
G2L["27"]["Size"] = UDim2.new(0, 34, 0, 26);
G2L["27"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["27"]["BackgroundTransparency"] = 1;
G2L["27"]["Name"] = [[Verify]];
G2L["27"]["Position"] = UDim2.new(0.15194, 0, 0.535, 0);


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.Verify.UIAspectRatioConstraint
G2L["28"] = Instance.new("UIAspectRatioConstraint", G2L["27"]);



-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.Verify.TextLabel
G2L["29"] = Instance.new("TextLabel", G2L["27"]);
G2L["29"]["TextWrapped"] = true;
G2L["29"]["ZIndex"] = 2;
G2L["29"]["BorderSizePixel"] = 0;
G2L["29"]["TextSize"] = 20;
G2L["29"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["29"]["TextScaled"] = true;
G2L["29"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["29"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["29"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["29"]["BackgroundTransparency"] = 1;
G2L["29"]["Size"] = UDim2.new(-4.98053, 210, -0.53833, 30);
G2L["29"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["29"]["Text"] = [[ClickToCopy]];
G2L["29"]["Position"] = UDim2.new(1.23488, 0, 0.19219, 0);


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.Verify.TextButton
G2L["2a"] = Instance.new("TextButton", G2L["27"]);
G2L["2a"]["BorderSizePixel"] = 0;
G2L["2a"]["TextTransparency"] = 1;
G2L["2a"]["TextSize"] = 14;
G2L["2a"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2a"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["2a"]["BackgroundTransparency"] = 1;
G2L["2a"]["Size"] = UDim2.new(0, 76, 0, 21);
G2L["2a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2a"]["Position"] = UDim2.new(-0, 0, 0, 0);


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.Place
G2L["2b"] = Instance.new("ImageLabel", G2L["14"]);
G2L["2b"]["BorderSizePixel"] = 0;
G2L["2b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["2b"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["2b"]["Image"] = [[rbxassetid://76183981184625]];
G2L["2b"]["Size"] = UDim2.new(0, 34, 0, 26);
G2L["2b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2b"]["BackgroundTransparency"] = 1;
G2L["2b"]["Name"] = [[Place]];
G2L["2b"]["Position"] = UDim2.new(0.4551, 0, 0.54333, 0);


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.Place.UIAspectRatioConstraint
G2L["2c"] = Instance.new("UIAspectRatioConstraint", G2L["2b"]);



-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.Place.TextLabel
G2L["2d"] = Instance.new("TextLabel", G2L["2b"]);
G2L["2d"]["TextWrapped"] = true;
G2L["2d"]["ZIndex"] = 2;
G2L["2d"]["BorderSizePixel"] = 0;
G2L["2d"]["TextSize"] = 20;
G2L["2d"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["2d"]["TextScaled"] = true;
G2L["2d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["2d"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2d"]["BackgroundTransparency"] = 1;
G2L["2d"]["Size"] = UDim2.new(-4.26692, 210, -0.53833, 30);
G2L["2d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2d"]["Text"] = [[ClickToCopy]];
G2L["2d"]["Position"] = UDim2.new(1.23488, 0, 0.19219, 0);


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.Place.TextButton
G2L["2e"] = Instance.new("TextButton", G2L["2b"]);
G2L["2e"]["BorderSizePixel"] = 0;
G2L["2e"]["TextTransparency"] = 1;
G2L["2e"]["TextSize"] = 14;
G2L["2e"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["2e"]["BackgroundTransparency"] = 1;
G2L["2e"]["Size"] = UDim2.new(0, 76, 0, 21);
G2L["2e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2e"]["Position"] = UDim2.new(-0, 0, 0, 0);


-- StarterGui.ScreenGui.SuperDuber.ScrollingFrame.Example.Count
G2L["2f"] = Instance.new("TextLabel", G2L["14"]);
G2L["2f"]["BorderSizePixel"] = 0;
G2L["2f"]["TextSize"] = 28;
G2L["2f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["2f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2f"]["BackgroundTransparency"] = 1;
G2L["2f"]["Size"] = UDim2.new(0, 41, 0, 32);
G2L["2f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2f"]["Text"] = [[1]];
G2L["2f"]["Name"] = [[Count]];


-- StarterGui.ScreenGui.SuperDuber.UICorner
G2L["30"] = Instance.new("UICorner", G2L["2"]);
G2L["30"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.SuperDuber.Normal
G2L["31"] = Instance.new("TextButton", G2L["2"]);
G2L["31"]["BorderSizePixel"] = 0;
G2L["31"]["TextSize"] = 14;
G2L["31"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["31"]["BackgroundColor3"] = Color3.fromRGB(67, 67, 67);
G2L["31"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["31"]["ZIndex"] = 2;
G2L["31"]["Size"] = UDim2.new(0, 60, 0.02, 16);
G2L["31"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["31"]["Text"] = [[NormalCore]];
G2L["31"]["Name"] = [[Normal]];
G2L["31"]["Position"] = UDim2.new(0.04766, 0, 0.03499, 0);


-- StarterGui.ScreenGui.SuperDuber.Normal.UICorner
G2L["32"] = Instance.new("UICorner", G2L["31"]);
G2L["32"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.SuperDuber.Normal.UIStroke
G2L["33"] = Instance.new("UIStroke", G2L["31"]);
G2L["33"]["Transparency"] = 0.38;
G2L["33"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["33"]["Thickness"] = 1.8;
G2L["33"]["Color"] = Color3.fromRGB(158, 158, 158);


-- StarterGui.ScreenGui.SuperDuber.Normal.UIStroke.UIGradient
G2L["34"] = Instance.new("UIGradient", G2L["33"]);
G2L["34"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(0.501, 1),NumberSequenceKeypoint.new(1.000, 0)};


-- StarterGui.ScreenGui.SuperDuber.Normal.UIStroke.UIGradient.LocalScript
G2L["35"] = Instance.new("LocalScript", G2L["34"]);



-- StarterGui.ScreenGui.SuperDuber.UIStroke
G2L["36"] = Instance.new("UIStroke", G2L["2"]);
G2L["36"]["Transparency"] = 0.38;
G2L["36"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["36"]["Thickness"] = 1.8;
G2L["36"]["Color"] = Color3.fromRGB(158, 158, 158);


-- StarterGui.ScreenGui.SuperDuber.UIStroke.UIGradient
G2L["37"] = Instance.new("UIGradient", G2L["36"]);
G2L["37"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(0.501, 1),NumberSequenceKeypoint.new(1.000, 0)};


-- StarterGui.ScreenGui.SuperDuber.UIStroke.UIGradient.LocalScript
G2L["38"] = Instance.new("LocalScript", G2L["37"]);



-- StarterGui.ScreenGui.SuperDuber.CuteCore
G2L["39"] = Instance.new("TextButton", G2L["2"]);
G2L["39"]["BorderSizePixel"] = 0;
G2L["39"]["TextSize"] = 14;
G2L["39"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["39"]["BackgroundColor3"] = Color3.fromRGB(67, 67, 67);
G2L["39"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["39"]["ZIndex"] = 2;
G2L["39"]["Size"] = UDim2.new(0, 60, 0.02, 16);
G2L["39"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["39"]["Text"] = [[CuteCore]];
G2L["39"]["Name"] = [[CuteCore]];
G2L["39"]["Position"] = UDim2.new(0.19766, 0, 0.03499, 0);


-- StarterGui.ScreenGui.SuperDuber.CuteCore.UICorner
G2L["3a"] = Instance.new("UICorner", G2L["39"]);
G2L["3a"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.SuperDuber.CuteCore.UIStroke
G2L["3b"] = Instance.new("UIStroke", G2L["39"]);
G2L["3b"]["Transparency"] = 0.38;
G2L["3b"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["3b"]["Thickness"] = 1.8;
G2L["3b"]["Color"] = Color3.fromRGB(158, 158, 158);


-- StarterGui.ScreenGui.SuperDuber.CuteCore.UIStroke.UIGradient
G2L["3c"] = Instance.new("UIGradient", G2L["3b"]);
G2L["3c"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(0.501, 1),NumberSequenceKeypoint.new(1.000, 0)};


-- StarterGui.ScreenGui.SuperDuber.CuteCore.UIStroke.UIGradient.LocalScript
G2L["3d"] = Instance.new("LocalScript", G2L["3c"]);



-- StarterGui.ScreenGui.SuperDuber.ann
G2L["3e"] = Instance.new("ImageLabel", G2L["2"]);
G2L["3e"]["BorderSizePixel"] = 0;
G2L["3e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3e"]["ImageTransparency"] = 0.75;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["3e"]["Image"] = [[rbxassetid://1878425826]];
G2L["3e"]["Size"] = UDim2.new(0, 450, 0, 291);
G2L["3e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3e"]["BackgroundTransparency"] = 1;
G2L["3e"]["Name"] = [[ann]];


-- StarterGui.ScreenGui.SuperDuber.ann.UICorner
G2L["3f"] = Instance.new("UICorner", G2L["3e"]);
G2L["3f"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.SuperDuber.TextLabel
G2L["40"] = Instance.new("TextLabel", G2L["2"]);
G2L["40"]["ZIndex"] = 2;
G2L["40"]["BorderSizePixel"] = 0;
G2L["40"]["TextSize"] = 13;
G2L["40"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["40"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["40"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["40"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["40"]["BackgroundTransparency"] = 1;
G2L["40"]["Size"] = UDim2.new(0, 108, 0, 25);
G2L["40"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["40"]["Text"] = [[by OutMoon and DreamyDolan2]];
G2L["40"]["Position"] = UDim2.new(0.04889, 0, 0.89003, 0);


-- StarterGui.ScreenGui.SuperDuber.super
G2L["41"] = Instance.new("ImageLabel", G2L["2"]);
G2L["41"]["BorderSizePixel"] = 0;
G2L["41"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["41"]["ImageTransparency"] = 0.39;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["41"]["Image"] = [[rbxassetid://10286206897]];
G2L["41"]["Size"] = UDim2.new(0, 450, 0, 291);
G2L["41"]["Visible"] = false;
G2L["41"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["41"]["BackgroundTransparency"] = 1;
G2L["41"]["Name"] = [[super]];


-- StarterGui.ScreenGui.SuperDuber.super.UICorner
G2L["42"] = Instance.new("UICorner", G2L["41"]);
G2L["42"]["CornerRadius"] = UDim.new(0, 25);


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

				if info.key == false then
					holder.COntainsKEy.TextLabel.Text = " Dont Contains Key!!"
				elseif info.key == true then
					holder.COntainsKEy.TextLabel.Text = "Contains Key!!"
				end

				if info.verified == false then
					holder.Verify.TextLabel.Text = "Not Verified!"
				elseif info.verified == true then
					holder.Verify.TextLabel.Text = "Verified!"
				end


				local countLabel = holder:FindFirstChild("Count")
				if countLabel and countLabel:IsA("TextLabel") then
					countLabel.Text = tostring(i)
				end

				holder.Place.TextLabel.Text = tostring(info.game._id)
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
					imageLabel.Image = "rbxassetid://"..tostring(info.imageUrl)
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
-- StarterGui.ScreenGui.SuperDuber.LocalScript
local function C_5()
	local script = G2L["5"];
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
task.spawn(C_5);
-- StarterGui.ScreenGui.SuperDuber.LocalScript
local function C_6()
	local script = G2L["6"];
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
task.spawn(C_6);
-- StarterGui.ScreenGui.SuperDuber.LocalScript
local function C_8()
	local script = G2L["8"];
	local chat = game:GetService("Chat")
	local char = game.Players.LocalPlayer.Character

	chat:Chat(char, "ElysianHub V3.5 beta loaded for "..game.Players.LocalPlayer.Name.." !!", Enum.ChatColor.White)
end;
task.spawn(C_8);
-- StarterGui.ScreenGui.SuperDuber.TextBox.UIStroke.UIGradient.LocalScript
local function C_d()
	local script = G2L["d"];
	local speed = 5

	while true do
		wait(0.05)
		script.Parent.Rotation += speed
	end
end;
task.spawn(C_d);
-- StarterGui.ScreenGui.SuperDuber.Normal.UIStroke.UIGradient.LocalScript
local function C_35()
	local script = G2L["35"];
	local speed = 5

	while true do
		wait(0.05)
		script.Parent.Rotation += speed
	end
end;
task.spawn(C_35);
-- StarterGui.ScreenGui.SuperDuber.UIStroke.UIGradient.LocalScript
local function C_38()
	local script = G2L["38"];
	local speed = 5

	while true do
		wait(0.05)
		script.Parent.Rotation += speed
	end
end;
task.spawn(C_38);
-- StarterGui.ScreenGui.SuperDuber.CuteCore.UIStroke.UIGradient.LocalScript
local function C_3d()
	local script = G2L["3d"];
	local speed = 5

	while true do
		wait(0.05)
		script.Parent.Rotation += speed
	end
end;
task.spawn(C_3d);

return G2L["1"], require;
