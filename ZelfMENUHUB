local Mercury = loadstring(game:HttpGet("https://raw.githubusercontent.com/deeeity/mercury-lib/master/src.lua"))()

function getSpins()
	local spin = game:GetService("ReplicatedStorage").Events.SpinsAdd
	while wait(.2) do
		spin:FireServer()
    end
end

local GUI = Mercury:Create{
    Name = "Zelf MENU",
    Size = UDim2.fromOffset(600, 400),
    Theme = Mercury.Themes.Dark,
    Link = "https://github.com/deeeity/mercury-lib"
}

local Tab = GUI:Tab{
	Name = "Clicker Simulator",
	Icon = "rbxassetid://8569322835"
}

Tab:Button{
	Name = "Get spins",
	Description = "generate infinity spins - zelfyq",
	Callback = function()
		getSpins()
end
}
