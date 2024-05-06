pcall(function()
function CheckQuest()
        local Lv = game:GetService("Players").LocalPlayer.Data.Level.Value
            if Lv == 1 or Lv <= 9 then
                Mon = "Bandit [Lv. 5]"
                NameMon = "Bandit"
                LvQuest = 1
                NameQuest = "BanditQuest1"
                CFrameMon = CFrame.new(1038.2711181640625, 24.537282943725586, 1550.2586669921875)
            elseif Lv == 10 or Lv <= 14 then
                Mon = "Monkey [Lv. 14]"
                NameMon = "Monkey"
                LvQuest = 1
                NameQuest = "JungleQuest"
                CFrameMon = CFrame.new(-1443.7662353515625, 61.851966857910156, -47.555946350097656)
                elseif Lv == 15 or Lv <= 29 then
                Mon = "Gorilla [Lv. 20]"
                NameMon = "Gorilla"
                LvQuest = 2
                NameQuest = "JungleQuest"
                CFrameMon = CFrame.new(-1310.2041015625, 36.68962860107422, -503.99658203125)
  							elseif Lv == 30 or Lv <= 59 then
                Mon = "Pirate [Lv. 35]"
                NameMon = "Pirate"
                LvQuest = 1
                NameQuest = "BuggyQuest1"
                CFrameMon = CFrame.new(-1257.8212890625, 58.75202941894531, 3817.2724609375)
								elseif Lv == 60 or Lv <= 74 then
                Mon = "Desert Bandit [Lv. 60]"
                NameMon = "Desert Bandit"
                LvQuest = 1
                NameQuest = "DesertQuest"
                CFrameMon = CFrame.new(1055.29833984375, 52.41141128540039, 4489.96728515625)
								elseif Lv == 75 or Lv <= 89 then
                Mon = "Desert Officer [Lv. 70]"
                NameMon = "Desert Officer"
                LvQuest = 2
                NameQuest = "DesertQuest"
                CFrameMon = CFrame.new(1559.092041015625, 15.330206871032715, 4270.7451171875)
								elseif Lv == 90 or Lv <= 99 then
                Mon = "Snow Bandit [Lv. 90]"
                NameMon = "Snow Bandit"
                LvQuest = 1
                NameQuest = "SnowQuest"
                CFrameMon = CFrame.new(1349.8880615234375, 104.55516815185547, -1325.6455078125)
								elseif Lv == 100 or Lv <= 119 then
                Mon = "Snowman [Lv. 100]"
                NameMon = "Snowman"
                LvQuest = 2
                NameQuest = "SnowQuest"
                CFrameMon = CFrame.new(1219.2662353515625, 138.0118408203125, -1489.510986328125)
								elseif Lv == 120 or Lv <= 149 then
                Mon = "Chief Petty Officer [Lv. 120]"
                NameMon = "Chief Petty Officer"
                LvQuest = 1
                NameQuest = "MarineQuest2"
                CFrameMon = CFrame.new(-4759.033203125, 70.42005920410156, 4489.806640625)
								elseif Lv == 150 or Lv <= 174 then
                Mon = "Sky Bandit [Lv. 150]"
                NameMon = "Sky Bandit"
                LvQuest = 1
                NameQuest = "SkyQuest"
                CFrameMon = CFrame.new(-4987.26806640625, 278.0667724609375, -2871.459228515625)
								elseif Lv == 175 or Lv <= 189 then
                Mon = "Dark Master [Lv. 175]"
                NameMon = "Dark Master"
                LvQuest = 2
                NameQuest = "SkyQuest"
                CFrameMon = CFrame.new(-5246.5478515625, 388.6519470214844, -2262.514892578125)
								elseif Lv == 190 or Lv <= 209 then
                Mon = "Prisoner [Lv. 190]"
                NameMon = "Prisoner"
                LvQuest = 1
                NameQuest = "PrisonerQuest"
								CFrameMon = CFrame.new(5433.39307, 88.678093, 514.986877, 0.879988372, 0, -0.474995494, 0, 1, 0, 0.474995494, 0, 0.879988372)
								elseif Lv == 210 or Lv <= 249 then
                Mon = "Dangerous Prisoner [Lv. 210]"
                NameMon = "Dangerous Prisoner"
                LvQuest = 2
                NameQuest = "PrisonerQuest"
	              CFrameMon = CFrame.new(5433.39307, 88.678093, 514.986877, 0.879988372, 0, -0.474995494, 0, 1, 0, 0.474995494, 0, 0.879988372)
								elseif Lv == 254 or Lv <= 299 then
                Mon = "Toga Warrior [Lv. 250]"
                NameMon = "Toga Warrior"
                LvQuest = 1
                NameQuest = "ColosseumQuest"
	              CFrameMon = CFrame.new(-1779.97583, 44.6077499, -2736.35474, 0.984437346, 4.10396339e-08, 0.175734788, -3.62286876e-08, 1, -3.05844168e-08, -0.175734788, 2.3741821e-08, 0.984437346)
								elseif Lv == 300 or Lv <= 329 then
                Mon = "Military Soldier [Lv. 300]"
                NameMon = "Military Soldier"
                LvQuest = 1
                NameQuest = "MagmaQuest"
	              CFrameMon = CFrame.new(-5363.01123, 41.5056877, 8548.47266, -0.578253984, -3.29503091e-10, 0.815856814, 9.11209668e-08, 1, 6.498761e-08, -0.815856814, 1.11920997e-07, -0.578253984)
								elseif Lv == 330 or Lv <= 374 then
                Mon = "Military Spy [Lv. 325]"
                NameMon = "Military Spy"
                LvQuest = 2
                NameQuest = "MagmaQuest"
	              CFrameMon = CFrame.new(-5787.99023, 120.864456, 8762.25293, -0.188358366, -1.84706277e-08, 0.982100308, -1.23782129e-07, 1, -4.93306951e-09, -0.982100308, -1.22495649e-07, -0.188358366)
								elseif Lv == 375 or Lv <= 399 then
                Mon = "Fishman Warrior [Lv. 375]"
                NameMon = "Fishman Warrior"
                LvQuest = 1
                NameQuest = "FishmanQuest"
	              CFrameMon = CFrame.new(60946.6094, 48.6735229, 1525.91687, -0.0817126185, 8.90751153e-08, 0.996655822, 2.00889794e-08, 1, -8.77269599e-08, -0.996655822, 1.28533992e-08, -0.0817126185)
								elseif Lv == 400 or Lv <= 449 then
                Mon = "Fishman Commando [Lv. 400]"
                NameMon = "Fishman Commando"
                LvQuest = 2
                NameQuest = "FishmanQuest"
	              CFrameMon = CFrame.new(61855.4609375, 18.482818603515625, 1402.176025390625)
								elseif Lv == 450 or Lv <= 474 then
                Mon = "God's Guard [Lv. 450]"
                NameMon = "God's Guards"
                LvQuest = 1
                NameQuest = "SkyExp1Quest"
	              CFrameMon = CFrame.new(-4721.71436, 845.277161, -1954.20105)
								elseif Lv == 475 or Lv <= 524 then
                Mon = "Shanda [Lv. 475]"
                NameMon = "Shandas"
                LvQuest = 2
                NameQuest = "SkyExp1Quest"
	              CFrameMon = CFrame.new(-7658.2978515625, 5545.49169921875, -493.08270263671875)
								elseif Lv == 525 or Lv <= 549 then
                Mon = "Royal Squad [Lv. 525]"
                NameMon = "Royal Squad"
                LvQuest = 1
                NameQuest = "SkyExp2Quest"
	              CFrameMon = CFrame.new(-7667.400390625, 5606.876953125, -1459.8875732421875)
								elseif Lv == 550 or Lv <= 624 then
                Mon = "Royal Soldier [Lv. 550]"
                NameMon = "Royal Soldier"
                LvQuest = 2
                NameQuest = "SkyExp2Quest"
	              CFrameMon = CFrame.new(-7837.90185546875, 5622.2802734375, -1787.8131103515625)
								elseif Lv == 625 or Lv <= 649 then
                Mon = "Galley Pirate [Lv. 625]"
                NameMon = "Galley Pirate"
                LvQuest = 1
                NameQuest = "FountainQuest"
	              CFrameMon = CFrame.new(5259.81982, 37.3500175, 4050.0293, 0.087131381, 0, 0.996196866, 0, 1, 0, -0.996196866, 0, 0.087131381)
								elseif Lv == 650 or Lv <= 699 then
                Mon = "Galley Captain [Lv. 650]"
                NameMon = "Galley Captain"
                LvQuest = 2
                NameQuest = "FountainQuest"
	              CFrameMon = CFrame.new(5259.81982, 37.3500175, 4050.0293, 0.087131381, 0, 0.996196866, 0, 1, 0, -0.996196866, 0, 0.087131381)
			end
    end
end)
    local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/naypramx/Ui__Project/Script/XeNonUi", true))()
    library:CreateWatermark("Nexus HUB")
    local CenterHubNo1 = library:CreateWindow("Nexus HUB | BLOX FRUIT",Enum.KeyCode.M)
    local Tab = CenterHubNo1:CreateTab("Main")
    local AutoFarm = Tab:CreateSector("AutoFarm","Left")
    AutoFarm:AddLabel("AutoFarm Lv")
    Weapon = {}
    for i,v in pairs(game:GetService("Players").LocalPlayer.Backpack:GetChildren()) do
        if v:IsA"Tool" then
            table.insert(Weapon,v.Name)
    end
