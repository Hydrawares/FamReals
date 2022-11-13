local Lib = loadstring(game:HttpGet("https://raw.githubusercontent.com/laagginq/ui-libraries/main/coastified/src.lua"))()
local Window = Lib:Window("Reality Fam", "Donate here", Enum.KeyCode.RightShift)
local Test = Window:Tab("$$$")

Test:Toggle('Enabled',function(state)
    print(state)
end)


Test:Slider('how much you wanna donate?',1,1000,75,function(Value)
    print(Value)
end)

Test:Colorpicker("Color",Color3.fromRGB(0,0,0), function(color)
    print(color)
end)

Test:Dropdown("Part",{'Head',"UpperTorso","HumanoidRootPart","LowerTorso"}, function(objective)
    print(objective)
end)
