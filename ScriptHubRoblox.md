local library = loadstring(game:HttpGet("https://pastebin.com/raw/Vsm3NtME"))();

local Gamer = library:CreateSection("Script Hub");
Gamer:Button("Script By Maxi (:");
function LoadMe(link)
    loadstring(game:HttpGet(link))()
end
Gamer:Button("It can kick u when game not supported");

Gamer:Button("AlphaX(It Can Crash)", function()
    getgenv().http_request = http_request or request or (http and http.request) or syn.request 
repeat until http_request
loadstring(http_request({Url="https://cdn.applebee1558.com/alphax/alphax.lua",Method="GET"}).Body)()
end)
Gamer:Button("LumbSmasher (Need Key)", function()
getgenv().http_request = http_request or request or (http and http.request) or syn.request 
repeat until http_request
loadstring(http_request({Url="https://cdn.applebee1558.com/autoloader.lua",Method="GET"}).Body)()
end)
Gamer:Button("Project Evolution", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Project-Evolution/Main/main/Loader.lua", true))()
end)
Gamer:Button("MheeHub", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/BunnySalf/Hentai/main/MHEEHUB",true))()
end)
Gamer:Button("Ez Hub (More then 130 Games)", function()
loadstring(game:HttpGet(('https://raw.githubusercontent.com/debug420/Ez-Industries-Launcher-Data/master/Launcher.lua'),true))()
end)
Gamer:Button("CupCakeHub", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Toxic-Mods/Kupcake.Hub/main/Loader", true))()
end)
Gamer:Button("ShuShiScriptHub", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Farn2000/ShuShiScript/master/ShuShiScriptHub"))()
end)
Gamer:Button("JayHub", function()
loadstring(game:HttpGet("https://jack1214060.xyz/jayhub",true))()
end)
Gamer:Button("BloodGui(LumberTycoon)", function()
_G.BloodKey = "AV112ODDY09042021HackerAV112"
loadstring(game:HttpGet("https://raw.githubusercontent.com/BloodStillCool/666blood666/main/nil"))()
end)
Gamer:Button("Antarctic Hub", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/JusticeValley/Antarctic-Hub/main/New.lua", true))()
end)
Gamer:Button("CATIX HUB", function()
-- anti ban for  
-- Tapping Craze,
-- Tapping Mania,
-- Mining Legends, 
-- Saber Legends. 
    local sowd = getrawmetatable(game)
    local sucks = sowd.__namecall
    local player = game.Players.LocalPlayer
    setreadonly(sowd, false)
    sowd.__namecall = newcclosure(function(name, ...)
        local tabs = {
            ...
        }
        if getnamecallmethod() == "FireServer"  and tostring(name) == "UDPSocket" then
            return
        end
        return sucks(name, unpack(tabs)) 
    end) 
-- script/lodastring
loadstring(game:HttpGet("https://raw.githubusercontent.com/quentin452/CATIX-HUB/master/!Catix%20Hub", true))()
end)
Gamer:Button("RoxHub(NeedKey)", function()
Rox_Hub = true
loadstring(game:HttpGet("https://gist.githubusercontent.com/HaxxV1/d7cfdb5090e819a84a8db22fb113f39d/raw"))()
end)
Gamer:Button("PRIVAT(DONT USE)", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/EHUBWINNING/KRNL/main/Script.lua"))()
end)
library:Ready();