end
    local WE = AutoFarm:AddDropdown("Select Weapon",Weapon,"Select Weapon",false,function(t)
        _G.SelectWeapon = t
    end)
function Equip(ToolX)
    if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild(ToolX) then
        getgenv().Tol = game:GetService("Players").LocalPlayer.Backpack:FindFirstChild(ToolX)
        game.Players.LocalPlayer.Character.Humanoid:EquipTool(Tol)
    end
end
function click()
pcall(function()
local VirtualUser=game:service'VirtualUser'
		VirtualUser:CaptureController()
		VirtualUser:ClickButton1(Vector2.new(851, 158), game:GetService("Workspace").Camera.CFrame)
		end)
		end

 function TP(P)
	pcall(function()
   local Distance = (P.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
   local Speed = 350 -- ความเร็วของมึง
   tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
   tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = P})
   tween:Play()
 end)
		end
         AutoFarm:AddButton("ReSet Weapon",function()
        table.clear(Weapon)
        for i,v in pairs(game:GetService("Players").LocalPlayer.Backpack:GetChildren()) do
        if v:IsA"Tool" then
        WE:Add(v.Name)
        end
    end
end)

    AutoFarm:AddToggle("Start",true,function(t)
        _G.AutoFarm = t
				_G.BringMob = t
				_G.Usecode = t
				_G.fastattack = t
				_G.Usefastattack = t
				SuperhumanFull = t
				_G.Auto_Buy_Legendary_Sword = t
				Triple_A = t
    end)
		AutoFarm:AddToggle("Whitescreen",false,function(t)
				_G.White = t
		spawn(function()
 if _G.White then
        game:GetService("RunService"):Set3dRenderingEnabled(false)
    else
        game:GetService("RunService"):Set3dRenderingEnabled(true)
    end
	end)
		end)

