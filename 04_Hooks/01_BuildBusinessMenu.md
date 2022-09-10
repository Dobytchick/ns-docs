### GM:BuildBusinessMenu(panel)

Called when a business tab is being built

#### Example:

```lua
     -- Business menu don`t draw if player have citizen team

    PLUGIN:BuildBusinessMenu(pnl)
        if LocalPlayer():Team() == FACTION_CITIZEN then
            return false
        end
    end
```