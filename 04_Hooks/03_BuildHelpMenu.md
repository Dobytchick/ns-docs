### GM:BuildHelpMenu(panel)

#### Realm: `CLIENTSIDE`

Called when the help menu is being built. You can add your own tabs.

#### Example:

```lua
    PLUGIN:BuildHelpMenu(tabs)
        tabs["Simple Help Node"] = function(node)
            gui.OpenURL("https://www.google.com/")
        end
    end
```