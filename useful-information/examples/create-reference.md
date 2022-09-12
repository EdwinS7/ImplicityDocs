# 📎 Create reference

```lua
--https://edwn.gitbook.io/api-docs/documentation/api-reference/menu-dump
local Enable_Fakelag = menu.create_reference("ANTI-AIMBOT", "Fakelag", "Enabled")

client.set_event_callback( "paint_traverse", function()
    print(menu.get_value_int(Enable_Fakelag)) --1 if true, 0 if false.
end)
```
