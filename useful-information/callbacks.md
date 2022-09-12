# 📋 Callbacks

### Set Event Callback :

```lua
local function Paint() 
    --Code here!
end

client.set_event_callback("paint_traverse", Paint);
```

### Available Callbacks :

```
"frame_net_update_start"
"frame_net_update_postdataupdate_start"
"frame_net_update_postdataupdate_end"
"frame_net_update_end"
"frame_render_start"
"frame_render_end"
"paint_traverse"
"pre_engine_prediction"     // runs before engine prediction
"in_engine_prediction"    // runs after running engine prediction and before any software feature runs
"post_engine_prediction"  // runs after engine prediction and software features
"aim_hurt"
"aim_fire"
"aim_miss"
"local_anim_start"
"local_anim_pre_update"
"local_anim_post_update"
"local_anim_end"
```

### Accessing UserCmd :

```lua
--NOTE! UserCmd is only accessible in "pre_engine_prediction" , "in_engine_prediction"  and "post_engine_prediction" callbacks

local function PreEnginePrediction(cmd) --ref cmd : CUserCmd DataType
    client.log(cmd.command_number)
end
 
client.set_event_callback("pre_engine_prediction", PreEnginePrediction); 
```

### Accessing Aim Events :

```lua
local function callback(event) --ref : AimHurt_t , AimFire_t , AimMiss_t
    local aimplayer = event.aim_player;
end

-- ( "aim_fire", "aim_miss", "aim_hurt" )
client.set_event_callback("aim_hurt" ,callback);
```

### Game Event Accessors :

```lua
event.get_bool(uintptr ptr , std::string szKey)
event.get_int(uintptr ptr , std::string szKey)
event.get_unsigned_int_64(uintptr ptr , std::string szKey)
event.get_float(uintptr ptr , std::string szKey)
event.get_string(uintptr ptr , std::string szKey)
event.get_wide_string(uintptr ptr , std::string szKey)
event.get_pointer(uintptr ptr , std::string szKey)
```

#### Example :

```lua
local function PlayerHurt(ptr) 
   local m_damage = event.get_int(ptr,"dmg_health");
end

client.set_event_callback("player_hurt", PlayerHurt);
```

#### Available Game Events :

[https://wiki.alliedmods.net/Counter-Strike:\_Global\_Offensive\_Events](https://wiki.alliedmods.net/Counter-Strike:\_Global\_Offensive\_Events)
