--um
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()

--windown

local Window = Library.CreateLib("kakakak", "LightTheme")

--tabs
local Tab = Window:NewTab("samuel")


Section:NewLabel("meu primeiro script")

--começo


Section:NewButton("tuturial botão", "teste para o script", function()
    print"davi"
end)
--togles usavel

Section:NewToggle("speed", "ToggleInfo", function(state)
    if state then
        print"speed on"
    else
        print("Toggle Off")
    end
end)


--slider


Section:NewToggle("ToggleText", "ToggleInfo", function(state)
    if state then
        print("Toggle On")
    else
        print("Toggle Off")
    end
end)
