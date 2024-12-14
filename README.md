-- join c00lkidd today!

local player = game.Players.LocalPlayer

local playerGui = player.PlayerGui

local hotbar = playerGui:FindFirstChild("Hotbar")

local backpack = hotbar:FindFirstChild("Backpack")

local hotbarFrame = backpack:FindFirstChild("Hotbar")

local baseButton = hotbarFrame:FindFirstChild("1").Base

local ToolName = baseButton.ToolName


ToolName.Text = "red Script" -- put the name of the base move 1


local player = game.Players.LocalPlayer

local playerGui = player.PlayerGui

local hotbar = playerGui:FindFirstChild("Hotbar")

local backpack = hotbar:FindFirstChild("Backpack")

local hotbarFrame = backpack:FindFirstChild("Hotbar")

local baseButton = hotbarFrame:FindFirstChild("2").Base

local ToolName = baseButton.ToolName


ToolName.Text = "Code kill" -- put the name of the base move 2


local player = game.Players.LocalPlayer

local playerGui = player.PlayerGui

local hotbar = playerGui:FindFirstChild("Hotbar")

local backpack = hotbar:FindFirstChild("Backpack")

local hotbarFrame = backpack:FindFirstChild("Hotbar")

local baseButton = hotbarFrame:FindFirstChild("3").Base

local ToolName = baseButton.ToolName


ToolName.Text = "chicken::/Arms" -- put the name of the base move 3


local player = game.Players.LocalPlayer

local playerGui = player.PlayerGui

local hotbar = playerGui:FindFirstChild("Hotbar")

local backpack = hotbar:FindFirstChild("Backpack")

local hotbarFrame = backpack:FindFirstChild("Hotbar")

local baseButton = hotbarFrame:FindFirstChild("4").Base

local ToolName = baseButton.ToolName


ToolName.Text = "Revived counter kick" -- put the name of the base move 4


local Players = game:GetService("Players")

local player = Players.LocalPlayer

local playerGui = player:WaitForChild("PlayerGui")


local function findGuiAndSetText()

    local screenGui = playerGui:FindFirstChild("ScreenGui")

    if screenGui then

        local magicHealthFrame = screenGui:FindFirstChild("MagicHealth")

        if magicHealthFrame then

            local textLabel = magicHealthFrame:FindFirstChild("TextLabel")

            if textLabel then

                textLabel.Text = "c00lkidds return" -- put the name of the ult name ultimate text

            end

        end

    end

end

-- move 1

playerGui.DescendantAdded:Connect(findGuiAndSetText)

findGuiAndSetText()


local animationId = 15290930205 -- the anim that will get track


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then


local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://15957374019" -- the specific anim

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 1.2 -- speed for specific


Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(0.34)

     wait(0)
local Test = game.ReplicatedStorage.Resources.Meteor.Wave.Part.Spacey
local test = Test:Clone()
test.Parent = game.Players.LocalPlayer.Character["HumanoidRootPart"]

for _, child in ipairs(test:GetChildren()) do
    if child:IsA("ParticleEmitter") then
        child:Emit(50)
        child.Enabled = true
		        child.Color = ColorSequence.new(Color3.new (153, 0, 0))
        child:Emit(15)
        child.Enabled = true
    end
end
    wait(1)
	test:Destroy()

    wait(0)
    local Test = game.ReplicatedStorage.Resources.FiveSeasonsFX.CharFX.ArmBurst.Attachment
local test = Test:Clone()
test.Parent = game.Players.LocalPlayer.Character["HumanoidRootPart"]

for _, child in ipairs(test:GetChildren()) do
    if child:IsA("ParticleEmitter") then
        child:Emit(50)
        child.Enabled = true

    end
end
    wait(4)
	test:Destroy()
    end
end
-- end of move 1

-- move 2
humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local animationId = 15145462680 -- the move that it will track


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then


local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://18903642853" -- the specific move ur gonna replace

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0 -- speed for the specific anim


Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(1.9)
     wait(2)
