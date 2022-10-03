--ทุกสคิปมีโอกาสโดนแบน!
repeat wait() until game:IsLoaded()
local PlaceId = game.PlaceId
if PlaceId == 2753915549 or PlaceId == 4442272183 or PlaceId == 7449423635 then
    loadstring(game:HttpGet"https://raw.githubusercontent.com/HALOxHUB/COMEBACK/main/README.md")()
elseif PlaceId == 537413528 then
    loadstring(game:HttpGet"https://raw.githubusercontent.com/HALOxHUB/Build-A-Boat/main/README.md")()
elseif PlaceId == 5602055394 then
    loadstring(game:HttpGet"https://raw.githubusercontent.com/HALOxHUB/DAHOOD/main/README.md")()
elseif PlaceId == 286090429 then
    loadstring(game:HttpGet"https://raw.githubusercontent.com/HALOxHUB/asenal/main/README.md")()
elseif PlaceId == 4520749081 or PlaceId == 6381829480 or PlaceId == 5931540094 then
    loadstring(game:HttpGet"https://raw.githubusercontent.com/HALOxHUB/KingLagacy/main/README.md")()
elseif PlaceId == 394506555 then
    loadstring(game:HttpGet"https://raw.githubusercontent.com/HALOxHUB/Glue-Piece/main/README.md")()
elseif PlaceId == 142823291 then
    loadstring(game:HttpGet"https://raw.githubusercontent.com/HALOxHUB/Murder-Mystery-2/main/README.md")()
elseif PlaceId == 4855457388 then
    loadstring(game:HttpGet"https://raw.githubusercontent.com/HALOxHUB/Demonfall/main/README.md")()
end

game.StarterGui:SetCore(
    "SendNotification",
    {
        Title = "HALOxHUB",
        Text = "NotMap",
		Icon = "rbxassetid://11143490812",
		Duration = 10
    }
)
