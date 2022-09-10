### GM:PlayerLoadedChar(client, char, lastChar)

Called when player loaded character

#### Example:

```lua
function PLUGIN:PlayerLoadedChar(client, char, lastChar)
    local data = char:getData("simpleData")

    if data then
        char:setLocalVar("simpleVar", data)
    end
end