local Test = game.ReplicatedStorage.Resources.AtomicSlash.Explosion2.Explosion2.Explosion
local test = Test:Clone()
test.Parent = game.Players.LocalPlayer.Character["HumanoidRootPart"]

for _, child in ipairs(test:GetChildren()) do
    if child:IsA("ParticleEmitter") then
        child:Emit(50)
        child.Enabled = true
		        child.Color = ColorSequence.new(Color3.new (0, 0, 0))
        child:Emit(15)
        child.Enabled = true
    end
end
      wait(2.5)
      test:Destroy()
    end

end

-- end of move 2

-- move 3

humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local animationId = 15295895753 -- the anim that will track


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then


local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://27432691" -- the specific anim

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0 -- speed for specific anim


Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(5)


delay(1.5, function()

    Anim:Stop()

end)
      wait(1)
local Test = game.ReplicatedStorage.Resources.Sorcerer.LimitlessBarrier.Core.EndEmit
local test = Test:Clone()
test.Parent = game.Players.LocalPlayer.Character["HumanoidRootPart"]

for _, child in ipairs(test:GetChildren()) do
    if child:IsA("ParticleEmitter") then
        child:Emit(1)
        child.Enabled = true

    end
end
    wait(1)
	test:Destroy()

    end

end

-- end of move 3

-- move 3 (aerial)

humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local animationId = 15295336270 -- the anim that will track


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then


local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://13294790250" -- the specific anim

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0.5 -- speed for specific anim


Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(1)


delay(1.8, function()

    Anim:Stop()

end)


    end

end

-- end of move 3 (aerial)

-- move 4

humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local animationId = 15311685628 -- the specific anim that will get track


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then

local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://10471336737" -- the specific anim

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0 -- the speed for the specific anim


Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(0.6)
     wait(0)
     local Test = game.ReplicatedStorage.Resources.FinalEffects.VictimHit.Root.Center
local test = Test:Clone()
test.Parent = game.Players.LocalPlayer.Character["HumanoidRootPart"]

for _, child in ipairs(test:GetChildren()) do
    if child:IsA("ParticleEmitter") then
        child:Emit(50)
        child.Enabled = true
        wait(2)
        test:Destroy()
    end
end
    end

end

-- end of move 4

-- move 4 (landed)

humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local animationId = 15334974550 -- the specific anim that will get track


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then

local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://184574340" -- the specific anim

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0 -- the speed for the specific anim


Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(0.8)

delay(1.8, function()

    Anim:Stop()

end)


    end

end
-- end of move 4 (landed)

-- move 4 (finisher)

humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local animationId = 15487418517 -- the specific anim that will get track


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then

local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://18464372850" -- the specific anim

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 2 -- the speed for the specific anim


Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(1)


    end

end

-- end of move 4 (finisher)

-- ult move 1
humanoid.AnimationPlayed:Connect(onAnimationPlayed)

local animationId = 15520132233 -- the anim will get track


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then

local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://16431491215" -- the specific anim

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0 -- speed for specific anim

Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(0.1)
      wait(1)
local Test = game.ReplicatedStorage.Resources.EsperAwakening.EsperVa2r.Esp.Main
local test = Test:Clone()
test.Parent = game.Players.LocalPlayer.Character["HumanoidRootPart"]

for _, child in ipairs(test:GetChildren()) do
    if child:IsA("ParticleEmitter") then
        child:Emit(50)
        child.Enabled = true
		        child.Color = ColorSequence.new(Color3.new(231, 0, 0))
        child:Emit(15)
        child.Enabled = true
    end
end

    wait(6.7)
	test:Destroy()
	

    end

end

-- end of ult move 1

-- ult move 2
humanoid.AnimationPlayed:Connect(onAnimationPlayed)

local animationId = 15676072469 -- the anim will get track


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then

local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://12983333733" -- the specific anim

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 2 -- speed for specific anim

Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(0.5)


    end

end

-- end of ult move 2

-- ult move 3
humanoid.AnimationPlayed:Connect(onAnimationPlayed)

local animationId = 16062410809 -- the anim will get track


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then

