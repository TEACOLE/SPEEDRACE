local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "TA X HUB", HidePremium = false, IntroText = "TA X HUB",SaveConfig = true, ConfigFolder = "OrionTest"})

local Tab = Window:MakeTab({
	Name = "Main",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})


local Section = Tab:AddSection({
	Name = "SPEED RACE"
})

OrionLib:MakeNotification({
	Name = "TA X HUB",
	Content = "Beta Script",
	Image = "rbxassetid://4483345998",
	Time = 8
})

    Tab:AddButton({
	Name = "AutoCilck",
	Callback = function()
      		while wait() do
   game:GetService("Players").LocalPlayer.PlayerGui.SCRIPTS.PunchV2.Function:FireServer("Click")
end
  	end    
})

    Tab:AddButton({
	Name = "Auto Rebirth",
	Callback = function()
      		while wait() do
       game:GetService("ReplicatedStorage").GameClient.Events.RemoteEvent.UpdateRebirth:FireServer()
end
  	end    
})



local Tab = Window:MakeTab({
	Name = "mics",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "ScriptV.1",
	Callback = function()
      		local Library = loadstring(game:HttpGet("https://pastebin.com/raw/vff1bQ9F"))()

local Window = Library.CreateLib("TA X HUB", "Midnight")
local Tab = Window:NewTab("Main")
local Section = Tab:NewSection("V.1")
Section:NewButton("auto click", "อย่าลืมกดก่อนอ้อโต้ฟาม", function()
    while wait() do
   game:GetService("Players").LocalPlayer.PlayerGui.SCRIPTS.PunchV2.Function:FireServer("Click")
end
end)

Section:NewButton("auto farm", "อย่าลืมเลือกผ่านก่อนเปิด", function()
   while wait() do
   game:GetService("ReplicatedStorage").GameClient.Events.RemoteEvent.AFKmodeEvent:FireServer()
end

 end)
 
 local Tab = Window:NewTab("Mic")
 local Section = Tab:NewSection("script speed race")
Section:NewButton("ScriptV.2", "อย่าลืมเลือกผ่านก่อนเปิด", function()
   
   local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "TA X HUB", HidePremium = false, IntroText = "TA X HUB",SaveConfig = true, ConfigFolder = "OrionTest"})

local Tab = Window:MakeTab({
	Name = "Main",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})


local Section = Tab:AddSection({
	Name = "SPEED RACE"
})

OrionLib:MakeNotification({
	Name = "TA X HUB",
	Content = "Beta Script",
	Image = "rbxassetid://4483345998",
	Time = 8
})

    Tab:AddButton({
	Name = "AutoCilck",
	Callback = function()
      		while wait() do
   game:GetService("Players").LocalPlayer.PlayerGui.SCRIPTS.PunchV2.Function:FireServer("Click")
end
  	end    
})

    Tab:AddButton({
	Name = "Auto Rebirth",
	Callback = function()
      		while wait() do
       game:GetService("ReplicatedStorage").GameClient.Events.RemoteEvent.UpdateRebirth:FireServer()
end
  	end    
})



local Tab = Window:MakeTab({
	Name = "mics",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "ScriptV.1",
	Callback = function()
      		local Library = loadstring(game:HttpGet("https://pastebin.com/raw/vff1bQ9F"))()

local Window = Library.CreateLib("TA X HUB", "Midnight")
local Tab = Window:NewTab("Main")
local Section = Tab:NewSection("V.1")
Section:NewButton("auto click", "อย่าลืมกดก่อนอ้อโต้ฟาม", function()
    while wait() do
   game:GetService("Players").LocalPlayer.PlayerGui.SCRIPTS.PunchV2.Function:FireServer("Click")
end
end)

Section:NewButton("auto farm", "อย่าลืมเลือกผ่านก่อนเปิด", function()
   while wait() do
   game:GetService("ReplicatedStorage").GameClient.Events.RemoteEvent.AFKmodeEvent:FireServer()
end

 end)
  	end    
})

 end)
  	end    
})
