# Natural-disastre-Script

local kavoUi = loadstring(game:HttpGet("https://pastebin.com/raw/vff1bQ9F"))()
local Window = kavoUi.CreateLib("TheStrongestMaster Scripts", "DarkTheme")

-- Menu Tab
local MenuTab = Window:NewTab("Menu")
local MenuSection = MenuTab:NewSection("Menu")

MenuSection:NewButton("Carro Voador", "", function()
    loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Fly-Car-Mobile-gui-11884"))()
end)

MenuSection:NewButton("Super Ring", "", function()
    loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Super-ring-script-23171"))()
end)

MenuSection:NewButton("Balon Grátis", "", function()
    loadstring(game:HttpGet("https://rawscripts.net/raw/Free-CLIENTSIDED-Balloon-Giver!_175"))()
end)

-- Misc Tab
local MiscTab = Window:NewTab("Misc")
local MiscSection = MiscTab:NewSection("Misc")

MiscSection:NewButton("Shift Lock", "", function()
    loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-ShiftLock-17755"))()
end)

-- Credits Section (Mantido como está)
local Credits = Window:NewTab("Credits")
local CreditsSection = Credits:NewSection("Credits")

CreditsSection:NewLabel("Made by Deadly_Frenzy_")
CreditsSection:NewLabel("Sub to Deadly_Frenzy_ on YouTube")
CreditsSection:NewLabel("Follow deadly_frenzy_ on TikTok")
CreditsSection:NewLabel("Deadly_Frenzy_ Roblox Account: F0X42512")
CreditsSection:NewLabel("")
CreditsSection:NewLabel("imgood_atnameing_things helped me")
CreditsSection:NewLabel("Follow imgood_atnameing_things on TikTok")
CreditsSection:NewLabel("imgood_atnameing_things Roblox Account: duckarmy609")