local Stats = Tab:CreateSector("Stats","Reft")
Stats:AddLabel("Stats")
Stats:AddToggle("Auto Melee",false,function(t)
_G.Melee = t
while _G.Melee do wait(.1)
pcall(function()
game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AddPoint","Melee",Point)
end)
end
end)
Stats:AddToggle("Auto Defense",false,function(t)
_G.Defense = t
while _G.Defense do wait(.1)
pcall(function()
game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AddPoint","Defense",Point)
end)
end
end)
Stats:AddToggle("Auto Sword",false,function(t)
_G.Sword = t
while _G.Sword do wait(.1)
pcall(function()
game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AddPoint","Sword",Point)
end)
end
end)
Stats:AddToggle("Auto Gun",false,function(t)
_G.Gun = t
while _G.Gun do wait(.1)
pcall(function()
game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AddPoint","Gun",Point)
end)
end
end)
Stats:AddToggle("Auto Blox Fruit",false,function(t)
_G.Fruit = t
while _G.Fruit do wait(.1)
pcall(function()
game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AddPoint","Demon Fruit",Point)
end)
end
end)
Stats:AddSlider("Point",1,1,100,1,function(x)
Point = x
end)

    spawn(function()
    while wait() do
        if _G.BringMob then
            pcall(function()
            CheckQuest()
       for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
for x,y in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
if v.Name == Mon then
    if y.Name == Mon then
   v.HumanoidRootPart.CFrame = y.HumanoidRootPart.CFrame
   v.HumanoidRootPart.Size = Vector3.new(5,0,5)
   y.HumanoidRootPart.Size = Vector3.new(5,0,5)
   v.HumanoidRootPart.Transparency = 1
   v.HumanoidRootPart.CanCollide = false
   y.HumanoidRootPart.CanCollide = false
   v.Humanoid.WalkSpeed = 0
   y.Humanoid.WalkSpeed = 0
   v.Humanoid.JumpPower = 0
   y.Humanoid.JumpPower = 0
   if sethiddenproperty then
     sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
end
end
end
end
end
end)
end
end
end)


