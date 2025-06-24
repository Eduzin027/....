if gameId == 2753915549 or gameId == 4442272183 or gameId == 7449423635 then
    local Tab = Window:MakeTab({Name = "Blox Fruits", Icon = "rbxassetid://4483345998", PremiumOnly = false})

    Tab:AddButton({
        Name = "Auto Farm Level",
        Callback = function()
            loadstring(game:HttpGet("https://raw.githubusercontent.com/eduardohub/scripts/main/bloxfruits_autofarm.lua"))()
        end
    })
