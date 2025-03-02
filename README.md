local gameid = game.PlaceId

if gameid == 130992896 then  -- Ensure the correct PlaceId
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Nexus242/Verse-Piece/refs/heads/main/s"))()
elseif gameid == 866390529 then
    -- Ensure the URL points to the correct Lua script, not a Markdown file
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Nexus242/-/main/some_script.lua"))()  -- Replace "some_script.lua" with the actual Lua script file URL
end