spawn(function()
    while wait() do
        if _G.AutoFarm then
            pcall(function()
            CheckQuest()
    if game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == false then
    TP(CFrameMon)
    if (CFrameMon.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 5 then
    wait(.15)
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StartQuest",NameQuest,LvQuest)
    end
    elseif game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == true then
        if string.find(game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text,NameMon) then
            for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                if v.Name == Mon and v:FindFirstChild("HumanoidRootPart") and v:FindFirstChild("Humanoid")   then
                    if v.Humanoid.Health > 0 then
                    repeat wait()
                        click()
                        Equip(_G.SelectWeapon)
                        HealthMin = v.Humanoid.MaxHealth * 90 / 100
                        Magma = (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
                        if Magma <= 230 then
                            if v.Humanoid.Health > HealthMin then
                                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,45,0)
                                else
                                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,45,0)
                            end
                        end
                            if v.Humanoid.Health > HealthMin then
                        Distance = (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude 
                        Speed = 400 
                        tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
                        tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,45,0)})
                        tween:Play() 
												else
                        Distance = (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude 
                        Speed = 400 
                        tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
                        tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,45,0)})
                        tween:Play()
                            end
                        v.HumanoidRootPart.Size = Vector3.new(5,0,5)
                        v.HumanoidRootPart.CanCaillde = false
                    until _G.AutoFarm == false or v.Humanoid.Health <= 0
                    if not string.find(game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text,NameMon) then
												local Lv = game:GetService("Players").LocalPlayer.Data.Level.Value
													if Lv <= Lv then
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AbandonQuest")
												end
                    if game.Players.LocalPlayer.Character.Humanoid.Health <= 0 then
                        _G.AutoFarm = false
                        wait(3)
                        _G.AutoFarm = true
                        end
                end
                end
        end
        end
end
					end
			end)
		end
	end
	end)

spawn(function()
		pcall(function()
    game:GetService("RunService").Heartbeat:Connect(function()
        if _G.AutoFarm then
        if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Humanoid") then
            setfflag("HumanoidParallelRemoveNoPhysics", "False")
            setfflag("HumanoidParallelRemoveNoPhysicsNoSimulate2", "False")
            game:GetService("Players").LocalPlayer.Character.Humanoid:ChangeState(11)
            end
        end
    end)
end)
	end)


spawn(function()
		while wait(.1) do
			if game.Players.LocalPlayer.PlayerGui.Main.HP.TextLabel.Text == "Health 100/100" and StatsBypass == "Bypassed" then
				StatsBypass = "NoBypassTP"
			end
			if _G.AutoFarm then 
				if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
					local args = {
						[1] = "Buso"
					}
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
				end
			end
			if AUTOHAKIObs then 
				if game:GetService("Players").LocalPlayer:FindFirstChild("PlayerGui") and game.Players.LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel") then
				else wait(1)
					game:service('VirtualUser'):CaptureController()
					game:service('VirtualUser'):SetKeyDown('0x65')
					wait(2)
					game:service('VirtualUser'):SetKeyUp('0x65')
				end
			end
		end
	end)


spawn(function()
		function UseCode(Text)
			game:GetService("ReplicatedStorage").Remotes.Redeem:InvokeServer(Text)
		end
		UseCode("SUB2GAMERROBOT_EXP1")
		UseCode("StrawHatMaine")
		UseCode("Sub2OfficialNoobie")
		UseCode("FUDD10")
		UseCode("BIGNEWS")
		UseCode("THEGREATACE")
		UseCode("SUB2NOOBMASTER123")
		UseCode("Sub2Daigrock")
		UseCode("Axiore")
		UseCode("TantaiGaming")
		UseCode("STRAWHATMAINE")
		UseCode("15B_BESTBROTHERS")
		UseCode("Sub2CaptainMaui")
		UseCode("DEVSCOOKING")
		UseCode("NOOB_REFUND")
		UseCode("SUB2GAMERROBOT_RESET1")
		UseCode("kittgaming")
		end)


local plr = game.Players.LocalPlayer

