while true do
    local player = game:GetService("Players").LocalPlayer
    if player and player.Character and player.Character:FindFirstChild("Humanoid") then
        local args = {
            [1] = player.Character.Humanoid,
            [2] = 1
        }
        game:GetService("ReplicatedStorage").jdskhfsIIIllliiIIIdchgdIiIIIlIlIli:FireServer(unpack(args))
    end
    wait(0) -- Attendre une seconde entre chaque itération
end
