game:GetService("Players")https://github.com/KevinYTx/Breaking-Point-Script---Inf-Cash/releases/tag/v2.0(function()
game:GetService("VirtualUser"):ClickButton2(https://github.com/KevinYTx/Breaking-Point-Script---Inf-Cash/releases/tag/v2.0())
end)

if https://github.com/KevinYTx/Breaking-Point-Script---Inf-Cash/releases/tag/v2.0 == 648362523 then
    repeat wait() until game:IsLoaded()
    https://github.com/KevinYTx/Breaking-Point-Script---Inf-Cash/releases/tag/v2.0(
        "SendNotification",
        {
            Title = "Breaking Point AutoFarm Credits",
            Text = "Updated by Kevin.#1350, By Kevin_Programadxr in Roblox."
        }
    )
    
    
    
    Clone = game:GetService("Players")https://github.com/KevinYTx/Breaking-Point-Script---Inf-Cash/releases/tag/v2.0()
    game:GetService("Players")https://github.com/KevinYTx/Breaking-Point-Script---Inf-Cash/releases/tag/v2.0()
    https://github.com/KevinYTx/Breaking-Point-Script---Inf-Cash/releases/tag/v2.0 = game:GetService("Players")https://github.com/KevinYTx/Breaking-Point-Script---Inf-Cash/releases/tag/v2.0
    https://github.com/KevinYTx/Breaking-Point-Script---Inf-Cash/releases/tag/v2.0["Display Gun"].Value = true
    https://github.com/KevinYTx/Breaking-Point-Script---Inf-Cash/releases/tag/v2.0(
        function()
            if getgenv().AutoFarm then
                pcall(function()
                https://github.com/KevinYTx/Breaking-Point-Script---Inf-Cash/releases/tag/v2.0["Display Gun"].Value = true
                wait(4)
                Clone = game:GetService("Players")https://github.com/KevinYTx/Breaking-Point-Script---Inf-Cash/releases/tag/v2.0()
                game:GetService("Players")https://github.com/KevinYTx/Breaking-Point-Script---Inf-Cash/releases/tag/v2.0()
                https://github.com/KevinYTx/Breaking-Point-Script---Inf-Cash/releases/tag/v2.0 = game:GetService("Players")https://github.com/KevinYTx/Breaking-Point-Script---Inf-Cash/releases/tag/v2.0
                end)
            end
        end
    )

    while getgenv().AutoFarm do
        pcall(function()
        game:GetService("ReplicatedStorage").RemoteEvent:FireServer(16, "public")
        end)
        wait()
        for i, v in pairs(https://github.com/KevinYTx/Breaking-Point-Script---Inf-Cash/releases/tag/v2.0()) do
            if https://github.com/KevinYTx/Breaking-Point-Script---Inf-Cash/releases/tag/v2.0 == https://github.com/KevinYTx/Breaking-Point-Script---Inf-Cash/releases/tag/v2.0 then
            else
                pcall(function()
                game:GetService("ReplicatedStorage").RemoteEvent:FireServer(30, v)
                end)
            end
        end
    end
else
    game:GetService("TeleportService"):Teleport(648362523, LocalPlayer)
end


if getgenv().ServerHop == true then
wait (1500)
game:GetService("TeleportService"):Teleport(648362523, LocalPlayer)
end
