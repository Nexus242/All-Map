local gameid = game.PlaceId

if gameid == 130992896367999 then  -- Ensure the correct PlaceId
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Nexus242/Verse-Piece/refs/heads/main/s"))()
elseif gameid == 86639052909924 then
    -- Ensure the URL points to the correct Lua script, not a Markdown file
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Nexus242/-/refs/heads/main/README.md"))()
end