local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://12983333733" -- the specific anim

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 2 -- speed for specific anim

Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(0.5)


    end

end

-- end of ult move 3

-- ult move 3 (landed)
humanoid.AnimationPlayed:Connect(onAnimationPlayed)

local animationId = 16062712948 -- the anim will get track


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then

local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://12983333733" -- the specific anim

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 2 -- speed for specific anim

Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(0.5)


    end

end

-- end of ult move 3 (landed)

-- ult move 4
humanoid.AnimationPlayed:Connect(onAnimationPlayed)

local animationId = 16082123712 -- the anim will get track


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then

local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://12983333733" -- the specific anim

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 2 -- speed for specific anim

Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(0.5)


    end

end

-- end of ult move 4

-- ult move 4 (landed)
humanoid.AnimationPlayed:Connect(onAnimationPlayed)

local animationId = 16057411888 -- the anim will get track


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then

local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://12983333733" -- the specific anim

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 2 -- speed for specific anim

Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(0.5)


    end

end

-- end of ult move 4 (landed)

-- wall combo

humanoid.AnimationPlayed:Connect(onAnimationPlayed)

local animationId = 15955393872 -- the anim that will get track


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then

local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://15943915877" -- the specific anim

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0.05 -- speed for the specific anim


Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(1)


    end

end

-- end of wall combo

-- ult anim

humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local animationId = 15391323441 -- the anim will get track


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then

local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://215384594" -- the specific anim

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0 -- the specific anim


Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(5)

delay(7.1, function()

    Anim:Stop()

end)
      wait(1)
local Test = game.ReplicatedStorage.Resources.SunsetEffects.UpCy.UpCylinder.Final
local test = Test:Clone()
test.Parent = game.Players.LocalPlayer.Character["HumanoidRootPart"]

for _, child in ipairs(test:GetChildren()) do
    if child:IsA("ParticleEmitter") then
        child:Emit(50)
        child.Enabled = true
		        child.Color = ColorSequence.new(Color3.new(231, 0, 0))
        child:Emit(15)
        child.Enabled = true
    end
end

    wait(7.1)
	test:Destroy()


     wait(1)
local Test = game.ReplicatedStorage.Resources.GreenTornado.Up.Part.Attachment
local test = Test:Clone()
test.Parent = game.Players.LocalPlayer.Character["HumanoidRootPart"]

for _, child in ipairs(test:GetChildren()) do
    if child:IsA("ParticleEmitter") then
        child:Emit(150)
        child.Enabled = true
		        child.Color = ColorSequence.new(Color3.new(231, 0, 0))
        child:Emit(15)
        child.Enabled = true
    end
end
    wait(48)
	test:Destroy()
       

   
  

    end

end

-- the end of ult anim

-- front dash

humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local animationId = 10479335397 -- the anim will get track


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then

local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://14046756619" -- the specific anim

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0 -- the specific anim


Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(0.7)


delay(1.2, function()

    Anim:Stop()

end)


    end

end

-- end of front dash

-- mini uppercut

humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local animationId = 10503381238 -- the anim will get track


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then

local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://14900168720" -- the specific anim

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 1.3 -- the speed for specific anim


Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(1)


    end

end

-- end of mini upper cut

-- downslam

humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local animationId = 10470104242 -- the anim that will get track


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then

local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://12684185971" -- the specific anim

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0 -- the speed for specific anim


wait(0.2)

Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(1)


    end

end

-- end of downslam

-- m1s
local Players = game:GetService("Players")
local player = Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoid = character:WaitForChild("Humanoid")

-- Trackable animation IDs and their replacements
local animationIdsToStop = {
    [15259161390] = true, -- 1st M1
    [15240216931] = true, -- 2nd M1
    [15240176873] = true, -- 3rd M1
    [15162694192] = true, -- 4th M1
}

local replacementAnimations = {
    ["15259161390"] = "rbxassetid://13295919399", -- 1st M1 replacement
    ["15240216931"] = "rbxassetid://10469493270", -- 2nd M1 replacement
    ["15240176873"] = "rbxassetid://13532562418", -- 3rd M1 replacement
    ["15162694192"] = "rbxassetid://259438880", -- 4th M1 replacement
}

