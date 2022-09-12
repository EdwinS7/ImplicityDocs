# ⚙ Entity

### Get Local Player :

```lua
entity.get_local_player()
```

### Get Entity :

```lua
entity.get_entity(int iIndex)
```

### Get Weapon :

```lua
entity.get_weapon(uintptr_t iPtr)
```

### Get Class Name :

```lua
entity.get_class_name(uintptr_t iPtr)
```

### Get Class Id :

```lua
entity.get_class_id(uintptr_t iPtr)
```

### Get Max Entities :

```lua
entity.get_max_entities()
```

### Get Highest Entity Index :

```lua
entity.get_highest_entity_index()
```

### Is Valid :

```lua
entity.is_valid(uintptr_t iPtr)
```

### Is Player :

```lua
entity.is_player(uintptr_t iPtr)
```

### Is Dormant :

```lua
entity.is_dormant(uintptr_t iPtr)
```

### Is Alive :

```lua
entity.is_alive(uintptr_t iPtr)
```

### Is Enemy :

```lua
entity.is_enemy(uintptr_t iPtr)
```

### Is Player Bot :

```lua
entity.is_player_bot(uintptr_t iPtr)
```

### Get Bounding Box :

```lua
entity.get_bounding_box(uintptr_t iPtr)
```

### Get Hitbox Position :

```lua
entity.get_hitbox_position(uintptr_t iPtr , int iHitbox)
```

### Get Player Name :

```lua
entity.get_player_name(uintptr_t iPtr)
```

### Get Player User Id :

```lua
entity.get_player_userid(uintptr_t iPtr)
```

NOTE! Use the given style to get or set a prop Example Prop "DT\_BasePlayer" , "m\_vecVelocity\[0]" szProp is going to be "CBasePlayer->m\_vecVelocity\[0]"



### Get Prop Float :

```lua
entity.get_prop_float(uintptr_t iPtr, string szProp)
```

### Get Prop Integer :

```lua
entity.get_prop_int(uintptr_t iPtr, string szProp)
```

### Get Prop Vector3D

```lua
entity.get_prop_vector3d(uintptr_t iPtr, string szProp)
```

### Get Prop Vector2D

```lua
entity.get_prop_vector2d(uintptr_t iPtr, string szProp)
```

### Get Prop String :

```lua
entity.get_prop_string(uintptr_t iPtr, string szProp)
```

### Get Prop Array Int :

```lua
entity.get_prop_array_int(uintptr ptr , string szProp ,int index)
```

### Get Prop Array Float :

```lua
entity.get_prop_array_float(uintptr ptr , string szProp ,int index)
```

### Set Prop Float :

```lua
entity.set_prop_float(uintptr_t iPtr, string szProp , float flValue)
```

### Set Prop Integer :

```lua
entity.set_prop_int(uintptr_t iPtr, string szProp , int iValue)
```

### Set Prop Vector3D :

```lua
entity.set_prop_vector3d(uintptr_t iPtr, string szProp , Vector3D vecValue)
```

### Set Prop Vector2D :

```lua
entity.set_prop_vector2d(uintptr_t iPtr, string szProp , Vector2D vecValue)
```

### Set Prop String :

```lua
entity.set_prop_string(uintptr_t iPtr, string szProp , std::string szValue)
```

### Set Prop Array Int :

```lua
entity.set_prop_array_int(uintptr ptr , string szProp ,int index , int iValue)
```

### Set Prop Array Float :

```lua
entity.set_prop_array_float(uintptr ptr , string szProp ,int index , float flValue)
```
