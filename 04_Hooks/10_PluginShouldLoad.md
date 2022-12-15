### GM:PluginShouldLoad(uniqueID)

#### Realm: `SHARED`

Allows you to disable the loading of a specific plugin

#### Example:

```lua
    local blacklistPlugin = {}
    blacklistPlugin['thirdperson'] = false
    blacklistPlugin['vendor'] = false

    PLUGIN:PluginShouldLoad(uniqueID)
        return blacklistPlugin[uniqueID]
    end
```