spawn(function()
	local CbFw = getupvalues(require(plr.PlayerScripts.CombatFramework))
	local CbFw2 = CbFw[2]
	local CameraShakerR = require(game.ReplicatedStorage.Util.CameraShaker)
	CameraShakerR:Stop()
	spawn(function()
		game:GetService("RunService").Stepped:Connect(function()
			pcall(function()
				CbFw2.activeController.hitboxMagnitude = 55
				if _G.Usefastattack then
					if _G.fastattack then
						if game.Players.LocalPlayer.Character:FindFirstChild("Weapon") then
							CbFw2.activeController.timeToNextAttack = 2
						elseif game.Players.LocalPlayer.Character:FindFirstChild("Weapon") then
							CbFw2.activeController.timeToNextAttack = 1
						else
							CbFw2.activeController.timeToNextAttack = 0
						end
						CbFw2.activeController.attacking = false
						CbFw2.activeController.increment = 2
						CbFw2.activeController.blocking = false
						CbFw2.activeController.timeToNextBlock = 0
						game.Players.LocalPlayer.Character.Humanoid.Sit = false	
					end
				end
			end)
		end)
	end)
	end)
	
spawn(function()
    game:GetService("RunService").RenderStepped:Connect(function()
			pcall(function()
				if _G.Usefastattack then
					if _G.fastattack then
						Click()
					end
				end
			end)
		end)
	end)



        local decalsyeeted = true -- Leaving this on makes games look shitty but the fps goes up by at least 20.
		local g = game
		local w = g.Workspace
		local l = g.Lighting
		local t = w.Terrain
		t.WaterWaveSize = 0
		t.WaterWaveSpeed = 0
		t.WaterReflectance = 0
		t.WaterTransparency = 0
		l.GlobalShadows = false
		l.FogEnd = 9e9
		l.Brightness = 0
		settings().Rendering.QualityLevel = "Level01"
		for i, v in pairs(g:GetDescendants()) do
			if v:IsA("Part") or v:IsA("Union") or v:IsA("CornerWedgePart") or v:IsA("TrussPart") then 
				v.Material = "Plastic"
				v.Reflectance = 0
			elseif v:IsA("Decal") or v:IsA("Texture") and decalsyeeted then
				v.Transparency = 1
			elseif v:IsA("ParticleEmitter") or v:IsA("Trail") then
				v.Lifetime = NumberRange.new(0)
			elseif v:IsA("Explosion") then
				v.BlastPressure = 1
				v.BlastRadius = 1
			elseif v:IsA("Fire") or v:IsA("SpotLight") or v:IsA("Smoke") or v:IsA("Sparkles") then
				v.Enabled = false
			elseif v:IsA("MeshPart") then
				v.Material = "Plastic"
				v.Reflectance = 0
				v.TextureID = 10385902758728957
			end
		end
		for i, e in pairs(l:GetChildren()) do
			if e:IsA("BlurEffect") or e:IsA("SunRaysEffect") or e:IsA("ColorCorrectionEffect") or e:IsA("BloomEffect") or e:IsA("DepthOfFieldEffect") then
				e.Enabled = false
			end
		end


        spawn(function()
            while wait() do
                AntiAutoClick:GetPropertyChangedSignal("Visible"):Connect(function()
                    if AntiAutoClick.Visible == true then
                        wait(0.1)
                        local Color
                        for i,v in pairs(TextMatch) do
                            if string.match(AntiAutoClick.TextFrame.ColorIndicator.Text,v) then
                                Color = v
                            end
                        end
                        for i,v in pairs(AntiAutoClick.Colors:GetChildren()) do
                            if v.Button.Text == Color:sub(1,1) then
                                firesignal(v.Button.MouseButton1Click)
                            end
                        end
                    end
                end) 
                LocalPlayer.Idled:connect(function()
                    VirtualUser:Button2Down(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
                    wait(1)
                    VirtualUser:Button2Up(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
                end)
            end
        end)


spawn(function()
		while wait(.25) do
			pcall(function()
			if Superhuman or SuperhumanFull and game.Players.LocalPlayer:FindFirstChild("WeaponAssetCache") then 
				if game.Players.LocalPlayer.Backpack:FindFirstChild("Combat") or game.Players.LocalPlayer.Character:FindFirstChild("Combat") then
					local args = {
						[1] = "BuyElectro"
					}
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
				end   
				if game.Players.LocalPlayer.Character:FindFirstChild("Superhuman") or game.Players.LocalPlayer.Backpack:FindFirstChild("Superhuman") then
					SelectToolWeapon = "Superhuman"
				end  
				if game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg").Level.Value <= 299  then
					SelectToolWeapon = "Black Leg"
				end
				if game.Players.LocalPlayer.Backpack:FindFirstChild("Electro") and game.Players.LocalPlayer.Backpack:FindFirstChild("Electro").Level.Value <= 299  then
					SelectToolWeapon = "Electro"
				end
				if game.Players.LocalPlayer.Backpack:FindFirstChild("Fishman Karate") and game.Players.LocalPlayer.Backpack:FindFirstChild("Fishman Karate").Level.Value <= 299  then
					SelectToolWeapon = "Fishman Karate"
				end
				if game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Claw") and game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Claw").Level.Value <= 299  then
					SelectToolWeapon = "Dragon Claw"
				end
				if game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg").Level.Value >= 300  then
					local args = {
						[1] = "BuyFishmanKarate"
					}
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
				end
				if game.Players.LocalPlayer.Character:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Character:FindFirstChild("Black Leg").Level.Value >= 300  then
					local args = {
						[1] = "BuyFishmanKarate"
					}
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
				end
				if game.Players.LocalPlayer.Backpack:FindFirstChild("Electro") and game.Players.LocalPlayer.Backpack:FindFirstChild("Electro").Level.Value >= 100  then
					local args = {
						[1] = "BuyBlackLeg"
					}
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
				end
				if game.Players.LocalPlayer.Character:FindFirstChild("Electro") and game.Players.LocalPlayer.Character:FindFirstChild("Electro").Level.Value >= 300  then
					local args = {
						[1] = "BuyBlackLeg"
					}
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
				end
				if game.Players.LocalPlayer.Backpack:FindFirstChild("Fishman Karate") and game.Players.LocalPlayer.Backpack:FindFirstChild("Fishman Karate").Level.Value >= 300  then
					if SuperhumanFull and game.Players.LocalPlayer.Data.Fragments.Value < 1500 then
						if game.Players.LocalPlayer.Data.Level.Value > 1100 then
							RaidsSelected = "Flame"
							AutoRaids = true
							RaidsArua = true
						end
					else
						AutoRaids = false
						RaidsArua = false
						local args = {
							[1] = "BlackbeardReward",
							[2] = "DragonClaw",
							[3] = "2"
						}
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
					end
				end
				if game.Players.LocalPlayer.Character:FindFirstChild("Fishman Karate") and game.Players.LocalPlayer.Character:FindFirstChild("Fishman Karate").Level.Value >= 300  then
					if SuperhumanFull and game.Players.LocalPlayer.Data.Fragments.Value < 1500 then
						if game.Players.LocalPlayer.Data.Level.Value > 1100 then
							RaidsSelected = "Flame"
							AutoRaids = true
							RaidsArua = true
						end
					else
						AutoRaids = false
						RaidsArua = false
						local args = {
							[1] = "BlackbeardReward",
							[2] = "DragonClaw",
							[3] = "2"
						}
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
					end
				end
				if game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Claw") and game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Claw").Level.Value >= 300  then
					local args = {
						[1] = "BuySuperhuman"
					}
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
				end
				if game.Players.LocalPlayer.Character:FindFirstChild("Dragon Claw") and game.Players.LocalPlayer.Character:FindFirstChild("Dragon Claw").Level.Value >= 300  then
					local args = {
						[1] = "BuySuperhuman"
					}
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
				end 
			end
					end)
	end
end)