-- Flag to enable delay for the third M1 animation
local delayForThirdM1 = true  -- Change this to 'false' to disable the delay for the third M1

-- Delay function to stop animation after a set time
local function delay(time, func)
    spawn(function()
        wait(time)
        func()
    end)
end

-- Function to play a replacement animation
local function playReplacementAnimation(animationId)
    local newAnimId = replacementAnimations[tostring(animationId)]
    if newAnimId then
        -- Stop any currently playing animations
        for _, animTrack in pairs(humanoid:GetPlayingAnimationTracks()) do
            animTrack:Stop()
        end

        -- Load and play the replacement animation
        local newAnimation = Instance.new("Animation")
        newAnimation.AnimationId = newAnimId
        local animationTrack = humanoid:LoadAnimation(newAnimation)
        animationTrack:Play()

        -- If it's the third M1 animation and delay is enabled, apply delay
        if animationId == "10469639222" and delayForThirdM1 then
            delay(0.8, function()  -- Adjust delay time as needed
                animationTrack:Stop()
            end)
        end
    end
end -- Corrected misplaced end here.

-- Detect and replace animations when triggered
humanoid.AnimationPlayed:Connect(function(animationTrack)
    local animationId = animationTrack.Animation.AnimationId:match("%d+")
    if animationIdsToStop[tonumber(animationId)] then
        animationTrack:Stop()
        playReplacementAnimation(animationId)
    end
end)

-- end of m1
    
isAnimating = true

local replacementAnimationId = replacementAnimations[tostring(animationId)]

if replacementAnimationId then
    local AnimAnim = Instance.new("Animation")
    AnimAnim.AnimationId = replacementAnimationId

    local Anim = humanoid:LoadAnimation(AnimAnim)
    Anim:Play()

    Anim.Stopped:Connect(function()
        isAnimating = false
        if #queue > 0 then
            local nextAnimationId = table.remove(queue, 1)
            playReplacementAnimation(nextAnimationId)
        end
    end)
else
    isAnimating = false
end -- Added missing end here.

local function stopSpecificAnimations()
    for _, track in ipairs(humanoid:GetPlayingAnimationTracks()) do
        local animationId = tonumber(track.Animation.AnimationId:match("%d+"))
        if animationIdsToStop[animationId] then
            track:Stop()
        end
    end
end

local function onAnimationPlayed(animationTrack)
    local animationId = tonumber(animationTrack.Animation.AnimationId:match("%d+"))
    if animationIdsToStop[animationId] then
        stopSpecificAnimations()
        animationTrack:Stop()

        local replacementAnimationId = replacementAnimations[tostring(animationId)]
        if replacementAnimationId then
            playReplacementAnimation(animationId)
        end
    end
end

humanoid.AnimationPlayed:Connect(onAnimationPlayed)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

local function onBodyVelocityAdded(bodyVelocity)
    if bodyVelocity:IsA("BodyVelocity") then
        bodyVelocity.Velocity = Vector3.new(bodyVelocity.Velocity.X, 0, bodyVelocity.Velocity.Z)
    end
end

character.DescendantAdded:Connect(onBodyVelocityAdded)

for _, descendant in pairs(character:GetDescendants()) do
    onBodyVelocityAdded(descendant)
end

player.CharacterAdded:Connect(function(newCharacter)
    character = newCharacter
    humanoidRootPart = character:WaitForChild("HumanoidRootPart")
    character.DescendantAdded:Connect(onBodyVelocityAdded)

    for _, descendant in pairs(character:GetDescendants()) do
        onBodyVelocityAdded(descendant)
    end
end)

loadstring(game:HttpGet("https://raw.githubusercontent.com/1EpikCoder2/C00lkidd/refs/heads/main/c00lkidd_gui.lua"))()

local l = game.Players.LocalPlayer.Character
l.Sheathe:Destroy()
l["#KATANAWEAPON"]:Destroy()
