local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("สคริปแมพบ้านนาByแอดหยงแดง", "DarkTheme")
local Tab = Window:NewTab("รวมทุกฟังชั่นกุขี้เกียจทำ")
local Section = Tab:NewSection("ฟังชั่นวาป")
Section:NewButton("วาปเข้าโรงบาล", "ButtonInfo", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(186.882812, 127.402458, 45739.2969, 0.992393494, -2.87876532e-08, -0.123106249, 2.03136512e-08, 1, -7.00900102e-08, 0.123106249, 6.70561349e-08, 0.992393494)
end)
Section:NewButton("วาปมาจุดเกิด", "ButtonInfo", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-195.002747, 69.1603775, 96.9073868, -0.953188002, -5.5628826e-09, 0.302378327, -3.30847549e-09, 1, 7.96777844e-09, -0.302378327, 6.59437882e-09, -0.953188002)
end)
Section:NewKeybind("วาปไปโรงบาลแบบปุ่มลัด", "KeybindInfo", Enum.KeyCode.G, function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(186.882812, 127.402458, 45739.2969, 0.992393494, -2.87876532e-08, -0.123106249, 2.03136512e-08, 1, -7.00900102e-08, 0.123106249, 6.70561349e-08, 0.992393494)
end)
Section:NewKeybind("วาปไปจุดเกิดแบบลัด", "KeybindInfo", Enum.KeyCode.Q, function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-195.002747, 69.1603775, 96.9073868, -0.953188002, -5.5628826e-09, 0.302378327, -3.30847549e-09, 1, 7.96777844e-09, -0.302378327, 6.59437882e-09, -0.953188002)
end)
Section:NewKeybind("วาปบ้าน", "KeybindInfo", Enum.KeyCode.H, function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(113.062019, 69.0677414, 334.079132, 0.0880503282, 1.2089314e-09, 0.996116042, -5.92810201e-09, 1, -6.89638568e-10, -0.996116042, -5.84435478e-09, 0.0880503282)
end)
Section:NewKeybind("วาปหนี", "KeybindInfo", Enum.KeyCode.T, function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-691.293579, 218.294174, -179.934357, -0.2506001, -1.25589832e-08, -0.968090713, -4.96907582e-08, 1, -1.099833e-10, 0.968090713, 4.80775988e-08, -0.2506001)
end)
local Section = Tab:NewSection("ฟังชั่นpvp")
Section:NewButton("ล็อคเป้ายิงคาเครื่องบินได้", "ButtonInfo", function()
    loadstring(game:HttpGet('https://rentry.co/forkoritothegoat/raw'))()
end)
Section:NewButton("ฟังชั่นลอย", "ButtonInfo", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/XNEOFF/FlyGuiV3/main/FlyGuiV3.txt"))()
end)
Section:NewButton("สคริปespมองชื่อไม่คอ่ยดีเท่าไหร่อันเก่ารันไม่ติด", "ButtonInfo", function()
    --- Tut
 
local esp_settings = { ---- table for esp settings 
    textsize = 8,
    colour = 255,255,255
}
 
local gui = Instance.new("BillboardGui")
local esp = Instance.new("TextLabel",gui) ---- new instances to make the billboard gui and the textlabel
 
 
 
gui.Name = "Cracked esp"; ---- properties of the esp
gui.ResetOnSpawn = false
gui.AlwaysOnTop = true;
gui.LightInfluence = 0;
gui.Size = UDim2.new(1.75, 0, 1.75, 0);
esp.BackgroundColor3 = Color3.fromRGB(255, 255, 255);
esp.Text = ""
esp.Size = UDim2.new(0.0001, 0.00001, 0.0001, 0.00001);
esp.BorderSizePixel = 4;
esp.BorderColor3 = Color3.new(esp_settings.colour)
esp.BorderSizePixel = 0
esp.Font = "GothamSemibold"
esp.TextSize = esp_settings.textsize
esp.TextColor3 = Color3.fromRGB(esp_settings.colour) -- text colour
 
game:GetService("RunService").RenderStepped:Connect(function() ---- loops faster than a while loop :)
    for i,v in pairs (game:GetService("Players"):GetPlayers()) do
        if v ~= game:GetService("Players").LocalPlayer and v.Character.Head:FindFirstChild("Cracked esp")==nil  then -- craeting checks for team check, local player etc
            esp.Text = "{"..v.Name.."}"
            gui:Clone().Parent = v.Character.Head
    end
end
end)
end)
Section:NewButton("วาปหาคน", "ButtonInfo", function()
    loadstring(game:HttpGet("https://gist.githubusercontent.com/DagerFild/b4776075a0d26ef04394133ee6bd2081/raw/0ed51ac94057d2d9a9f00e1b037b9011c76ca54a/tpGUI", true))()
end)
Section:NewButton("มองจอคนอื่น(ส่องไมค์)", "ButtonInfo", function()
    local runDummyScript = function(f,scri)
local oldenv = getfenv(f)
local newenv = setmetatable({}, {
__index = function(_, k)
if k:lower() == 'script' then
return scri
else
return oldenv[k]
end
end
})
setfenv(f, newenv)
ypcall(function() f() end)
end
cors = {}
mas = Instance.new("Model",game:GetService("Lighting")) 
mas.Name = "CompiledModel"
o1 = Instance.new("ScreenGui")
o2 = Instance.new("Frame")
o3 = Instance.new("TextButton")
o4 = Instance.new("TextButton")
o5 = Instance.new("TextLabel")
o6 = Instance.new("ImageButton")
o7 = Instance.new("LocalScript")
o1.Name = "SpectateGui"
o1.Parent = mas
o2.Name = "Bar"
o2.Parent = o1
o2.Position = UDim2.new(-1,-100,0.87999999523163,-50)
o2.Size = UDim2.new(0,200,0,50)
o2.Position = UDim2.new(-1,-100,0.87999999523163,-50)
o2.BackgroundColor3 = Color3.new(0, 0, 0)
o2.BackgroundTransparency = 0.20000000298023
o2.BorderSizePixel = 5
o3.Name = "Previous"
o3.Parent = o2
o3.Size = UDim2.new(0.25,0,1,0)
o3.Text = "<"
o3.BackgroundColor3 = Color3.new(0.52549, 0.52549, 0.52549)
o3.BorderColor3 = Color3.new(0.509804, 0.796079, 1)
o3.BorderSizePixel = 0
o3.Font = Enum.Font.SourceSans
o3.FontSize = Enum.FontSize.Size48
o3.TextColor3 = Color3.new(1, 1, 1)
o4.Name = "Next"
o4.Parent = o2
o4.Position = UDim2.new(1,0,0,0)
o4.Size = UDim2.new(-0.25,0,1,0)
o4.Text = ">"
o4.Position = UDim2.new(1,0,0,0)
o4.BackgroundColor3 = Color3.new(0.52549, 0.52549, 0.52549)
o4.BorderColor3 = Color3.new(0.509804, 0.796079, 1)
o4.BorderSizePixel = 0
o4.Font = Enum.Font.SourceSans
o4.FontSize = Enum.FontSize.Size48
o4.TextColor3 = Color3.new(1, 1, 1)
o5.Name = "Title"
o5.Parent = o2
o5.Position = UDim2.new(0.27500000596046,0,0,0)
o5.Size = UDim2.new(0.44999998807907,0,1,0)
o5.Text = ""
o5.Position = UDim2.new(0.27500000596046,0,0,0)
o5.BackgroundColor3 = Color3.new(1, 1, 1)
o5.BackgroundTransparency = 1
o5.Font = Enum.Font.SourceSans
o5.FontSize = Enum.FontSize.Size14
o5.TextColor3 = Color3.new(1, 1, 1)
o5.TextScaled = true
o5.TextWrapped = true
o6.Name = "Button"
o6.Parent = o1
o6.Position = UDim2.new(0,0,0.5,-25)
o6.Size = UDim2.new(0,50,0,50)
o6.Position = UDim2.new(0,0,0.5,-25)
o6.BackgroundColor3 = Color3.new(1, 1, 1)
o6.BackgroundTransparency = 0.30000001192093
o6.BorderSizePixel = 5
o6.Image = "http://www.roblox.com/asset/?id=176106970"
o7.Parent = o1
table.insert(cors,coroutine.create(function()
wait()
runDummyScript(function()

cam = game.Workspace.CurrentCamera

local bar = script.Parent.Bar
local title = bar.Title
local prev = bar.Previous
local nex = bar.Next
local button = script.Parent.Button

function get()
	for _,v in pairs(game.Players:GetPlayers())do
		if v.Name == title.Text then
			return(_)
		end
	end
end


local debounce = false
button.MouseButton1Click:connect(function()
	if debounce == false then debounce = true
		bar:TweenPosition(UDim2.new(.5,-100,0.88,-50),"In","Linear",1,true)
		pcall(function()
				title.Text = game.Players:GetPlayerFromCharacter(cam.CameraSubject.Parent).Name
		end)
	elseif debounce == true then debounce = false
		pcall(function() cam.CameraSubject = game.Players.LocalPlayer.Character.Humanoid end)
			bar:TweenPosition(UDim2.new(-1,-100,0.88,-50),"In","Linear",1,true)
		end
end)

prev.MouseButton1Click:connect(function()
	wait(.1)
	local players = game.Players:GetPlayers()
	local num = get()
	if not pcall(function() 
		cam.CameraSubject = players[num-1].Character.Humanoid
		end) then
		cam.CameraSubject = players[#players].Character.Humanoid
	end
pcall(function()
				title.Text = game.Players:GetPlayerFromCharacter(cam.CameraSubject.Parent).Name
		end)
end)

nex.MouseButton1Click:connect(function()
	wait(.1)
	local players = game.Players:GetPlayers()
	local num = get()
	if not pcall(function() 
		cam.CameraSubject = players[num+1].Character.Humanoid
		end) then
		cam.CameraSubject = players[1].Character.Humanoid
	end
pcall(function()
				title.Text = game.Players:GetPlayerFromCharacter(cam.CameraSubject.Parent).Name
		end)
end)


end,o7)
end))
mas.Parent = workspace
mas:MakeJoints()
local mas1 = mas:GetChildren()
for i=1,#mas1 do
	mas1[i].Parent = game:GetService("Players").LocalPlayer.PlayerGui 
	ypcall(function() mas1[i]:MakeJoints() end)
end
mas:Destroy()
for i=1,#cors do
coroutine.resume(cors[i])
end

end)
Section:NewKeybind("ปุ่มปิดสคริป", "KeybindInfo", Enum.KeyCode.F, function()
	Library:ToggleUI()
end)