spawn(function()
		while wait() do
			if _G.AutoFarm then
game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
end
end
	end)


-- ❌
-- ✅
local AutoFarm = Tab:CreateSector("AutoFarm","Left")
local Kill_Elite_Hunter_ST = AutoFarm:AddLabel("Kill Elite Hunter : 0")
local Kill_Cake_Monster_ST = AutoFarm:AddLabel("Kill Cake Monster : 0/500")
local Bartlio_ST = AutoFarm:AddLabel("❌ : Quest Bartlio")
local Open_Don_Swan_ST = AutoFarm:AddLabel("❌ : Quest Open Don Swan")
local Phoenix_Awaken_ST = AutoFarm:AddLabel("❌ : Quest Phoenix Awaken")
local Observation_Haki_ST = AutoFarm:AddLabel("❌ : Quest Observation Haki")
local Observation_Haki_V2_ST = AutoFarm:AddLabel("❌ : Quest Observation Haki V2")
AutoFarm:AddLabel("Status Legendary Sword")
local ST_Shisui = AutoFarm:AddLabel("❌ : Shisui")
local ST_Saddi = AutoFarm:AddLabel("❌ : Saddi")
local ST_Wando = AutoFarm:AddLabel("❌ : Wando")
function CheckStatus()
	Kill_Elite_Hunter_ST:Set("Kill Elite Hunter : "..tostring(game.ReplicatedStorage.Remotes.CommF_:InvokeServer("EliteHunter", "Progress")))
	local OP = game.ReplicatedStorage.Remotes.CommF_:InvokeServer("CakePrinceSpawner")
    local Lp = tonumber(string.match(tostring(OP), "%d+"))
	Kill_Cake_Monster_ST:Set("Kill Cake Monster : "..tostring(Lp).."/500")
	if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("TalkTrevor","1") == 0 then
		Open_Don_Swan_ST:Set("✅ : Open Don Swan Quest")
	end
	if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BartiloQuestProgress","Bartilo") == 3 then
		Bartlio_ST:Set("✅ : Bartilo Quest") 
	end
	if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SickScientist","Heal") == 1 then
		Phoenix_Awaken_ST:Set('✅ : Quest Phoenix Awaken')
	end
	if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("ProQuestProgress","SickMan") == 0 then
		Observation_Haki_ST:Set('✅ : Quest Observation Haki')
	end
	if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("CitizenQuestProgress","Citizen") == 3 then
		Observation_Haki_V2_ST:Set('✅ : Quest Observation Haki V2')
	end

	for i,x in pairs(I_W) do
		v = {
			Name = x["Name"]
		}
		if v.Name == "Shisui" then
			ST_Shisui:Set("✅ : Shisui")
		end
		if v.Name == "Wando" then
			ST_Wando:Set("✅ : Wando")
		end
		if v.Name == "Saddi" then
			ST_Saddi:Set("✅ : Saddi")
		end
	end
	for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
		if v:IsA("Tool") then
			if v.Name == "Shisui" then
				ST_Shisui:Set("✅ : Shisui")
			end
			if v.Name == "Wando" then
				ST_Wando:Set("✅ : Wando")
			end
			if v.Name == "Saddi" then
				ST_Saddi:Set("✅ : Saddi")
			end
		end
	end
	for i,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
		if v:IsA("Tool") then
			if v.Name == "Shisui" then
				ST_Shisui:Set("✅ : Shisui")
			end
			if v.Name == "Wando" then
				ST_Wando:Set("✅ : Wando")
			end
			if v.Name == "Saddi" then
				ST_Saddi:Set("✅ : Saddi")
			end
		end
	end
