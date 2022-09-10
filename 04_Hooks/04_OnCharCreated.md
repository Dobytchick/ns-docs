### GM:OnCharCreated(client, id)

This hook builds help menu.

#### Example:

```lua
    PLUGIN:OnCharCreated(client, id)
        local char = nut.char.list[id]

        char:setData("simpleData", "simpleDataValue")
    end
```