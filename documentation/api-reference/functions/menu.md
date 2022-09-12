# ⚙ menu

### Is Menu Open :

```lua
menu.is_menu_open()
```

### Checkbox :

```lua
menu.create_checkbox(string szTab, string szSubsection, string szName)
```

### Color Picker :

```lua
menu.create_colorpicker(string szTab, string szSubsection, string szName, int szRed, int szGreen, int szBlue, int szAlpha)
```

### Key Bind :

<pre class="language-lua"><code class="lang-lua"><strong>menu.create_keybind(string szTab, string szSubsection, string szName)</strong></code></pre>

### Slider Integer :

```lua
menu.create_slider_int(szTab, szSubsection, szName, int szDefault, int szMin, int szMax)
```

### Slider Float :

```lua
menu.create_slider_float(szTab, szSubsection, szName, float szDefault, float szMin, float szMax)
```

### Dropdown :

```lua
menu.create_single_select(szTab, szSubsection, szName, szPreviousName, [optional] elements...)
```

### Multi Dropdown :

```lua
menu.create_multi_select(szTab, szSubsection, szName, szPreviousName, [optional] elements...)
```

### Spacing :

```lua
menu.create_spacing(string szTab, string szSubsection)
```

### Text :

```lua
menu.create_text(string szTab, string szSubsection, string szPreviousName)
```

### Set Visible :

```lua
menu.set_visible(string szReference, bool szValue) 
```

### Create Reference :

```lua
local reference = menu.create_reference("MISC", "Miscellaneous", "Anti Untrusted")
```

### Get Color Picker Value :

```lua
menu.get_colorpicker_value(string szReference)
```

### Set Value :

```lua
menu.set_value(string szReference, (int / float / bool / string) szValue)
```

### Get Value :

```lua
menu.get_value_int(string szReference)
menu.get_value_float(string szReference)

--To get the value of multiselect
menu.get_value_int(string szReference, int index)
```