end
CheckStatus()
local AutoFarm = Tab:CreateSector("AutoFarm","Left")
AutoFarm:AddLabel("Check Status")
AutoFarm:AddButton("Open Fruit Inventory",function()
	game:GetService("Players").LocalPlayer.PlayerGui.Main.FruitInventory.Visible = true
end)
AutoFarm:AddButton("Open Fruit Awaken",function()
	game:GetService("Players").LocalPlayer.PlayerGui.Main.AwakeningToggler.Visible = true
end)
AutoFarm:AddButton("Open Fruit Store",function()
	game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("GetFruits")
    game.Players.localPlayer.PlayerGui.Main.FruitShop.Visible = true
end)
AutoFarm:AddButton("Open Inventory",function()
	game:GetService("Players").LocalPlayer.PlayerGui.Main.Inventory.Visible = true 
end)
AutoFarm:AddButton("Open Color Haki",function()
	game.Players.localPlayer.PlayerGui.Main.Colors.Visible = true
end)
AutoFarm:AddButton("Open Title Name",function()
	game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("getTitles")
    game.Players.localPlayer.PlayerGui.Main.Titles.Visible = true
end)
function isnil(thing)
	return (thing == nil)
end


spawn(function()
    while wait(.1) do
        pcall(function()
            if _G.Auto_Buy_Legendary_Sword or Triple_A then
                local args = {
                    [1] = "LegendarySwordDealer",
                    [2] = "2"
                }
                -- Triple_A
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
            else
				wait(2)
			end
        end)
    end
end)
